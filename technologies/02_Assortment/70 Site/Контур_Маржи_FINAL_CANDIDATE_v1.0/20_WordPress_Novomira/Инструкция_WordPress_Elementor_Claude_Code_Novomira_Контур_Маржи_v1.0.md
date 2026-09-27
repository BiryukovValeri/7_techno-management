# Инструкция WordPress / Elementor / Claude Code / Novomira

Проект: Контур Маржи  
Статус: подготовка production-переноса после принятой версии Claude Design v1.2  
Цель: перенести сайт технологии в WordPress без потери визуального кода, структуры, SEO/GEO, CTA, mobile и редактируемости.

## 1. Главное решение переноса

Контур Маржи переносится не как скриншот и не как сырой Claude Design bundle.

Правильная схема:

1. Claude Design дает чистый production HTML и ассеты.
2. Claude Code разбирает HTML на карту переноса.
3. WordPress / Elementor собирает страницу `/kontur-marzhi/`.
4. Novomira переносит структуру, стили, ассеты, SEO, форму и блоговый контур.
5. После переноса выполняется QA на WordPress-preview.

Рекомендуемый способ сборки: гибридный Elementor.

- Elementor / Containers: редактируемые текстовые секции, карточки, CTA, FAQ, материалы, формы.
- Custom HTML / CSS component: сложный hero, cinematic-сцены, декоративные линии, lightbox визуализаций, если Elementor не сохраняет точность.
- WordPress posts: раздел материалов / блог.
- SEO plugin: title, description, canonical, OG, Twitter, JSON-LD, если Novomira не управляет этим напрямую.

## 1A. Что реально дает Novomira

По локальному пакету Novomira: это MCP-сервер для WordPress, который дает агенту доступ к WordPress через PHP execution, файловые операции и WP-CLI. Использовать только на staging / dev-среде до финальной приемки.

Доступные возможности, которые важны для переноса:

1. `novamira/discover-abilities` - посмотреть доступные действия.
2. `novamira/agent-context` - получить контекст WordPress-сайта.
3. `novamira/list-directory` / `read-file` - изучить тему, плагины и структуру.
4. `novamira/create-upload-link` - загрузить ZIP, изображения, WebP, OG и другие большие файлы.
5. `novamira/write-file` / `edit-file` - точечно создать или править файлы темы / child theme / snippets.
6. `novamira/run-wp-cli` - проверить плагины, страницы, медиа, поля, posts, permalinks.
7. `novamira/create-admin-access-link` - временный вход в wp-admin для браузерной проверки.

Ограничение: Novomira не заменяет архитектуру переноса. Она выполняет перенос. Поэтому до работы через Novomira нужен чистый transfer package и карта секций.

## 1B. Принцип безопасности

Перед подключением Novomira:

1. Работать сначала на staging / тестовом поддомене.
2. Сделать backup WordPress и базы.
3. Включать Novomira AI Abilities только на время работы.
4. Не давать агенту задачу "сделай красиво" или "сам реши".
5. Запретить удаление файлов и массовую перезапись темы без отдельного разрешения.
6. Все изменения делать через child theme, Elementor page, Custom CSS / Code Snippets или отдельный безопасный plugin-snippet.
7. Production-публикация только после QA-gate.

## 1C. Выбор Elementor / Gutenberg

В старых материалах по WordPress есть рекомендация Block Theme / Gutenberg и запрет Elementor. Для текущего проекта это не принимается как обязательное правило, потому что утвержденная цепочка сейчас: Claude Design -> WordPress / Elementor -> Novomira.

Берем из старых материалов только инженерные требования:

- редактируемость;
- чистая структура;
- медиатека WordPress;
- блог / материалы как WordPress posts;
- SEO/GEO;
- доступность;
- скорость;
- отсутствие мусора Claude Design в production.

Elementor допустим, если не превращает страницу в тяжелую кашу из вложенных контейнеров и сохраняет mobile.

## 2. Пакет, который должен лежать на входе

Создать папку:

`Контур_Маржи_NOVOMIRA_TRANSFER_v1.0`

Внутри:

1. `01_source/`
   - `production/index.html` или `transfer/index.html`;
   - если есть только standalone HTML, положить его сюда и отметить как источник для извлечения, а не прямой публикации.

2. `02_assets/`
   - `assets/vizw/` - 12 WebP-визуализаций для сайта;
   - `assets/viz/` - PNG-оригиналы визуализаций;
   - `assets/images/` - 6 финальных изображений для image slots;
   - `assets/og/og-kontur-marzhi.jpg` - OG-картинка 1200x630.

3. `03_transfer_docs/`
   - `Перенос_в_WordPress_Novomira_Контур_Маржи_v1.1.md`;
   - QA-отчет Claude Design v1.2;
   - этот файл-инструкция.

4. `04_wordpress_fields/`
   - будущий файл с SEO-полями;
   - будущий файл с формой заявки;
   - будущий файл с картой ссылок.

5. `05_qa/`
   - скриншоты после переноса: 1440, 430, 390, 360;
   - итоговый акт `GO / NOT GO`.

Не передавать в Novomira как production:

- `_ds`;
- `ref`;
- `uploads` с Design System;
- Claude runtime;
- `x-dc`;
- bundler-слой;
- placeholder / prompt / negative prompt в публичном HTML.

## 3. Настройка WordPress

1. Подготовить staging:
   - сайт не должен быть production до финального QA;
   - включить SSL;
   - выставить постоянные ссылки `post name`;
   - проверить, что сайт индексируется только после разрешения.

2. Установить / включить плагины:
   - Elementor;
   - Elementor Pro или отдельный forms-плагин, если формы не закрываются базовым стеком;
   - SEO-плагин, который позволит управлять title, description, canonical, OG, Twitter, JSON-LD;
   - Novomira;
   - плагин для безопасного custom CSS / snippets, если не используется child theme.

3. Подключить Novomira:
   - установить `novamira.zip`;
   - активировать plugin;
   - открыть страницу Novomira в wp-admin;
   - скачать / подключить MCPB для нужного сайта;
   - включить AI Abilities только на период работы;
   - проверить через Claude Code / MCP `discover-abilities`.

4. Создать страницу:
   - название: `Контур Маржи`;
   - slug: `/kontur-marzhi/`;
   - шаблон: Elementor Canvas или Full Width;
   - скрыть стандартный title темы, если он дублирует H1.

5. Настроить глобальные элементы:
   - header: ссылка на C-Level Insight / главный сайт, меню технологии, CTA `Диагностика`;
   - footer: C-Level Insight, 7 технологий, материалы, контакты, политика.

6. Настроить медиатеку:
   - загрузить WebP-визуализации для публичной страницы;
   - загрузить PNG-оригиналы только если нужны для полноэкранного просмотра / скачивания;
   - загрузить 6 финальных изображений image slots;
   - загрузить OG-картинку.

7. Настроить блоговый контур:
   - для MVP использовать обычные WordPress posts;
   - создать рубрику `Материалы`;
   - создать подрубрики или теги: `Разборы маржи`, `Кейсовые заметки`, `Ошибки управления`, `Связки технологий`;
   - карточки материалов на странице должны вести на реальные будущие slugs или на черновики.

8. Настроить форму:
   - место формы: финальный CTA-блок;
   - обязательные поля: имя, компания, должность, email/телефон, что сейчас неуправляемо, комментарий;
   - visible label у каждого поля;
   - CTA: `Запросить платную Диагностику`;
   - обработчик: Elementor Form / WPForms / Fluent Forms / Novomira form module;
   - после отправки: сообщение о получении заявки, без обещания результата без Диагностики.

## 4. Настройка Elementor

Использовать Elementor не как конструктор случайных карточек, а как систему редактируемых секций.

Обязательные секции страницы:

1. Hero.
2. Лента разделов.
3. Что открывает Контур Маржи.
4. Ситуация.
5. Ядро технологии.
6. Где течет маржа.
7. Карта утечки.
8. Красная зона.
9. Владелец красной зоны.
10. Это не.
11. Управляемость.
12. Продуктовая линейка.
13. Визуализации.
14. Кейсы.
15. Материалы.
16. Стоимость и границы.
17. FAQ.
18. CTA и форма.
19. Footer.

Правила Elementor-сборки:

- каждый блок должен быть редактируемым;
- H1 только один;
- H2 у секций;
- H3 у карточек и продуктов;
- визуализации вставлять как Image widget или gallery/lightbox, не как фон без alt;
- сложные cinematic-сцены можно оставить как HTML/CSS component;
- не ломать мягкие радиусы 14-28px;
- не превращать страницу в dashboard / BI / финансовую панель;
- mobile проверять отдельно на 360 / 390 / 430.

## 5. Что должен сделать Claude Code до Novomira

Claude Code не должен редизайнить сайт. Его задача - технически разобрать пакет и подготовить перенос.

Промпт для Claude Code:

```text
Ты senior WordPress / Elementor engineer.

Нужно подготовить перенос сайта технологии Контур Маржи из Claude Design в WordPress / Elementor / Novomira.

Не редизайнь сайт. Не меняй тексты. Не меняй art direction.

На входе:
1. production/index.html или transfer/index.html;
2. assets/vizw/;
3. assets/viz/;
4. assets/images/ с финальными изображениями;
5. og-kontur-marzhi.jpg;
6. Перенос_в_WordPress_Novomira_Контур_Маржи_v1.1.md;
7. QA-отчет Claude Design v1.2.

Сделай:
1. elementor-transfer-map.md - карта 19 секций: что собирается Elementor widgets/containers, что остается custom HTML/CSS;
2. wordpress-assets-map.md - список ассетов, куда грузить, какие alt, какие размеры;
3. seo-geo-fields.md - title, description, canonical, OG, Twitter, JSON-LD, robots;
4. form-spec.md - поля формы, labels, required, success message, privacy note;
5. content-links-map.md - все CTA, anchors, будущие slugs материалов;
6. novomira-handoff.md - короткое ТЗ для Novomira;
7. qa-after-transfer.md - чеклист проверки после переноса.

Требования:
- не публиковать standalone bundle как финальный сайт;
- не переносить служебные папки _ds, ref, uploads, runtime, x-dc;
- сохранить desktop/mobile внешний вид;
- сохранить структуру 19 секций;
- сохранить блоговый контур Материалы;
- сохранить блок "Это не";
- сохранить CTA на платную Диагностику;
- проверить, что в публичный слой не попали prompt, placeholder, TODO, browse files.
```

## 6. Что передавать в Novomira

Передавать не хаотичную папку, а чистый пакет:

1. `production/index.html` или `transfer/index.html`;
2. `assets/vizw/`;
3. `assets/viz/`;
4. `assets/images/`;
5. `assets/og/og-kontur-marzhi.jpg`;
6. `Перенос_в_WordPress_Novomira_Контур_Маржи_v1.1.md`;
7. `elementor-transfer-map.md`;
8. `wordpress-assets-map.md`;
9. `seo-geo-fields.md`;
10. `form-spec.md`;
11. `content-links-map.md`;
12. `qa-after-transfer.md`;
13. письмо сопровождения для Novomira.

## 7. SEO / GEO после переноса

В WordPress должны быть настроены:

- `title`;
- `description`;
- `canonical`;
- `robots`;
- OpenGraph: title, description, image, url, type, locale, site_name;
- Twitter Card;
- JSON-LD: Organization, WebSite, WebPage, BreadcrumbList, Service + OfferCatalog, FAQPage;
- alt у всех визуализаций и изображений;
- нормальная H-структура;
- рубрика материалов.

Важно: если SEO-плагин сам генерирует schema, не дублировать JSON-LD. Должен быть один согласованный источник schema.

## 8. QA после переноса

Страница получает GO на публикацию только если:

1. На странице один H1.
2. Нет горизонтального скролла на 360 / 390 / 430.
3. Hero выглядит как принятый art direction.
4. Все CTA ведут в рабочие места.
5. Форма отправляет заявку.
6. Все поля формы имеют visible labels.
7. Все изображения имеют alt.
8. В публичной странице нет prompt, placeholder, TODO, browse files, negative prompt.
9. Блок `Материалы` есть и связан с WordPress posts.
10. Блок `Это не` есть и не превращен в агрессивное сравнение.
11. JSON-LD валиден и не продублирован.
12. Страница читается без JS.
13. `prefers-reduced-motion` отключает motion.
14. Вес страницы после оптимизации приемлем для WordPress.
15. Десктоп и mobile соответствуют принятой версии.

## 9. Текущий следующий шаг

Сейчас нужно не редизайнить сайт, а собрать чистый Novomira transfer package:

1. Положить финальный v1.2 HTML и ZIP в `01_source/`.
2. Достать из ZIP только нужные ассеты в `02_assets/`.
3. Добавить 6 финальных изображений и OG-картинку.
4. Заменить домен `c-level-insight.ru` на фактический домен / поддомен.
5. Запустить Claude Code по промпту из раздела 5.
6. После Claude Code передать Novomira чистый пакет из раздела 6.
7. После переноса проверить gates из раздела 8.
