# ELEMENTOR_BUILD_SHEET
Status: S06 FEASIBILITY PASS

| Family | Container geometry | Content / visual | Responsive | Blocksy/Elementor | Risk |
|---|---|---|---|---|---|
| EL-HERO | parent row; 46/54 | HTML copy + H-LOCK image | mobile copy first; art crop right-focus | header Blocksy; body Elementor | LOW |
| EL-KNOWLEDGE-STRIP | wrapping grid | 4–8 semantic items | 2→1 cols | Elementor | LOW |
| EL-EXPLANATORY-SPLIT | 50/50 or 42/58 | copy + semantic visual/diagram slot | stack by semantic order | Elementor | LOW |
| EL-PROJECTION | 2 equal cards/panels | external/internal | stack | Elementor | LOW |
| EL-PROCESS | responsive grid; no JS | 10 numbered steps | linear 1-col | Elementor | LOW |
| EL-STATUS | 3-col/wrap | valid outcomes | 1-col/2-col | Elementor | LOW |
| EL-PRODUCT-GRID | exactly 4 cards | product records | 2→1 | Elementor | LOW |
| EL-PRODUCT-DETAIL | editorial containers | source-locked content | stack | Elementor | LOW |
| EL-CASE-GRID | manual cards initially | approved cases only | 3→2→1 | Elementor | MEDIUM: no Loop Builder |
| EL-CASE-DETAIL | editorial containers | case record | stack | Elementor | LOW |
| EL-TOOL-GRID | manual 7-card grid | Forms 17–23 | 3→2→1 | Elementor | LOW |
| EL-EVIDENCE | split/list | bounded evidence | stack | Elementor | LOW |
| EL-ANTI-CATEGORY | 2 panels | boundaries | stack | Elementor | LOW |
| EL-FAQ | readable 1-col | FAQ records | same | Elementor Free accordion/toggle or plain headings | LOW |
| EL-CTA | centered/split band | one action | stack | Elementor | LOW |
| EL-FORM | copy + form slot | context capture | stack | mechanism not assumed | BOTH | HOLD until approved form mechanism |
| EL-CONTACT | split | current contact data | stack | Elementor | LOW |

## Global configuration
- no essential information in hover state;
- keyboard-visible links/buttons;
- images require alt text or decorative null alt as appropriate;
- headings preserve hierarchy;
- H-LOCK image uses object-position/right focal behavior;
- reusable cards use consistent padding/radius/border tokens supplied by eventual Design System;
- visual style may be refined by Claude but semantic order and section job are locked upstream.

## Feasibility
All required semantic families have an Elementor Free custom-Container implementation path.
Only contact form mechanism remains a downstream implementation HOLD; it does not block page architecture because a direct contact CTA is a safe baseline.
