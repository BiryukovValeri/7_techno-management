# BLOCK_SPECIFICATION — Архитектура Переговоров
Status: S07 PASS
Date: 2026-09-30
Inputs: A LOCK + S06 feasibility PASS

Legend: SRC = source/content requirement; EV = evidence boundary; VIS = asset role; R = responsive.

## GLOBAL
G-01 Header — job: navigation + contact action; Blocksy; content: Technology / Products / Cases / Tools / FAQ + Discuss situation; no invented service; R: desktop nav → mobile menu; accessibility: keyboard/focus/current-page.
G-02 Footer — job: secondary navigation/legal; Blocksy; content from A-LOCK + current legal/contact records at S08; R stacked mobile.
G-03 CTA rule — one semantic conversion family: discuss/analyze a real negotiation situation; wording may contextualize by page but cannot create a product.

## HOME /
| ID | Job | Section | SRC / content | EV | VIS | CTA | R |
|---|---|---|---|---|---|---|---|
| HOME-01 | establish category/value/action | EL-HERO | M LOCK + H LOCK | T1/M/H | FINAL Hero H-LOCK | primary discuss situation; secondary technology | desktop 46/54; mobile copy→CTA→art |
| HOME-02 | show managed objects | EL-KNOWLEDGE-STRIP | T1 objects | source-confirmed names only | semantic icons/diagram TBD S10 | technology | 4–8 grid→2→1 |
| HOME-03 | explain one core/two contours | EL-PROJECTION | T1 | no invented org model | two-contour semantic visual TBD | technology | 2→1 |
| HOME-04 | explain mechanism | EL-PROCESS | canonical 10-step cycle | public summary only | process diagram TBD | technology detail | grid→linear |
| HOME-05 | redefine valid result | EL-STATUS | T1 decision outcomes | no result guarantee | simple status/route visual | none/technology | 3→2→1 |
| HOME-06 | route to four products | EL-PRODUCT-GRID | S02 four products | exactly four | product visual system TBD | each product | 4→2→1 |
| HOME-07 | show instruments | EL-TOOL-GRID | Forms 17–23 name/role | no XLSX cell claims | form-card visual system | tools | 3/4→2→1 |
| HOME-08 | bounded proof | EL-EVIDENCE | Technology 10 | limited checks only | evidence diagram optional | technology/cases | split→stack |
| HOME-09 | expose approved cases | EL-CASE-GRID | case records only after READ/disclosure | HOLD until S08 completeness | case images TBD | cases | 3→2→1 |
| HOME-10 | set boundaries | EL-ANTI-CATEGORY | T1/M anti-category | no competitive boasting | none required | none | 2→1 |
| HOME-11 | answer objections/questions | EL-FAQ | approved FAQ/glossary | normalized against locks | none | FAQ | 1-col |
| HOME-12 | convert | EL-CTA | M conversion rule | no promised outcome | none | discuss situation | stack |

## TECHNOLOGY /technology/
TECH-01 Intro — EL-EXPLANATORY-SPLIT; definition + governing value; T1/M; VIS contextual semantic asset TBD; CTA products.
TECH-02 Managed object — EL-KNOWLEDGE-STRIP; goal/authority/BATNA/ZOPA/influence/concessions/risks/scenario; EV public names/roles only.
TECH-03 One core/two contours — EL-PROJECTION; external/internal; no separate technologies.
TECH-04 Cycle — EL-PROCESS; 10 steps; no protected operating detail.
TECH-05 Managed objects in relation — EL-EXPLANATORY-SPLIT; source-locked explanatory copy; VIS semantic diagram.
TECH-06 Forms — EL-TOOL-GRID; 17–23; no cell-level claims until cleared.
TECH-07 Decision outcomes — EL-STATUS; source-confirmed valid outcomes.
TECH-08 Boundaries — EL-ANTI-CATEGORY; no guarantee/manipulation/diagnosis/legal-financial substitution.
TECH-09 Application formats — EL-PRODUCT-GRID; exactly four products.
TECH-10 Conversion — EL-CTA; discuss situation.
R: all split sections stack in semantic order; cycle becomes linear; grids 4→2→1.

## PRODUCTS INDEX /products/
PROD-00 — EL-EXPLANATORY-SPLIT; job: explain four forms of applying one technology; SRC S02.
PROD-01..04 — EL-PRODUCT-GRID as one four-card family: Diagnostics / Session / Sprint / Support; each record requires role, when used, work objects, output; CTA detail page.
PROD-05 — EL-EXPLANATORY-SPLIT; job: choose by situation/work depth; must not invent mandatory purchase sequence.
PROD-06 — EL-CTA; discuss situation.
VIS: coherent four-product visual system TBD S10; R 4→2→1.

## PRODUCT DETAIL TEMPLATE ×4
P-01 — EL-PRODUCT-DETAIL; product name/role; current protocol; no commercial variant promoted to core.
P-02 — EL-EXPLANATORY-SPLIT; when used; protocol.
P-03 — EL-EXPLANATORY-SPLIT; inputs; protocol; missing data never invented.
P-04 — EL-EXPLANATORY-SPLIT; what happens; disclose only public-safe work objects.
P-05 — EL-EXPLANATORY-SPLIT; outputs/decision artifacts; no KPI guarantee.
P-06 — EL-TOOL-GRID; relevant Forms 17–23 only when source mapping supports relation.
P-07 — EL-STATUS; possible decision outcomes.
P-08 — EL-ANTI-CATEGORY; boundaries/not promised.
P-09 — EL-EVIDENCE and/or EL-CASE-GRID; render only when approved record exists; otherwise omit, never placeholder proof.
P-10 — EL-CTA; contextual “обсудить ситуацию”.
VIS: product-specific semantic/contextual asset slots classified S10. R stacked mobile.

## CASES /cases/
CASES-01 — EL-EXPLANATORY-SPLIT; explain what cases demonstrate and disclosure boundary.
CASES-02 — optional filter/group; **do not implement unless S08 source truth justifies taxonomy**.
CASES-03 — EL-CASE-GRID; each card requires approved title/context + disclosure-safe summary; current case bodies HOLD.
CASES-04 — EL-CTA.
No result, client identity, quote or metric from filename alone.

## CASE DETAIL TEMPLATE
C-01 — EL-CASE-DETAIL; situation/context; approved case record.
C-02 — EL-EXPLANATORY-SPLIT; management/negotiation problem.
C-03 — EL-KNOWLEDGE-STRIP; technology objects actually evidenced in case.
C-04 — EL-EXPLANATORY-SPLIT; work/decision path.
C-05 — EL-EVIDENCE; outcome only at source-supported disclosure level.
C-06 — EL-ANTI-CATEGORY or explanatory split; what case demonstrates + limitation.
C-07 — related product link only if source/interpretation is traceable.
C-08 — EL-CTA.
VIS: contextual/semantic case asset only after S10 classification; no fabricated before/after.

## TOOLS /tools/
TOOLS-01 — EL-EXPLANATORY-SPLIT; instruments support real decision work, not spreadsheet product.
TOOLS-02 — EL-TOOL-GRID; Forms 17–23 name + approved role.
TOOLS-03 — EL-PROCESS; relation to 10-step cycle, only source-supported mapping.
TOOLS-04 — EL-PRODUCT-GRID/adapted relation cards; relation to products only when supported.
TOOLS-05 — EL-ANTI-CATEGORY; disclosure/protected detail boundary.
TOOLS-06 — EL-CTA.
No calculator/solver/new form.

## FAQ /faq/
FAQ-01..07 are content groups inside EL-FAQ:
1 category/definition;
2 audience/situations;
3 external/internal;
4 BATNA/ZOPA/authority/concessions etc.;
5 four products;
6 boundaries/results;
7 engagement/contact.
SRC: approved FAQ + glossary normalized to T1/M/A. No stale FAQ wording may override locks.
Accessibility: accordion controls keyboard operable; if widget feasibility fails, render headings + text instead.

## CONTACT /contact/
CONTACT-01 — EL-CONTACT; concise proposition + current contact route.
CONTACT-02 — EL-FORM only if approved implementation mechanism exists; minimal fields: contact/company/context only after S08/current privacy decision.
CONTACT-03 — consent/privacy notice and legal link required if form collects data.
CONTACT-04 — alternative current contact route only if source/current data confirms it.
Implementation HOLD: Elementor Pro Form is forbidden assumption. Direct CTA/contact route is safe baseline.

## CONTENT / EVIDENCE RULES
1. S07 specifies slots; it does not fill missing evidence.
2. Any block whose required entity remains HOLD is conditional and may be omitted until S08 clears it.
3. No placeholder testimonial, logo, KPI, client result, price or duration.
4. Forms 17–23 are public only at approved name/role level until detailed XLSX disclosure is cleared.
5. Cases remain non-evidentiary until body READ + disclosure classification.
6. Product ontology remains exactly four.

## VISUAL RULES
- H-LOCK binary only in HOME-01 unless later reuse is explicitly justified; no regeneration.
- Non-Hero visual slots are status TBD until S10.
- No image is generated merely because S07 names a slot.
- Semantic diagrams must not imply unsupported metrics, software UI, AI capability or psychological profiling.

## RESPONSIVE / ACCESSIBILITY
- mobile order follows semantic sequence in this file;
- no essential hover-only content;
- all interactive controls keyboard reachable with visible focus;
- heading hierarchy remains logical per page;
- informative images require meaningful alt; decorative assets null alt;
- no critical text baked into generated imagery;
- CTA tap targets and contrast must remain usable;
- cards do not become horizontal-scroll-only dependencies.

## S07 DoD
Every A-LOCK page/block is mapped to: semantic job + S06 section family + source/content requirement + evidence boundary + CTA where applicable + visual role + responsive behavior.
No Elementor Pro/ACF/new plugin dependency introduced.
