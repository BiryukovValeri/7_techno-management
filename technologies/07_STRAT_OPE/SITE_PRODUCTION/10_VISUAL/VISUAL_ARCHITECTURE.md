# S10 — VISUAL ASSET ARCHITECTURE — проSTRAнство
Status: REVISED FINAL
Dependencies: T1 / M / H / A / C LOCK; S09 PASS

# 1. Visual model
The site uses three distinct layers:

1. **Image slots** — images that help the reader perceive and understand the information of the site. They support reading rhythm, comprehension and emotional/semantic orientation.
2. **Technology visualizations** — finished semantic images that explain a part of the technology. They are stronger than ordinary supporting images and must be used selectively.
3. **Native interface graphics** — Elementor containers, cards, status blocks, timelines and typographic/data compositions. They structure information but do not replace image slots or technology visualizations.

A website must not become a slide deck. Therefore the 12 existing technology visualizations are a source corpus, not a set to be inserted wholesale.

# 2. Governing visual principle
The site explains the technology first. Visuals support this explanation and leave controlled traces of technological depth.

Target:
- **3–4 technology visualizations across the entire site**, including only those that materially explain the mechanism;
- a separate system of supporting image slots where imagery improves perception;
- native Elementor graphics for structural information.

No requirement to put an image into every section.

# 3. Hero — FINAL / OWNER LOCK
The owner-selected first wide Hero image remains the main visual anchor.
Status: **FINAL / LOCK H**.
It is an image slot and a governing conceptual image, but it is not counted as one of the 3–4 legacy technology visualizations.

Use one binary on desktop/tablet/mobile. Crop/object-position only. No alternate mobile Hero.

# 4. Technology visualizations — selection ceiling
Maximum production set: **4**.

## TV-01 — Narrowing the decision space
Role: explain the central mechanism: many plausible options → evidence/triggers → bounded working choice.
Source candidate: legacy visualization 05 “Отбор стратегических фреймворков”, rebuilt/revalidated against current M/C locks.
Placement: HOME-03; reusable on /how-it-works/ if needed.
Status: **SELECTED FOR PRODUCTION REWORK**.

## TV-02 — Bridge to operational execution
Role: show how a justified strategic choice becomes an operational carrier with owner, metric, rhythm and verification.
Source candidate: legacy visualization 06 “Мост к операционным инструментам”.
Placement: HOME-06 or /session/.
Status: **SELECTED FOR PRODUCTION REWORK**.

## TV-03 — Sprint 30–60–90 / reality check
Role: show that execution is a test of the chosen contour, not a ceremonial final stage.
Source candidate: legacy visualization 10.
Placement: /sprint/ and optionally a reduced reference on HOME-06/07 only if not repetitive.
Status: **SELECTED FOR PRODUCTION REWORK**.

## TV-04 — Conditional
Candidate role: demonstrate either evidence/diagnostic logic or anti-catalog depth, only if the final page composition genuinely needs a fourth technology visualization.
Candidate sources: legacy 03 or 02.
Status: **OPTIONAL / NOT AUTOMATICALLY INCLUDED**.

Hard rule:
- 01, 08 and other legacy visuals are not inserted merely because they exist.
- No page becomes a gallery of diagrams.
- One visualization may be reused responsively/contextually, but duplicated full-size appearances should be avoided.

# 5. Supporting image slots
Image slot means a visual that helps the reader perceive the site content. It may be a conceptual image, contextual image, restrained illustration or designed still. It is not necessarily a technology diagram.

## IS-01 Hero
HOME-01. Locked canonical image.

## IS-02 Decision ambiguity
HOME-02 “Почему разумного решения недостаточно?”
Purpose: visually support the feeling of several equally plausible routes before evidence narrows them.
Production: new supporting conceptual image or design-system still.
Must not duplicate Hero’s exact “filter planes” composition.

## IS-03 Do-not-touch / preserve what works
HOME-05.
Purpose: help perceive the distinction between “изменить” and “не разрушить работающий контур”.
Production: supporting conceptual image.
Must avoid danger/alarm cliché.

## IS-04 Artifacts / tangible output
HOME-08 or one product page.
Purpose: make the technology feel materially operational through real-looking but non-fake artifact composition.
Production: designed still based on actual public artifact types; no fabricated dashboards or fake client screenshots.

## IS-05 Cases context
HOME-10 / /cases/.
Purpose: provide visual rhythm and distinguish case territory from mechanism territory.
Production: one master contextual visual system or restrained sector illustrations. Do not create 12 unrelated stock images.

## IS-06 Technology depth
HOME-09 or /technology/.
Purpose: support the idea “large internal knowledge base → small working set”.
Production: conceptual image only if TV-04 is not used for this job. Never both merely for decoration.

Image-slot count is not a quota. IS-02–IS-06 are production slots justified by comprehension; final design may merge or omit a slot if the semantic job is already fully carried by a selected technology visualization.

# 6. Native graphics — where images are NOT needed
Use Elementor/native composition for:
- four diagnostic verdicts;
- six diagnostic criteria;
- product contour and conditional transitions;
- qualification conditions;
- FAQ;
- CTA blocks;
- compact artifact lists;
- status comparisons;
- internal links/navigation.

These are interface/information structures, not image slots.

# 7. Legacy 12-visualization corpus
| Legacy | Decision |
|---|---|
| 01 Ядро: от проблемы к исполнению | EXCLUDED AS-IS — generic strategy→execution risk |
| 02 Не каталог моделей | RESERVE candidate for TV-04 |
| 03 Диагностика | RESERVE candidate for TV-04 |
| 04 Экспертная система триггеров | REFERENCE only; protected-logic risk |
| 05 Отбор стратегических фреймворков | SELECTED → TV-01 rework |
| 06 Мост к операционным инструментам | SELECTED → TV-02 rework |
| 07 Операционные инструменты и измерители | REFERENCE only |
| 08 Клиентский путь 4 продуктов | EXCLUDED AS-IS — false linearity risk |
| 09 Сессия | REFERENCE only |
| 10 Спринт 30/60/90 | SELECTED → TV-03 rework |
| 11 Кейсовая схема | REFERENCE only |
| 12 Антипозиционирование | REFERENCE only |

Thus only **3 are currently selected**, with **1 reserve slot**. The other 8 are not production images.

# 8. Distribution / rhythm
Homepage target:
Hero image + 2–4 supporting image slots + no more than 2 full technology visualizations.

Internal pages:
technology visualization only where it explains a mechanism better than text/native layout.
Avoid placing full technology diagrams in consecutive sections.

The desired rhythm is:
**content → supporting image → content/native structure → technology visualization → content**, not “slide after slide”.

# 9. Responsive
Hero: same locked binary.
Supporting images: crop safely; no essential text inside raster.
Technology visualizations: do not solve mobile by destructive crop. Produce/recompose responsive version or rebuild labels as live text where possible.
No horizontal scroll required to understand a visualization.

# 10. Accessibility
Every technology visualization has a nearby text explanation.
Supporting images never carry unique factual claims.
Decorative assets use empty alt.
Meaningful assets use factual alt without SEO stuffing.
Status is not communicated by color alone.

# 11. Production boundary
S10 defines slots and selects visualization jobs; it does not generate assets automatically.
S11 must tell Claude Design which slots need visual production and which technology visualizations must be adapted.
Claude may improve composition/style but may not change the semantic role or introduce additional presentation-like diagrams.

# 12. DoD
- distinction image slot / visualization / native graphic: PASS
- Hero locked: PASS
- visualization ceiling 3–4: PASS
- 12 legacy visuals selectively classified: PASS
- supporting image slots defined: PASS
- site protected from “presentation instead of website”: PASS
- responsive/accessibility rules: PASS

**S10 REVISED RESULT: PASS**
