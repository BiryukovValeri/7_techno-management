# PRE-CLAUDE PACKAGE CONSISTENCY AUDIT V2
Status: NO-GO → CORRECTION INSTRUCTION READY
Date: 2026-10-03
Scope: current Claude build archive + current recovered production package.

## 1. Current build inspected
Archive inspected: ТУПЩ.zip.
It contains the expected page/template family, but content completeness is materially below the current V2 masters.

Observed:
- Home.dc.html: substantive content exists, but predates final V2 narrative/visual decisions.
- Technology.dc.html: substantive but materially thinner than 04F; BATNA/ZOPA and other methods are not yet at required depth.
- Products.dc.html: thin.
- Diagnostics.dc.html / Session.dc.html / Sprint.dc.html / Support.dc.html: wrapper-level files with almost no page body; content is delegated to ProductBody and is therefore not four independently complete public pages.
- Tools.dc.html: thin relative to 04G.
- Cases.dc.html: index exists but thin relative to 04H.
- Case.dc.html: generic template exists; full 12 source bodies are not physically populated as 12 complete case pages.
- FAQ/About/Author/Contact exist.
- Articles hub/template exist; no invented article bodies should be added.
- Assets currently include viz 01/02/05/12. Current visual authority requires 02/05/06/12; viz 06 is absent from this archive and viz 01 must not be used as canonical cycle.

## 2. What must be preserved
- approved Hero asset and hero direction;
- useful existing design system/components;
- current public page architecture;
- Russian public UI;
- four peer products;
- model-case status;
- Blocksy + Elementor Free feasibility.

## 3. What must change before Gate F
### Home
Reconcile against 04F. Preserve the continuous causal narrative; add current visual 06 where functionally placed; do not use 01 as cycle.

### Technology
Major content expansion required. Must implement T01–T15 from 04F, especially:
- 10-step what/question/tool/output depth;
- full BATNA method;
- full ZOPA method;
- why both;
- concessions;
- influence/authority;
- cognitive risks;
- outcomes;
- closed loop/forms.

### Products
Products index and four detail pages must implement 04G.
Four pages cannot remain one generic ProductBody with only variable labels if that causes content loss. Shared components are allowed; source-specific page bodies are required.

### Tools
Implement Forms 17–23 individually with function/capture/cycle/output/boundary plus the complete forms↔cycle map.

### Cases
Implement 04H and all 12 full A3 source bodies.
A generic Case template is acceptable technically, but the deliverable must prove that all 12 public pages can be populated with their full source-derived bodies, not only summary variables.

### Visuals
Current public default set: 02,05,06,12.
Remove 01 from any canonical-cycle role.
Do not use 03/07/09/11 as-is.
Add/rebuild 06 from the approved source visualization without semantic alteration.

### FAQ / About / Author / Contact
Retain, but verify against current approved content and language gate.

### Articles
Keep honest empty/source-governed state unless actual approved article bodies exist.

## 4. Package authority conflicts resolved
- 04F supersedes old Home/Technology copy.
- 04G supersedes old Products/Tools copy.
- 04H + 04B full sources supersede case summaries.
- 05A supersedes prior visual selection.
- Current four-peer-product lock supersedes legacy source funnel/duration/pricing.
- No old source visualization may override current ontology.

## 5. Gate result
Current site archive: **FAIL / NOT READY FOR FINAL HANDOFF**.
Reason: CONTENT_LOSS + CASE_TRUNCATION + PRODUCT_PAGE_THINNESS + VISUAL_AUTHORITY_DRIFT.

This is not a design-style failure. It is a content-completion failure relative to the now-recovered corpus.

## 6. Recovery action
Use 10_CONTENT_COMPLETION_PATCH.md as the execution instruction.
After Claude returns the revised full-site package, rerun this audit against every required page and only then decide Gate F.
