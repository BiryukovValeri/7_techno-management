# ЗАДАНИЕ CLAUDE DESIGN — «АРХИТЕКТУРА ПЕРЕГОВОРОВ»

Claude, тебе передаётся не исследовательская задача и не просьба придумать технологию или сайт с нуля.

Technology Truth, Message Strategy, публичная архитектура, контент, продуктовая модель, 12 модельных кейсов, Forms 17–23, SEO/GEO-контур, визуальные классы, FINAL Hero и production stack уже определены.

Твоя задача — профессионально применить приложенную выбранную Design System и спроектировать законченный responsive design сайта nego.7vctr.ru, сохранив переданные знания и ограничения.

## 1. Что приложено
1. Папка 07_CLAUDE_DESIGN_PACKAGE, файлы 00–09.
2. FINAL Hero image — отдельный Owner-approved файл. Считать его LOCK: использовать, не перерисовывать.
3. Выбранная Design System — отдельное приложение. Это основная визуальная система сайта.
4. Исходные Technology Visualizations хранятся в GitHub. Используй именно эти source assets и не подменяй их собственной реконструкцией:

01 — Ядро Архитектуры Переговоров:
https://github.com/BiryukovValeri/7_techno-management/blob/codex/site-factory/technologies/03_Negotiations/80%20%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F/%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0_%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BE%D0%B2%D0%BE%D1%80%D0%BE%D0%B2_%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_01_%D0%AF%D0%B4%D1%80%D0%BE_%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D1%8B_%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BE%D0%B2%D0%BE%D1%80%D0%BE%D0%B2_V1.png

02 — Переговорное поле:
https://github.com/BiryukovValeri/7_techno-management/blob/codex/site-factory/technologies/03_Negotiations/80%20%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F/%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0_%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BE%D0%B2%D0%BE%D1%80%D0%BE%D0%B2_%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_02_%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BE%D0%B2%D0%BE%D1%80%D0%BD%D0%BE%D0%B5_%D0%9F%D0%BE%D0%BB%D0%B5_V1.png

05 — BATNA / ZOPA:
https://github.com/BiryukovValeri/7_techno-management/blob/codex/site-factory/technologies/03_Negotiations/80%20%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F/%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0_%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BE%D0%B2%D0%BE%D1%80%D0%BE%D0%B2_%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_05_BATNA_ZOPA_V1.png

12 — Антипозиционирование, OPTIONAL:
https://github.com/BiryukovValeri/7_techno-management/blob/codex/site-factory/technologies/03_Negotiations/80%20%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F/%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0_%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BE%D0%B2%D0%BE%D1%80%D0%BE%D0%B2_%D0%92%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F_12_%D0%90%D0%BD%D1%82%D0%B8%D0%BF%D0%BE%D0%B7%D0%B8%D1%86%D0%B8%D0%BE%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_V1.png

5. Полный исходный корпус 12 кейсов хранится в GitHub:
technologies/03_Negotiations/50 Кейсы/

Точный manifest 12 source DOCX с path, blob SHA и GitHub link находится в 04A_CASE_SOURCE_MANIFEST.md. Это обязательный источник для case detail pages; сокращённый CASE_CONTENT_MASTER не заменяет полное тело кейса.

Если приложение физически не передано, не заменяй его собственной генерацией. Проектируй корректное TBD/no-image состояние и отметь dependency.

## 2. Что нельзя переосмысливать
- одна технология, два поля применения: внешнее и внутреннее;
- канонический цикл из 10 шагов;
- ровно четыре продукта: Диагностика / Сессия / Спринт / Сопровождение;
- Forms 17–23; Form 24 не существует;
- соглашение не является обязательным признаком хорошего решения;
- кейсы — модельные/учебные, не testimonials и не доказательства результатов клиентов;
- нет обещаний победы, ROI, win-rate, маржи или гарантированного эффекта;
- нет психологического профилирования, скрытой манипуляции, AI-продукта или SaaS;
- публичный язык — русский.

## 3. Визуальные классы
Не смешивать:
A. Hero-image — только первое восприятие и среда.
B. Technology Visualization — источник, объясняющий реальную структуру технологии.
C. Image Slot — самостоятельное изображение, которое помогает понять конкретный блок.

Hero не является стилевым шаблоном для остальных изображений.

Для публичного сайта разрешены только source visualizations 01, 02, 05 и опционально 12. Цель — 3 сильные визуализации, не перенос всей 12-слайдовой серии.

Visualization 01 содержит собственный 8-узловой архитектурный маршрут и НЕ заменяет канонический 10-шаговый цикл.

Если Image Slot не улучшает понимание, изображения быть не должно.

## 4. Обязательная архитектура
Главная.
Технология.
Продукты + четыре продуктовые страницы.
Инструменты.
Кейсы + 12 detail pages/templates.
Статьи + article template.
Частые вопросы.
О проекте.
Об авторе.
Контакты.

Primary navigation:
Технология | Продукты | Кейсы | Инструменты | Статьи

CTA:
Обсудить ситуацию

Trust/footer:
О проекте | Об авторе | Частые вопросы | Контакты

## 5. Как проектировать
Не превращай BLOCK_SPECIFICATION в набор одинаковых карточек.
Он задаёт знания и отношения, которые посетитель должен понять.

Ты свободен выбирать профессиональную композицию, иерархию, ритм, whitespace, сетку, типографические масштабы и responsive-композицию внутри выбранной Design System.

Но дизайн не имеет права сокращать обязательное знание. Если контент не помещается — меняется композиция, а не смысл.

Сайт должен выглядеть как зрелый технологический продукт для управленческой аудитории, а не как generic consulting landing, презентация, SaaS-dashboard или набор красивых карточек.

## 6. Работа с кейсами
На /cases/ должны быть доступны все 12 модельных ситуаций.
На detail page должен существовать короткий reading layer и полный body.
Нельзя превращать кейс в 3–4 строки ради компактности.
Нельзя создавать testimonial framing, логотипы «клиентов», before/after или измеренный результат, которого нет в источнике.

## 7. Image Slots
Не генерируй декоративные изображения просто потому, что есть свободное место.

Forms 17–23: допускается Image Slot, функция которого — показать материальность рабочих инструментов и их связанность. Не выдумывать читаемые поля форм.

Cases: optional/TBD contextual system. Сайт должен быть полноценным без неё.

Articles: optional. Article template должен работать без обложки.

Products / FAQ / Contact / Evidence / About Project: обязательных Image Slots нет.

Author portrait — только реальная фотография, отдельно утверждённая Owner.

## 8. Production stack
WordPress + Blocksy + Elementor Free.
Elementor V3 Containers.
Max content width 1240 px.
Breakpoints: desktop >=1025; tablet 768–1024; mobile <=767.
Side padding: 32 / 28 / 20 px.
Major section spacing: 96 / 72 / 48.
Normal: 72 / 56 / 40.
Compact: 48 / 40 / 32.
Header/footer — Blocksy.

Не закладывать Elementor Pro, ACF, Loop Builder, premium carousel или новый plugin.
Эти параметры — технический envelope, а не визуальный шаблон.

## 9. Порядок работы
Не начинай с генерации всего сайта одним проходом.

Шаг 1. Прочитай весь пакет и Design System. Верни короткий LOCK CHECK: что считаешь неизменяемым, какие реальные attachments видишь, какие dependencies отсутствуют.

Шаг 2. Спроектируй HOMEPAGE как pilot, включая реальное использование FINAL Hero и выбранных визуальных классов.

Шаг 3. После проверки homepage спроектируй family templates:
Technology;
Products / Product;
Tools;
Cases / Case;
Articles / Article;
FAQ;
About;
Author;
Contact.

Шаг 4. Собери coherent responsive system desktop/tablet/mobile.

Шаг 5. Верни component/template mapping для реализации в Elementor Free.

## 10. Самопроверка
Перед handoff проверь 08_ACCEPTANCE_CRITERIA.md.
По каждому FAIL укажи page/block/reason.

Важно: твой self-check не является финальным PASS. Финальную проверку выполняет независимый audit после design output.

## 11. Главный критерий
Посетитель после сайта должен понимать технологию лучше, чем до сайта.
Физическое наличие текста, карточки или картинки без передачи знания не считается выполнением задачи.


## CRITICAL CORPUS RECOVERY — READ BEFORE ANY FURTHER DESIGN
The Owner supplied the complete authoritative Google Drive documentation and it has now been read and materialized into this GitHub package.

You MUST additionally read:
- 00A_CORPUS_RECOVERY_DIRECTIVE.md
- every file in 04B_FULL_CASES/
- every file in 04C_RECOVERED_CORPUS/
- every file in 04D_PRODUCT_CORPUS/

The previous SOURCE_UNREADABLE status for A3-01…A3-12 is CLOSED. Full source-derived Russian text for all 12 cases is now physically present in the package. Do not leave case bodies empty.

The current site was built from an under-complete content layer. Therefore the next task is not merely to add missing pages. Re-open every existing page and perform a source-to-page completeness pass. Expand thin pages with the recovered source-backed content while preserving later Owner locks.

Do not copy obsolete conflicts from older site/commercial documents: no mandatory product funnel, no fifth product, no automatic publication of old prices/durations, no conversion of model cases into real client cases.


## TECHNOLOGY EXPLANATION MASTER — NEW REQUIRED NARRATIVE AUTHORITY
Read 04E_TECHNOLOGY_EXPLANATION_MASTER.md before revising Home or Technology.
The current site must not remain a stack of independent marketing sections. Home and Technology must express the continuous causal explanation defined in this master. Do not mechanically create one card/section per numbered point; design one coherent reading journey. If sections can be arbitrarily reordered without breaking the explanation, the design has failed the narrative requirement.


## CONTENT MASTER V2 — HOME + TECHNOLOGY — REQUIRED
For Home and /technology/, 04F_CONTENT_MASTER_V2_HOME_TECHNOLOGY.md is now the authoritative public content/sequence layer where it supersedes the older fragmented sections of 04_CONTENT_MASTER.md.

Required design consequence:
- Home is a compressed continuous explanation, not a directory of equal cards.
- /technology/ is the full methodological explanation.
- BATNA and ZOPA must each receive a real method explanation: procedure, management function, why selected as a key technology element, how they differ, and why both are required.
- The 10-step cycle must show movement and return loop, not ten decorative equal cards.
- Transitions between major acts must preserve the causal chain.
- Do not shorten the recovered methodology back into one-line marketing definitions for visual convenience.
