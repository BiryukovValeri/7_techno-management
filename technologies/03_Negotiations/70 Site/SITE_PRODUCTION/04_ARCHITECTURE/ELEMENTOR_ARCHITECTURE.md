# ELEMENTOR_ARCHITECTURE — Архитектура Переговоров
Status: S06 FEASIBILITY PASS
Stack: WordPress + Blocksy + Elementor Free

## Responsibility
Blocksy: global header/navigation, footer, global page shell, typography/color tokens where practical, legal/footer navigation.
Elementor Free: page-body sections, grids/containers, headings/text/buttons/images/icons, accordion/toggle where available in Free, forms only if an already-approved stack component exists; otherwise contact CTA/link is baseline.

## Baseline
No Elementor Template Library/My Templates account access was available in this documentation run. Therefore no library template is claimed as selected. All production sections use **custom Flexbox/Grid Container baseline** with Elementor Free widgets. Any later library substitution must preserve semantic job and Free-stack feasibility.

## Responsive system
Desktop: max content width ~1200–1280px; section padding 72–104px depending density.
Tablet: two-column sections collapse selectively; 40–64px section padding.
Mobile: single semantic column; 24–40px section padding; content order follows meaning, not desktop geometry.
Hero: H-LOCK left copy / right art on desktop; mobile copy → primary CTA → cropped art → supporting content.

## Dependencies
No Elementor Pro, ACF, loop builder, popup builder, dynamic tags, premium carousel or new plugin is assumed.
