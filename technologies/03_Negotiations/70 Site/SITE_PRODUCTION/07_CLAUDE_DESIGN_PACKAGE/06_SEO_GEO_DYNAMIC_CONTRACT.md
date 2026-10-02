# SEO_GEO_DYNAMIC_CONTRACT — Архитектура Переговоров
Status: S09 RECOVERY / OWNER ARTICLES ADDITION — HANDOFF CURRENT
Date: 2026-09-30
Inputs: T1 / M / H / A / C LOCK
Domain: nego.7vctr.ru
Stack: WordPress + Blocksy + Elementor Free

## 1. Principle
SEO/GEO exposes approved technology/public entities and includes the Owner-required source-governed Articles knowledge layer. It does not create filler content, new products, capabilities, proof claims or protected know-how. C-LOCK plus Owner-approved additions are the semantic ceiling.

## 2. Indexation contract
INDEX:
- / — Архитектура Переговоров
- /technology/
- /products/
- /products/diagnostics/
- /products/session/
- /products/sprint/
- /products/support/
- /cases/
- /cases/{approved-case-slug}/ — 12 model/teaching case pages only
- /tools/
- /articles/
- /articles/{approved-article-slug}/ — only when an actual source/editorially approved body exists
- /faq/
- /about/
- /author/
- /contact/

NOINDEX unless later intentionally published:
- WordPress author/date/tag/category/search archives
- attachment/media pages
- Elementor templates/system pages
- duplicate feeds/parameter URLs
- internal/private legal drafts
- staging/test URLs

A source-governed **Статьи** layer is mandatory by Owner recovery decision. It is an expert knowledge layer, not an automatic SEO blog. Empty/generated article bodies are forbidden.

## 3. Canonical URLs
Self-referencing canonical on every indexable canonical page.
Production host: https://nego.7vctr.ru
Canonical host has no www.
One trailing-slash convention: WordPress canonical trailing slash.
HTTP → HTTPS and any www variant → canonical host.
Do not canonicalize distinct product/case pages to parent pages.
Query/filter/UTM URLs canonicalize to the clean page where technically applicable.
Old/legacy URLs receive 301 only when an actual predecessor→target mapping is known. No guessed redirect map.

## 4. Primary page metadata
Metadata is descriptive, not a claim expansion.

| URL | SEO title | Meta description |
|---|---|---|
| / | Архитектура Переговоров — технология управления переговорной позицией | Цели, полномочия, BATNA, ZOPA, уступки, влияние и риски в одной системе для внешних и внутренних переговорных решений. |
| /technology/ | Технология Архитектуры Переговоров: 10 шагов и 2 контура | Как компания управляет переговорной позицией: от цены ошибки и целей до BATNA, ZOPA, уступок, рисков и следующего решения. |
| /products/ | Продукты Архитектуры Переговоров: 4 формата работы | Диагностика, Сессия, Спринт и Сопровождение — четыре формата применения одной технологии к реальным переговорным ситуациям. |
| /products/diagnostics/ | Диагностика переговорной позиции | Разбор конкретной переговорной ситуации: цели, границы, BATNA, ZOPA, полномочия, уступки, риски и следующий управленческий шаг. |
| /products/session/ | Сессия по Архитектуре Переговоров | Совместная работа команды над конкретной переговорной ситуацией: единая позиция, границы, роли, уступки и следующий шаг. |
| /products/sprint/ | Спринт Архитектуры Переговоров | Работа с переговорной позицией через несколько раундов: подготовка, решение, фиксация, разбор и корректировка следующего цикла. |
| /products/support/ | Сопровождение переговорных решений | Регулярная работа с потоком внешних и внутренних переговорных ситуаций: позиции, границы, уступки, риски и следующие действия. |
| /cases/ | Кейсы Архитектуры Переговоров — 12 модельных ситуаций | 12 модельных учебных ситуаций показывают применение технологии к внешним и внутренним переговорным решениям. |
| /tools/ | Инструменты Архитектуры Переговоров — формы 17–23 | Семь рабочих форм поддерживают цикл от подготовки переговорной позиции до фиксации результата и следующего решения. |
| /faq/ | Архитектура Переговоров — вопросы и ответы | BATNA, ZOPA, полномочия, уступки, четыре продукта, границы технологии и ответы на основные вопросы. |
| /contact/ | Обсудить переговорную ситуацию | Опишите контекст, стороны и решение, которое предстоит принять, чтобы определить подходящий формат работы. |

Case detail title pattern:
{case title} — модельный кейс Архитектуры Переговоров
Description pattern must be written from the approved CASE_CONTENT_MASTER record and explicitly preserve model/teaching framing; never invent result metrics.

## 5. Internal graph
Global navigation: Технология → Продукты → Кейсы → Инструменты → Статьи; primary CTA → Contact. Secondary/trust navigation: О проекте → Об авторе → Частые вопросы → Контакты.

Required contextual links:
- Home mechanism → /technology/
- Home four products → each product page
- Home forms → /tools/
- Home cases → /cases/
- Technology → /tools/ + /products/
- Products index → four product pages
- Product pages → /tools/ when relevant form mapping is source-supported; → model cases only when source mapping is traceable; → /contact/
- Case detail → technology objects used; related product only when CASE_CONTENT_MASTER/source supports it; → /contact/
- Tools → /technology/ + relevant product pages according to recovered Form Navigator
- FAQ answers → relevant technology/product/tools page where natural
- Articles link contextually to Technology/Tools/Cases/Products only when the subject supports the relation.
- About Project links to Technology and appropriate knowledge pages.
- Author links to Articles/materials and Contact without inventing credentials.
- Contact does not become an SEO hub.

No orphan indexable page.

## 6. GEO / answer contract
Pages must answer the user's question in visible HTML before decorative/interactive elaboration. Do not hide the only answer inside tabs, images or generated graphics.

Approved concise answer blocks:
- What is Архитектура Переговоров? — source-locked definition from C-LOCK.
- What does it manage? — situation/error price, goals, participants, influence/authority, BATNA, ZOPA, concessions, risks, next scenario, fixation.
- External vs internal? — one core, two application contours.
- What are BATNA and ZOPA? — approved glossary definitions; keep distinct.
- What products exist? — exactly four.
- Must negotiations end in agreement? — no; use approved decision outcomes.
- Is this psychological profiling/manipulation? — no.
- What are Forms 17–23? — seven working instruments; detailed public wording only from recovered XLSX/disclosure boundary.
- Are the cases real client success stories? — no; they are model/teaching application cases unless a future separately verified record changes that status.

Answer blocks may be reused semantically but must not create new factual claims.

## 7. Structured-data eligibility
Allowed when technically supported and matching visible content:
- Person schema may be used for Валерий Бирюков only when it mirrors the Owner-approved public author facts. Do not invent legal/company identity.
- Organization schema remains conditional on verified legal/public organization identity.
- WebSite on home.
- WebPage on normal pages.
- BreadcrumbList on secondary pages.
- FAQPage on /faq/ only if the visible Q&A is present and current platform/search-engine eligibility warrants implementation; schema must mirror visible answers exactly.
- Article schema is eligible only for actual published article pages with visible article body and truthful metadata. It is NOT used for product/tool/case pages.
- Product schema is NOT used for the four service formats merely because they are called products internally.
- Review/AggregateRating/Testimonial schema forbidden without real verified evidence.
- HowTo schema forbidden for the 10-step technology cycle: it would overstate public procedural disclosure and is not needed.
- Case pages must not use review/testimonial/result schema.

## 8. Dynamic-content contract
Locked stack baseline is static WordPress pages built with Elementor Free/Blocksy.
No ACF, Elementor Pro Loop Builder, dynamic plugin, custom post type or new plugin is silently required.

Implementation baseline:
- four product pages = static pages;
- 12 case pages = static pages using one repeatable case-detail section pattern;
- FAQ = static visible content/accordion if Free-stack feasible;
- tools = static records;
- articles index/detail = WordPress native posts or static pages within the locked stack; no new plugin required;
- about/author/contact = static pages;
- navigation/footer = Blocksy.

If a future implementation chooses CPT/fields, it is an implementation optimization only and must preserve URLs, C-LOCK content, schema rules and four-product ontology. It cannot become a semantic dependency.

## 9. Case SEO contract
All 12 case pages are eligible for indexation only after their C-LOCK model-case disclosure is present on-page.
Each page must contain:
1. explicit label: Модельный / учебный кейс;
2. situation;
3. management decision problem;
4. source-supported technology objects;
5. source-supported work/decision path;
6. model decision labelled as model decision, never client outcome;
7. what the case demonstrates;
8. limitations;
9. related product only if traceable.

No fabricated company identity, testimonial quote, before/after metric or actual achieved result.

## 10. Protected know-how boundary
Indexable copy may explain objects, roles, 10-step public cycle, Forms 17–23 public role and model application.
Do not publish:
- protected facilitation/operating instructions beyond approved public master;
- workbook formulas merely for SEO;
- internal scoring/decision mechanics as universal doctrine;
- evidence-control/release-control internals;
- source-sensitive/private commercial data;
- unverified author/legal/contact data.

## 11. Robots/sitemap behavior
XML sitemap should contain only canonical indexable public URLs.
Noindex pages should not be intentionally promoted through sitemap.
robots.txt must not be used as a substitute for noindex/canonical controls.
Do not block CSS/JS/assets needed to render indexable pages.

## 12. Redirect/migration rule
Legacy 70 Site is not a semantic authority.
Before launch, inventory actual currently indexed/linked legacy URLs. Map only genuine equivalents:
old URL → closest A/C-LOCK canonical page.
Use 301 for true permanent replacements.
Use 410/404 for removed content with no valid equivalent rather than redirecting everything to home.
No redirect is created from filename similarity alone.

## 13. Content freshness / dynamic state
Technology truth and product ontology are lock-controlled, not date-feed content.
Cases/forms change only through source/content lock update.
Commercial numbers, contacts, legal identity and author data are currentness-sensitive and must not be generated from stale corpus.
No automatic publication or AI-generated SEO expansion is authorized.

## 14. S09 acceptance
PASS:
- indexable set defined;
- metadata defined without claim expansion;
- internal graph defined;
- GEO answer blocks bounded by C-LOCK;
- structured-data eligibility bounded;
- canonical/redirect rules defined;
- dynamic behavior implementable on Blocksy + Elementor Free;
- no protected know-how leakage;
- no new product/entity/capability;
- Owner-required Articles layer included without filler/auto-generated bodies;
- About / Author / Contact included with current Owner-approved facts;

No Owner gate at S09. Proceed to S10.
