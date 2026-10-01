# QUALITY_RECOVERY_REGISTER — pre-S11
Status: ACTIVE / S11 BLOCKED
Date: 2026-10-01

## Purpose
Prevent semantic/content/visual degradation between approved corpus and Claude Design output. This is a targeted recovery; T1/M/H/A/C meanings remain locked unless an explicit owner change is required.

| ID | Defect | Current evidence | Risk | Required repair |
|---|---|---|---|---|
| QR-D01 | Generic Elementor architecture | S06 mostly grid/split/cards/container feasibility | Claude invents composition | Rebuild S06 as design-intent + semantic composition + feasibility envelope |
| QR-D02 | Block spec lacks forbidden simplifications | S07 maps jobs but not enough composition invariants | mechanism becomes generic cards | Rebuild S07 after S06 |
| QR-D03 | No end-to-end content coverage | Traceability stops upstream and is stale | content loss downstream | CONTENT_COVERAGE_MATRIX source→content→design→HTML |
| QR-D04 | Case compression | CASE_CONTENT_MASTER has summaries, not full public bodies | source evidence lost | restore 12 public-safe full case bodies + summary layer |
| QR-D05 | Hero metaphor can leak into image slots | S10 contextual motifs overlap dossier/map language | cloned visual metaphor | separate Hero / Image Slot / Semantic Visualization contracts |
| QR-D06 | Web adaptations lack deterministic semantic diff | S10 says preserve/compare but no node-relation checklist | visual meaning drift | preservation contracts for 01/02/05 |
| QR-D07 | Claude design freedom not bounded | “visual style may be refined by Claude” | reinterpretation of locks | LOCKED / CONSTRAINED / DESIGNABLE authority |
| QR-D08 | No executable Russian-first gate | internal English terminology may leak public | mixed-language site | public lexicon + final HTML audit, 0 unauthorized terms |
| QR-D09 | Missing public About Project / About Author records | no source-backed author/about file found in current corpus | incomplete trust/provenance layer | architecture slots required; content HOLD until owner/source data |
| QR-D10 | Articles absent from S09 | S09 explicitly rejected hub | weak SEO/GEO knowledge layer | add source-governed Articles hub + article template; no invented article corpus |
| QR-D11 | Contact exists but implementation/current data HOLD | /contact/ architecture exists; current route not verified | dead conversion | preserve Contact page; resolve route/privacy before handoff |
| QR-D12 | Self-audit could be mistaken for acceptance | no independent build verification contract yet | false PASS | independent SOURCE→CONTRACT→BUILD→VERIFY audit |
| QR-D13 | Hero binary not repository-attached | H-LOCK metadata exists; binary path not normalized | wrong Hero attachment | identify/attach exact approved binary before S11 |
| QR-D14 | Output path drift | strategy/hero folders differ from V4 standard | stale/wrong package inputs | normalize package inputs or explicit mapping before S11 |

## New owner additions 2026-10-01
Mandatory public architecture now includes:
- О проекте;
- Об авторе;
- Контакты;
- Статьи as SEO/GEO knowledge layer.

Important: no biography, credentials, contacts, article claims or article inventory may be invented. Missing source data remains explicit HOLD while architecture is prepared.

## Stop rule
No Claude Design package and no Claude Design generation until QR-01…QR-10 recovery controls are complete and blocking HOLDs for actual handoff assets/current contact identity are resolved.
