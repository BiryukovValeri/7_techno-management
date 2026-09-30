# S06 — ELEMENTOR SECTION & COMPONENT ARCHITECTURE — проSTRAнство
Status: FINAL FOR STAGE REVIEW
Dependencies: T1 / M / H / A LOCK
Stack: Blocksy + Elementor Free
Rule: custom Container baseline because production Elementor library availability is not verified here.

## 1. Global implementation rules
- Blocksy owns header, footer, global page shell and global typography/color defaults.
- Elementor Free owns page sections/content.
- No Elementor Pro, ACF, loop builder, essential hover-only interaction or unsupported dynamic behavior.
- Desktop content max-width: 1240px; reading copy max-width: 680px.
- Section horizontal padding: desktop 32px; tablet 24px; mobile 20px.
- Section vertical rhythm baseline: desktop 88–112px; tablet 64–80px; mobile 48–64px. Final visual tokens are S10/Design System responsibility.
- Semantic order must remain meaningful without CSS positioning.
- All interactive controls keyboard-focusable; visible focus state; icons never carry essential meaning alone.
- Russian-first UI.

## 2. Reusable component library

### PS-HERO-CHOICE
Job: position technology and convert.
Build: outer full-width Container → inner 1240px Container → 2-child flex/grid: copy + visual.
Widgets: Heading, Text Editor, Buttons, Image.
Desktop: copy ~43%, visual ~57%; canonical Hero asset only.
Tablet: 45/55 or stacked when copy becomes compressed.
Mobile: copy first; same canonical image second; no generated substitute; use object-position/crop only.
CTA: primary + secondary.
No text baked into image.

### PS-QUESTION-INTRO
Job: open each reasoning chapter with one dominant question.
Build: narrow heading container + optional lead.
Widgets: Heading, Text Editor.
Reuse HOME-02/03/04/05/06/09 etc.

### PS-PLAUSIBLE-CHOICES
Job: explain why several reasonable answers can coexist.
Build: intro + 3–4 equal evidence cards + closing proposition.
Widgets: Heading, Text Editor, Icon optional.
Mobile: single column; no carousel.

### PS-NARROWING-PROCESS
Job: explain selection mechanism.
Build: intro → ordered 8-step Container sequence.
Widgets: Heading/Text/Icon.
Desktop: 4+4 grid or horizontal sequence only if legible.
Tablet: 2 columns.
Mobile: 1 column, semantic order fixed.
No interactive framework selector.

### PS-EVIDENCE-CHAIN
Job: prove grounds for selection.
Build: evidence chain + verdict group.
Verdicts: Go / Conditional Go / Hold / Stop.
Desktop: chain above, 4 status cards below.
Mobile: chain vertical; status cards stacked.
Status meaning must be text, not color-only.

### PS-NOT-DO
Job: show value of justified rejection.
Build: heading + 5–6 “не…” statements in editorial grid + closing statement.
No fear/red-alert styling.

### PS-BRIDGE-VERIFY
Job: show selected choice translated into reality.
Build: 7-node process:
strategic output → operational carrier → owner → metric → rhythm → baseline → 30/60/90 verdict.
Desktop: controlled horizontal process.
Mobile: vertical.
No animation required.

### PS-PRODUCT-CONTOUR
Job: show conditional product family.
Build: 4 product cards + explicit transition labels/return/stop note.
Widgets: Heading/Text/Button/Icon.
Important: do not visually imply mandatory linear purchase ladder.
Each card: purpose / input / output / transition condition.
Mobile: stacked.

### PS-ARTIFACT-GROUPS
Job: make outputs tangible.
Build: 3–4 grouped artifact clusters, not fake screenshots.
Each group corresponds to decision stage.
Can use simple typographic cards in Elementor Free.

### PS-DEPTH
Job: explain expert depth without catalog.
Build: copy + restrained proof figures 95 / 115 + selection boundary 5–7 / 3–5.
Figures always accompanied by explanatory labels.
No tool grid, search, filters or catalog CTA.

### PS-CASE-CARDS
Job: evidence-safe cases.
Build: 3 featured cards homepage; full grid on /cases/.
Card fields: situation / plausible initial view / evidence shift / selected-or-rejected direction / verdict-next step.
No company logos, invented results or percentage outcomes.
Elementor Free static cards.

### PS-ANTI-CATEGORY
Job: compare category boundaries.
Build: two-column “не это / а это” or paired rows.
Mobile: paired rows remain adjacent semantically.
No competitor naming.

### PS-QUALIFICATION
Job: commercial entry.
Build: qualification criteria + CTA.
Form itself may be linked/embedded only through approved implementation later; no invented integration.
No “free audit”.

### PS-FAQ
Job: resolve objections.
Build baseline: Elementor Accordion widget if Free availability confirmed at implementation; otherwise Heading + Text stacked questions as safe fallback.
All content accessible without hover.

### PS-FINAL-CTA
Job: close with governing idea and qualification CTA.
Simple Container + Heading + Text + Button.

## 3. Homepage build sheet

| ID | S05 job | S06 archetype | Elementor Free baseline | Desktop | Mobile |
|---|---|---|---|---|---|
| HOME-01 | Hero | PS-HERO-CHOICE | Container + Heading + Text + Buttons + Image | split | copy→image |
| HOME-02 | decision problem | PS-PLAUSIBLE-CHOICES | Containers/Text/Icon | 3–4 grid | stack |
| HOME-03 | narrowing | PS-NARROWING-PROCESS | Containers/Text/Icon | 4+4 | 1 col |
| HOME-04 | evidence | PS-EVIDENCE-CHAIN | Containers/Text | chain + 4 statuses | vertical |
| HOME-05 | what not to do | PS-NOT-DO | Containers/Text | editorial grid | stack |
| HOME-06 | reality test | PS-BRIDGE-VERIFY | Containers/Text/Icon | process | vertical |
| HOME-07 | products | PS-PRODUCT-CONTOUR | Containers/Text/Button | 4 cards | stack |
| HOME-08 | artifacts | PS-ARTIFACT-GROUPS | Containers/Text | clusters | stack |
| HOME-09 | depth | PS-DEPTH | Containers/Heading/Text | split/proof figures | stack |
| HOME-10 | cases | PS-CASE-CARDS | Containers/Text/Button | 3 cards | stack |
| HOME-11 | anti-category | PS-ANTI-CATEGORY | Containers/Text | paired comparison | paired stack |
| HOME-12 | entry | PS-QUALIFICATION | Containers/Text/Button | split | stack |
| HOME-13 | FAQ | PS-FAQ | Accordion or text fallback | 2-zone/1col | 1col |
| HOME-14 | final CTA | PS-FINAL-CTA | Container/Text/Button | centered/bounded | stack |

## 4. Supporting page map

### /how-it-works/
PS-HERO-CHOICE (text-led variant, no reuse of Hero art as decorative duplicate)
→ PS-NARROWING-PROCESS
→ PS-EVIDENCE-CHAIN
→ PS-BRIDGE-VERIFY
→ PS-ARTIFACT-GROUPS
→ PS-FINAL-CTA.

### /diagnostics/
Product intro
→ qualification/inputs
→ six-criteria explanatory grid
→ four verdicts
→ artifacts
→ transition/stop logic
→ CTA.

### /session/
Product intro
→ confirmed-diagnosis prerequisite
→ strategic narrowing
→ operational candidates
→ Bridge
→ Sprint charter
→ transition/return/stop
→ CTA.

### /sprint/
Product intro
→ 3–5 instrument boundary
→ owners/baseline/rhythm/metrics
→ 30/60/90 control
→ decision log/artifacts
→ possible verdicts
→ CTA.

### /support/
Product intro
→ active-object prerequisite
→ sustainability/drift
→ artifacts
→ continue/reduce/new Sprint/rebuild/exit
→ CTA.

### /cases/
Intro + evidence boundary
→ static PS-CASE-CARDS grid
→ case detail sections as static containers
→ CTA.
No dynamic loop dependency.

### /technology/
Definition
→ selection discipline
→ evidence chain
→ expert depth
→ roles/boundaries
→ anti-category
→ CTA.

### /faq/
Grouped PS-FAQ sections
→ CTA.

## 5. Header/footer
Blocksy header:
- logo/brand;
- Как это работает;
- Что проверяем;
- Продукты;
- Кейсы;
- О технологии;
- FAQ;
- CTA “Разобрать управленческую ситуацию”.
Tablet/mobile: Blocksy native accessible menu; CTA retained if it does not crowd viewport.

Blocksy footer:
- short category definition;
- product links;
- mechanism/technology/cases/FAQ links;
- contact/legal placeholders only when source/owner data exists.
No invented social/contact details.

## 6. Responsive rules
Breakpoints follow actual Blocksy/Elementor project settings at implementation; do not invent custom breakpoint dependencies unless needed.
- Desktop: preserve visual breathing room and bounded reading widths.
- Tablet: grids collapse 4→2; process sequences 4+4→2-column; Hero may stack if split becomes compressed.
- Mobile: all core reasoning becomes one semantic column; copy before supporting visual; no horizontal scroll; no carousel required.
- Canonical Hero image remains same asset. Crop/object-position must retain as much as practical of: final selected object + constraint planes + alternative field.
- No essential information exists only in imagery.

## 7. Feasibility gate
PASS on Elementor Free baseline:
- all structures can be built with Containers, Heading, Text Editor, Image, Button, Icon and optional Accordion;
- no Pro loop, forms, dynamic fields, custom query or hover dependency required;
- case/product collections are static at MVP;
- any future form integration is separate implementation decision.

## 8. Claude Design boundary
Claude may refine geometry, spacing, hierarchy and responsive proportions inside the locked semantics and future Design System.
Claude may NOT:
- reorder semantic jobs;
- turn 95/115 into a catalog;
- make products a mandatory ladder;
- regenerate/replace Hero art;
- introduce dashboard/SaaS/AI framing;
- remove Hold/Stop/do-not-touch logic;
- silently add Pro/plugin dependencies.

## 9. S06 result
Elementor Free implementation architecture is defined with custom Container baselines, reusable components, page-to-section map, responsive behavior and feasibility constraints.
No unverified Elementor library block is represented as selected.

Next: S07 Block Specification.
