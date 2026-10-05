# FINAL CORRECTION SPEC — CLAUDE DESIGN → ELEMENTOR
Status: EXECUTION SPEC / LAST CLAUDE PASS BEFORE GATE F
Date: 2026-10-05
Technology: Архитектура Переговоров
Domain: nego.7vctr.ru

## 0. Mission
Do NOT redesign the approved site. Complete the missing evidence, instrument, visual and deterministic-transfer layers, and correct the audited production defects.

Current design/content direction is frozen as:
**DESIGN_CONTENT_V2_APPROVED_FOR_TRANSFER_FIXES**

This pass must return ONE complete corrected full-site package. No homepage pilot. No intermediate stop.

## 1. Frozen — must not change
- approved Hero image/direction;
- governing message;
- Russian-first public language;
- canonical 10-step mechanism;
- one core / two fields;
- four peer products only: Диагностика / Сессия / Спринт / Сопровождение;
- no mandatory product funnel;
- no old public prices/durations;
- Forms 17–23 only;
- 12 cases are model/educational, not client testimonials;
- current full case bodies;
- current page architecture/navigation;
- Warm Paper / Deep Navy / Copper / Muted Teal visual system;
- no handshake/chess/duel/winner/SaaS-dashboard visual language.

## 2. Authoritative inputs for this pass
Read and implement, with later/current locks overriding legacy conflicts:
- 04E_TECHNOLOGY_EXPLANATION_MASTER.md
- 04F_CONTENT_MASTER_V2_HOME_TECHNOLOGY.md
- 04G_CONTENT_MASTER_V2_PRODUCTS_TOOLS.md
- 04H_CONTENT_MASTER_V2_CASES.md
- all 04B_FULL_CASES/A3-01…A3-12.md
- 05A_VISUAL_ASSET_ARCHITECTURE_V2.md
- 05B_FORMS_VISUAL_RECOVERY_SPEC.md
- 05C_VISUAL_EXPANSION_SPEC_V3.md
- BATNA_ZOPA_PROVENANCE_PUBLIC_EXPLANATION.md
- 06_SEO_GEO_DYNAMIC_CONTRACT.md
- 08_ACCEPTANCE_CRITERIA.md
- PRE_CLAUDE_PACKAGE_CONSISTENCY_AUDIT_V2.md
- current full-site build as the design base.

## 3. BATNA / ZOPA — mandatory content correction
At first meaningful occurrence, never show unexplained abbreviations.

Required:
**BATNA — Best Alternative to a Negotiated Agreement — лучшая альтернатива соглашению.**
**ZOPA — Zone of Possible Agreement — зона возможного соглашения.**

Add a compact provenance/explanation block on /technology/:
- BATNA: Harvard negotiation tradition; Roger Fisher / William Ury; later editions of Getting to Yes with Bruce Patton.
- ZOPA: standard negotiation concept; explain bargaining/agreement range without inventing a single historical inventor.
- clearly state these are external negotiation concepts incorporated into Архитектура Переговоров, not inventions/trademarks of 7VCTR.
- explain WHY each is included:
  BATNA = reference outside agreement / rational exit alternative.
  ZOPA = reference inside potential agreement / acceptable-condition search space.
- preserve full method, not dictionary-only definitions.

Do not add a history of Архитектура Переговоров here. This provenance requirement concerns BATNA and ZOPA only.
Do not make trademark claims.

## 4. Tools — real Forms 17–23 must be visible
/tools/ must become a demonstration of working instruments, not a list of names.

Implement seven Tool Previews TP-17…TP-23 exactly from 05B.
Each must show a faithful public-safe fragment/reconstruction of the real XLSX fields plus:
- Для чего
- Что заполняется
- Какое решение помогает принять
- Где в цикле
- Что ломается без формы

Do not invent data. Blank/neutralize example-specific values. Do not expose internal source-line references.

Special requirements:
- TP-18 visibly distinguishes goals, BATNA, ZOPA and summary decision.
- TP-23 visibly demonstrates plan/fact + improvement log + next-cycle decision.
- reduced TP-18 may appear in Technology BATNA/ZOPA section.
- reduced TP-21 may appear in concessions section.
Tool Previews are NOT Image Slots.

## 5. Visual expansion
Existing approved Technology Visualizations:
TV-02 / TV-05 / TV-06 / TV-12.

Add:
### TV-N01 canonical 10-step route
Exact current 10-step order + return to next cycle. This is the canonical cycle visualization. Do not use old viz-01 as cycle.

### TV-N02 internal mandate → external position
Internal alignment of goal/minimum/authority/red lines/concession price/pause owner → agreed mandate → external participant/influence/BATNA/ZOPA/packages/decision.
Not an org chart.

### TV-N03 architecture of one management decision
Goal+minimum → BATNA → bad-agreement boundary → ZOPA → package → concession↔counterstep → authority/risk check → continue/conditions/clarify/pause/exit → fixation.

Final Technology Visualization family: 02,05,06,12,N01,N02,N03.

## 6. Image Slots
Implement contextual Image Slots:
- IS-01 internal alignment before external round: Home H02–H04 OR Technology before N02, once.
- IS-02 negotiation as system of participants/decision centers: Technology participant/influence section.
- IS-03 post-round fixation/review/next actions: Technology T12 OR Tools before Form 23.
- IS-04 real author portrait only if an Owner-approved real portrait is supplied. If not, reserve/no substitute.

No stock handshake, staged victory, chess, duel, fake client success or generic AI imagery.

## 7. P0 — deterministic materialization
The corrected package must not require an Elementor implementer to reconstruct page meaning from Claude runtime logic.

### Products
Materialize four complete public page layouts:
- /products/diagnostics/
- /products/session/
- /products/sprint/
- /products/support/

Shared visual components are allowed, but every page must have its full source-specific copy/sections visibly resolved. A wrapper containing only a title + ProductBody + JSON is NOT accepted as handoff.

### Cases
Provide either:
A) 12 fully materialized page layouts; OR
B) one fixed Elementor Case Template plus 12 complete, human-readable Content Payloads with exact field→section mapping.

Option B is preferred for maintainability only if it is fully deterministic and requires no semantic interpretation.

### FAQ
Transfer payload must contain all approved FAQ Q&A, not unresolved runtime tokens.

### Tools
Seven resolved Tool Preview records and copy.

### Runtime tokens
No unresolved {{p.name}}, {{c.title}}, {{q.q}}, {{listTitle}} or equivalent template variables may remain in the Elementor handoff.

## 8. P0 — Elementor Transfer Spec
Create a standalone **ELEMENTOR_TRANSFER_SPEC.md**.

For EVERY public page section define:
- Page URL
- Section ID
- purpose
- Elementor container hierarchy
- direction
- content width / max-width
- padding Desktop / Tablet / Mobile
- gap Desktop / Tablet / Mobile
- alignment
- widget/component type
- exact content source/payload
- typography token
- background
- border
- radius
- asset filename/ID
- CSS class
- responsive behavior
- visibility rule
- link target
- interaction behavior if any
- implementation note

No “designer decides”, “adjust visually”, “as appropriate”, “choose one” instructions.

Explicitly lock production representation for every visual:
- TV-02
- TV-05
- TV-06
- TV-12
- TV-N01
- TV-N02
- TV-N03
- TP-17…TP-23
- IS-01…IS-04

If PNG is used on Desktop and semantic HTML/reconstruction on Mobile, specify that exact behavior. Do not leave PNG-vs-HTML to Elementor implementer.

Stack constraint: WordPress + Blocksy + Elementor Free. Do not silently require Elementor Pro, ACF, CPT, or a new plugin.

## 9. Production cleanup
Mandatory:
- update or remove stale LOCK_CHECK.md statements, especially SOURCE_UNREADABLE for cases;
- remove stale UNRESOLVED items that are actually resolved;
- remove viz-01-yadro.png from production handoff;
- remove duplicate H1 on Home;
- ensure Article template is reference/template only and cannot become an indexed fake article;
- remove obsolete/unused Claude artifacts from the Elementor handoff;
- ensure there is one current source of truth.

## 10. Cases semantic cleanup
Keep all 12 full model cases.

Public wording must not imply a real client result.
Where wording like «После применения технологии…» reads as testimonial before/after, replace with source-faithful model framing such as:
- «При проходе ситуации через технологию постановка решения меняется…»
- «В модели Архитектуры Переговоров вопрос перестраивается так…»

Do not change the modeled decision itself.
Keep disclosure that cases are educational/model and figures/roles conditional.

## 11. Responsive QA
Do not self-certify responsive PASS from code alone.

Produce and verify rendered states at minimum:
- Desktop 1440
- Tablet 1024
- Tablet 768
- Mobile 390

Check:
- semantic reading order;
- no horizontal overflow;
- 10-step route remains understandable;
- BATNA/ZOPA relationships survive;
- concessions relationship survives;
- Tool Previews remain legible;
- long case pages remain navigable/readable;
- tables do not become microscopic screenshots;
- menu/touch targets work;
- no essential content is hidden on Mobile.

Record result per page as PASS / FAIL + correction.

## 12. Accessibility QA
Verify:
- exactly one H1 per public page;
- coherent H2/H3 hierarchy;
- meaningful alt text for informative images;
- decorative images use empty alt where appropriate;
- keyboard navigation;
- visible focus;
- FAQ accordion keyboard behavior;
- mobile menu keyboard/touch behavior;
- link/button semantics;
- adequate tap targets;
- no meaning conveyed only by color.

Return an accessibility defect log and corrected status.

## 13. SEO/GEO boundary
Design/package must define, and WordPress deployment checklist must implement:
- canonical URLs;
- trailing slash policy;
- HTTPS;
- www→canonical redirect;
- sitemap inclusion;
- breadcrumbs;
- Article eligibility/indexation;
- noindex for templates/empty placeholders;
- FAQ structured-data eligibility only when content is actually visible and valid;
- article structured data only for real published article bodies;
- archive behavior;
- redirects.

Do not claim WordPress deployment PASS before it is deployed. Separate:
DESIGN SEO PASS vs WORDPRESS SEO PENDING.

## 14. Final page/content acceptance
Required public pages remain:
/
/technology/
/products/
/products/diagnostics/
/products/session/
/products/sprint/
/products/support/
/tools/
/cases/
/cases/{12 pages}
/articles/
/articles/{slug}/ template/reference only until real body exists
/faq/
/about/
/author/
/contact/

Primary navigation remains:
Технология | Продукты | Кейсы | Инструменты | Статьи
CTA: Обсудить ситуацию

## 15. Required output package
Return:
1. corrected full-site design package;
2. all materialized/deterministic page payloads;
3. ELEMENTOR_TRANSFER_SPEC.md;
4. VISUAL_REGISTER_FINAL.md with exact page/section placement and implementation mode for every visual object;
5. RESPONSIVE_QA.md with 1440/1024/768/390 results;
6. ACCESSIBILITY_QA.md;
7. WORDPRESS_SEO_DEPLOYMENT_CHECKLIST.md;
8. updated clean LOCK_CHECK.md or replacement truth manifest;
9. CHANGELOG_FINAL_CORRECTION.md mapping each audited defect D01–D13 to CLOSED / OPEN with evidence;
10. final list of any remaining SOURCE-MISSING item.

## 16. Defect closure matrix
D01 Elementor Transfer Spec — must CLOSE.
D02 product wrappers/runtime — must CLOSE.
D03 case materialization — must CLOSE.
D04 unresolved runtime tokens — must CLOSE.
D05 responsive unverified — must CLOSE by rendered QA.
D06 stale LOCK_CHECK — must CLOSE.
D07 PNG vs HTML ambiguity — must CLOSE in Transfer Spec.
D08 viz-01 in handoff — must CLOSE.
D09 duplicate Home H1 — must CLOSE.
D10 SEO deployment controls — design/checklist CLOSE; live WordPress status may remain PENDING.
D11 Article template indexability — must CLOSE.
D12 before/after model-case wording — must CLOSE.
D13 accessibility QA — must CLOSE.

Additional owner defects:
O01 BATNA/ZOPA full names + provenance + why selected — must CLOSE.
O02 Forms visible as real tools — must CLOSE.
O03 insufficient contextual Technology Visualizations — must CLOSE with N01/N02/N03.
O04 insufficient Image Slots — must CLOSE with IS-01/02/03 and conditional IS-04.
O05 Tool Previews are separate class and must not be counted as Image Slots — must CLOSE.

## 17. Stop condition
Do not return “COMPLETE” merely because data exists in JSON/runtime.
COMPLETE means:
- public page meaning is resolved;
- content is source-backed;
- visual object is placed;
- Elementor implementation is deterministic;
- responsive state is verified;
- accessibility state is verified;
- no contradictory package truth remains.

Do not redesign. Do not invent. Complete and harden the approved site for deterministic WordPress/Elementor transfer.
