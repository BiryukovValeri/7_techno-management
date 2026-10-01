# PUBLIC_LANGUAGE_GATE — Архитектура Переговоров
Status: QR-05 / PRODUCTION CONTROL
Date: 2026-10-01

## 1. Rule
Public site language is Russian.
Final production copy must contain **0 unauthorized English public terms**.

This is an executable acceptance rule, not a style preference.
Internal methodology/source terminology may remain in source/control documents. It does not automatically receive permission for public UI.

## 2. Three classes
### ALLOW
A term may appear publicly in the listed form because it is part of the locked Negotiations content or a necessary conventional identifier. First-use explanation rules still apply.

| Public token | Rule |
|---|---|
| BATNA | First meaningful occurrence: «BATNA — лучшая альтернатива соглашению» (or equivalent source-faithful Russian explanation). Later BATNA is allowed. |
| ZOPA | First meaningful occurrence: «ZOPA — зона возможного соглашения» (or equivalent source-faithful Russian explanation). Later ZOPA is allowed. |
| B2B | Allowed only where the actual case/context requires it; not decorative positioning language. |
| URL | Not public prose unless technically necessary. |

No other English token is automatically ALLOW merely because it appears in a source filename, internal protocol, design package or sibling technology.

### TRANSLATE / PUBLIC-RUSSIAN
Use Russian public wording. English/internal wording must not survive into production copy.

| Internal / possible English | Public site |
|---|---|
| Diagnostics / Diagnostic | Диагностика |
| Session | Сессия |
| Sprint | Спринт |
| Support | Сопровождение |
| Case / Cases | кейс / кейсы; where clearer: модельная ситуация |
| Tools | Инструменты |
| Articles | Статьи |
| About | О проекте |
| Author | Об авторе |
| Contact | Контакты |
| FAQ | Частые вопросы in visible navigation/headings; FAQ may remain only as technical/schema/internal identifier |
| CTA | призыв/действие only internally; visible button gets actual Russian action text |
| Hero | первый экран only in public discussion; never visible label |
| Image Slot | изображение блока / contextual image only internally; never visible label |
| Technology Visualization | визуализация технологии only internally; never visible label |
| model case | модельный / учебный кейс |
| readiness | готовность |
| influence map | карта влияния |
| counterstep | встречный шаг |
| decision outcome | результат / вариант управленческого решения by context |
| review | разбор / проверка by context |
| next cycle | следующий цикл |
| checklist | контрольный список |
| report | отчёт |
| baseline | исходная точка, if the concept is actually needed |
| framework | модель / метод / структура by source context |
| trigger | признак / условие; «триггер» only if separately justified in source-grounded public copy |

### FORBIDDEN BY DEFAULT
The following may not appear in visible public copy unless a later source-backed exception is explicitly added to ALLOW:
- Problem Unit
- Bridge as an imported technology entity
- Go / Conditional Go / Hold / Stop as sibling verdict ontology
- pipeline / funnel as product-path language
- dashboard
- workflow
- playbook
- roadmap
- framework as untranslated jargon
- insight
- toolkit
- use case
- touchpoint
- deliverable
- outcome as untranslated jargon
- evidence as untranslated jargon
- proof point
- deep dive
- workshop where «сессия» is the actual product
- assessment where «диагностика» is the actual product
- advisory where «сопровождение» is the actual product
- AI / copilot / agent as a technology capability unless separately source-proven and owner-approved

This list is a guardrail, not a claim that every token currently exists in copy.

## 3. Russian-first terminology rules
1. Russian meaning precedes abbreviation/jargon.
2. A visitor must not need the internal methodology glossary to understand the page.
3. Source-faithful specialist terms are not translated into a different concept merely to sound simpler.
4. BATNA/ZOPA may remain because they are locked technology terms, but their meaning is explained in Russian.
5. Product names are only: Диагностика / Сессия / Спринт / Сопровождение.
6. Navigation, buttons, headings, labels, filters, forms, errors and helper text are Russian.
7. English in image artwork counts as public copy if visible/readable.
8. English baked into a source visualization must be translated/adapted for web or explicitly approved; source fidelity does not require preserving avoidable English labels.
9. Brand/domain/file names and technical HTML attributes are outside visible-copy scanning.

## 4. Machine gate scope
Scan rendered visible text from:
- header/navigation;
- page body;
- buttons/links;
- cards;
- accordions;
- forms/placeholders/helper/error text;
- footer;
- alt text and accessible labels where user-facing;
- readable text embedded in final public visual assets, by asset QA.

Do not flag:
- HTML/CSS/JS syntax;
- class/id/data attributes;
- URLs/slugs;
- schema.org keys;
- analytics/code;
- filenames;
- internal comments;
- WP/Elementor admin labels.

## 5. Acceptance algorithm
For each Latin-script token in rendered public text:
1. normalize case/punctuation;
2. ignore technical/non-visible scope;
3. compare against ALLOW list and approved proper-name exception list;
4. if not allowed, classify as:
   - required proper name/source title → explicit exception record;
   - translatable public term → replace with Russian;
   - unnecessary jargon/imported ontology → remove/rewrite;
5. rerun until unauthorized count = 0.

**Gate formula: UNAUTHORIZED_PUBLIC_ENGLISH = 0.**
Any value >0 = FAIL.

## 6. Proper-name exceptions
No broad whitelist such as “all brands are allowed”.
Each proper-name exception must have:
- exact spelling;
- page/context;
- reason it must remain;
- source/provenance where relevant.

Current default exception set: EMPTY.
BATNA/ZOPA/B2B are governed above and do not open a general acronym exception.

## 7. Claude Design contract
Claude may not:
- preserve English merely because it appears in internal package headings;
- create English microcopy, section labels or decorative words;
- rename the four products;
- introduce fashionable English design/product vocabulary into public UI;
- convert Russian explanations back into internal abbreviations.

Claude may use internal English names in non-public design-layer annotations only.

## 8. Independent audit
Claude self-report is not evidence of language compliance.
Final audit must inspect actual rendered public copy and visual assets.
Defect class: LANGUAGE_VIOLATION.

## 9. QR-05 result
Public Language Gate: PASS as production control.
Final site language compliance remains a build-time acceptance gate.
