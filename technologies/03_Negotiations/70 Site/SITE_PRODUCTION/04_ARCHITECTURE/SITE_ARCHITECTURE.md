# SITE_ARCHITECTURE — Архитектура Переговоров

Status: FINAL FOR OWNER GATE A
Date: 2026-09-30
Inputs: T1 LOCK, M LOCK, H LOCK
Domain: nego.7vctr.ru

## 1. Architecture principle
The site explains one technology and routes a visitor to one of its four locked products. It does not create a new product ontology, mandatory funnel or generic negotiation-media portal.

## 2. Primary sitemap
1. **Главная** — /
2. **Технология** — /technology/
3. **Продукты** — /products/
   - **Диагностика** — /products/diagnostics/
   - **Сессия** — /products/session/
   - **Спринт** — /products/sprint/
   - **Сопровождение** — /products/support/
4. **Кейсы** — /cases/
   - case detail template — /cases/{slug}/
5. **Инструменты** — /tools/
6. **FAQ** — /faq/
7. **Контакты / обсудить ситуацию** — /contact/

No separate page is created merely because a source file exists.

## 3. Primary navigation
Desktop:
**Технология | Продукты | Кейсы | Инструменты | FAQ**
Right CTA: **Обсудить ситуацию**

Logo returns to Главная.

Mobile:
same semantic order in menu; CTA remains visually distinct.

## 4. Homepage story

### HOME-01 Hero
Known H-LOCK asset.
Job: establish category + governing value + concrete entry action.
Copy area left; FINAL Hero artwork right.
Primary CTA: Разобрать переговорную ситуацию.
Secondary CTA: Как работает технология.
Four products are visible as product family, without adding products.

### HOME-02 What is being managed
Job: shift understanding from “conversation skill” to managed company negotiation position.
Objects: goal, authority, alternative/BATNA, ZOPA/bad-agreement boundary, influence, concessions/countersteps, cognitive risks, next decision.

### HOME-03 Two contours, one core
External negotiations and internal decisions/alignment.
Job: show that the same core technology works across both source-confirmed contours without inventing two technologies.

### HOME-04 How the technology works
10-step canonical cycle, compressed for public comprehension.
Detailed know-how stays bounded by disclosure matrix.
CTA → Technology page.

### HOME-05 Decision outcomes
Show controlled legitimate outcomes: continue; continue under conditions; clarify data; align internally; change package/position; strengthen BATNA; pause; refuse/exit; define return conditions.
Job: explain why “agreement at any price” is not the objective.

### HOME-06 Four products
Exactly:
1. Диагностика
2. Сессия
3. Спринт
4. Сопровождение
Each card answers: when used / what work occurs / what decision-output is produced.
No fifth product.

### HOME-07 Instruments
Forms 17–23 at approved public name/role level.
No cell-level/internal mechanics until source/read/disclosure permits.
CTA → Instruments.

### HOME-08 Evidence
Only bounded evidence currently authorized.
Technology 10 may support limited checks with explicit scope.
Unread case bodies do not generate result claims.

### HOME-09 Cases
Case architecture exists, but publication of individual case content remains subject to READ/disclosure status.
Until content gate C, this section cannot fabricate outcomes from titles.
CTA → Cases.

### HOME-10 Anti-category / boundaries
Compact constructive distinction:
not negotiation tricks; not manipulation/personality diagnosis; not guaranteed victory; not legal/financial substitution; not spreadsheets detached from a real decision.

### HOME-11 FAQ
Public-safe questions from approved FAQ/glossary after content normalization.

### HOME-12 Conversion
“Обсудить переговорную ситуацию.”
Short context form/contact route; no promise of result.

## 5. Technology page
TECH-01 Intro / definition
TECH-02 What the technology manages
TECH-03 One core / two contours
TECH-04 Canonical 10-step cycle
TECH-05 Managed objects: BATNA, ZOPA, influence, authority, concessions, risks, scenario
TECH-06 Forms 17–23
TECH-07 Valid decision outcomes
TECH-08 Boundaries / anti-category
TECH-09 Four-product application routes
TECH-10 CTA

## 6. Products index
PROD-00 Intro: four forms of applying one technology.
PROD-01 Diagnostics
PROD-02 Session
PROD-03 Sprint
PROD-04 Support
PROD-05 How to choose by situation/work depth
PROD-06 CTA

No extra Board-level/package entity is promoted to a fifth core product.

## 7. Product detail template
Used by all four products with product-specific content:
P-01 Product name + role
P-02 When this format is used
P-03 What enters the work
P-04 What happens in the work
P-05 Outputs / decision artifacts
P-06 Relevant Forms 17–23
P-07 Possible decision outcomes
P-08 Boundaries / what is not promised
P-09 Related case/evidence where disclosure allows
P-10 CTA

## 8. Cases
CASES-01 Intro and disclosure framing
CASES-02 Filter/group only if source/content truth justifies it
CASES-03 Case grid
CASES-04 CTA

Case detail template:
C-01 situation/context
C-02 management/negotiation problem
C-03 technology objects used
C-04 work/decision path
C-05 outcome only at source-supported disclosure level
C-06 what the case demonstrates / limitations
C-07 related product
C-08 CTA

No case body is written from filename/title alone.

## 9. Instruments
TOOLS-01 Why instruments exist
TOOLS-02 Forms 17–23 overview
TOOLS-03 relationship of forms to the 10-step cycle
TOOLS-04 relationship to products
TOOLS-05 disclosure boundary: tool supports decision work, not standalone spreadsheet product
TOOLS-06 CTA

No calculator/solver is invented unless source evidence establishes one.

## 10. FAQ
FAQ-01 category/what it is
FAQ-02 who/which situations
FAQ-03 external vs internal
FAQ-04 BATNA/ZOPA/authority/concessions etc.
FAQ-05 products
FAQ-06 boundaries/results
FAQ-07 engagement/contact
Actual public records are completed at S08 from source-locked FAQ/glossary.

## 11. Contact / conversion
CONTACT-01 concise proposition
CONTACT-02 context capture: company/contact + situation description using only necessary fields
CONTACT-03 privacy/consent implementation requirement
CONTACT-04 alternative contact route if source/current commercial data permits

## 12. UX journey
Primary:
Hero → understand managed object → see mechanism → see four products → choose relevant depth → discuss situation.

Evidence-seeking:
Hero → Technology → Evidence/Cases → relevant Product → CTA.

Instrument-seeking:
Hero/Technology → Instruments → relevant Product → CTA.

Returning visitor:
Navigation → specific Product / Case / FAQ → CTA.

## 13. Conversion rules
- one primary conversion concept: discuss / analyze a real negotiation situation;
- product pages may contextualize the CTA but cannot invent a new service;
- no forced sequential purchase path is asserted in UX architecture;
- no guaranteed result language;
- forms and cases support the technology; they do not become substitute products.

## 14. Hero constraint
H-LOCK is a known architecture input:
- desktop first screen preserves left copy field + right visual;
- navigation/header must not cover the artwork;
- mobile semantic order: copy → primary CTA → Hero crop → secondary support/product family;
- do not regenerate Hero to solve layout problems; adapt crop within HERO_LOCK.

## 15. Secondary template system
Templates required:
- Product detail
- Case detail
Potential knowledge/article template is NOT introduced at S05 because current architecture does not yet establish a justified public knowledge hub. S09 may add indexable informational architecture only if content truth supports it without changing approved page story.

## 16. Footer
Technology
Products: four locked products
Cases
Instruments
FAQ
Contact
Legal/privacy links as required by implementation/publication context.

## 17. Explicit exclusions at S05
- no fifth product;
- no AI negotiation product;
- no personality profiling;
- no guaranteed result;
- no invented case outcomes;
- no invented calculators/solvers;
- no generic blog solely for SEO;
- no legacy-site structure carried forward without semantic job;
- no Elementor layout selection yet — that is S06.

## 18. Gate A scope
Owner approval at A locks:
- sitemap;
- navigation;
- homepage story/order;
- secondary page/template set;
- four-product presentation;
- primary UX/conversion paths;
- H-LOCK integration principle.

Detailed block implementation, final copy, Elementor sections, SEO schema and non-Hero visual slots remain downstream stages.
