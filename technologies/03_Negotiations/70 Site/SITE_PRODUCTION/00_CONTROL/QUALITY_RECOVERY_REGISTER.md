# QUALITY_RECOVERY_REGISTER — pre-S11
Status: ACTIVE / HANDOFF PACKAGE BUILT / FINAL GATE NOT YET OPEN
Date: 2026-10-01

## Purpose
Prevent semantic/content/visual degradation between approved corpus and Claude Design output. This is a targeted recovery; T1/M/H/A/C meanings remain locked unless an explicit owner change is required.

| ID | Defect | Current evidence | Risk | Required repair |
|---|---|---|---|---|
| QR-D01 | Generic Elementor architecture | CLOSED by DESIGN_INTENT_ARCHITECTURE | — | CLOSED 2026-10-01 |
| QR-D02 | Block spec lacks forbidden simplifications | CLOSED by knowledge-transfer Block Specification + package 03 | — | CLOSED 2026-10-02 |
| QR-D03 | No end-to-end content coverage | CLOSED by CONTENT_COVERAGE_MATRIX | — | CLOSED 2026-10-01 |
| QR-D04 | Case compression | CASE_CONTENT_MASTER has summaries, not full public bodies | source evidence lost | restore 12 public-safe full case bodies + summary layer |
| QR-D05 | Hero metaphor can leak into image slots | CLOSED by visual-class separation and package 05 | — | CLOSED 2026-10-02 |
| QR-D06 | Web adaptations lack deterministic semantic diff | S10 says preserve/compare but no node-relation checklist | visual meaning drift | preservation contracts for 01/02/05 |
| QR-D07 | Claude design freedom not bounded | CLOSED by authority contract + Design Intent + package 07 | — | CLOSED 2026-10-02 |
| QR-D08 | No executable Russian-first gate | CLOSED upstream by PUBLIC_LANGUAGE_GATE; final rendered audit still mandatory | — | CONTROL ACTIVE |
| QR-D09 | Missing public About Project / About Author records | CLOSED by Owner-approved author/contact/project content | — | CLOSED 2026-10-02 |
| QR-D10 | Articles absent from S09 | CLOSED by updated SEO_GEO_DYNAMIC_CONTRACT | — | CLOSED 2026-10-02 |
| QR-D11 | Contact route | CLOSED: Owner-approved Telegram/email route; no form required | — | CLOSED 2026-10-02 |
| QR-D12 | Self-audit could be mistaken for acceptance | Acceptance criteria explicitly deny self-PASS; independent final audit required | false PASS | CONTROL ACTIVE |
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
Claude Design package now exists. Do not issue final Owner Gate F until: (1) exact FINAL Hero binary is attached/verified; (2) full 12 case bodies are available to Claude from source or curated full-body package; (3) semantic preservation/pilot visual review is completed; (4) independent final handoff audit passes.
