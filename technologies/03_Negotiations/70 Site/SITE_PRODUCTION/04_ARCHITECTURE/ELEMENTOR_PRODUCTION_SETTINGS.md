# ELEMENTOR PRODUCTION SETTINGS — nego.7vctr.ru

Status: FINAL HANDOFF CONTRACT
Target: WordPress + Blocksy + Elementor Free

## Hard stack
Elementor Free V3 Containers (Flexbox/Grid). NO Sections/Inner Sections. NO Atomic V4. NO Elementor Pro. NO ACF/Loop Builder/premium dependency. Blocksy native Header/Footer. Ordinary content uses native Elementor widgets; no mass HTML.

## Breakpoints
Desktop >=1025 px; Tablet 768–1024 px; Mobile <=767 px.

## Global geometry
Content max-width 1240 px.
Text measure 680–760 px; wide explanatory/diagram measure up to 980 px.
Side padding: 32 px desktop / 28 tablet / 20 mobile.
Section vertical padding: major 96/72/48; normal 72/56/40; compact 48/40/32 px.
Major section gap 32/28/24 px.
Grid/card gap 24/20/16 px.
Typography, colors, radii, borders and shadows come from Owner-supplied Design System.

## Header — Blocksy
Desktop: max-width 1240; brand left; primary nav Технология / Продукты / Кейсы / Инструменты / Статьи; CTA Обсудить ситуацию.
Mobile: Blocksy mobile menu; all primary destinations plus О проекте / Об авторе / Частые вопросы / Контакты reachable.

## Footer — Blocksy
Primary knowledge navigation + О проекте / Об авторе / Частые вопросы / Контакты + verified contact/publication channels. No invented legal/company data.

## Hero
Desktop: inner 1240; Flex row; copy 43%, FINAL Hero 57%; align center; content-driven height.
Mobile: one column: copy → CTA → same Hero binary. No invented mobile Hero. Preserve meaningful crop. No text baked into image.

## Implementation families
Editorial split: 42/58 or 50/50 only where approved design needs it; mobile one column; no forced image.
One core/two fields: relation must remain explicit; two unrelated cards = FAIL.
10-step cycle: all 10 visible/reachable; mobile ordered column/sequence; no carousel-only/horizontal-scroll-only.
Four products: desktop 4 columns only if readable, otherwise 2x2; tablet 2x2; mobile 1; equal semantic level; no funnel.
Forms 17–23: connected set, not seven download cards; no Form 24.
Cases: index max 3→2→1; detail main reading width 680–760; full body survives.
Articles: index 3→2→1 or editorial list; detail 680–760; template works without image.
FAQ: single readable column; Free accordion/toggle only if accessible, otherwise headings+text.
Contact: 42/58 optional desktop, 1 column mobile; primary Telegram CTA, secondary email CTA; no form required.

## Native widgets
Heading, Text Editor, Button, Image, Icon where semantic, Divider where structural, Accordion/Toggle where accessible, Containers/nested Containers.
Avoid HTML widget for normal content. No custom JS for normal layout.

## Responsive/accessibility
DOM follows reading order; no essential hover-only content; Technology Visualization recomposes rather than shrinks unreadably; minimum touch target 44x44; informative image alt; decorative empty alt; logical H1→H2→H3; visible focus.

## Post-design implementation map
Every approved block must be mapped to:
ID | parent container | child containers | direction | width/max-width | gap | padding | alignment | widget | typography token | asset | link/CTA | desktop/tablet/mobile | class/ID | Free compatibility | post-build check.

Claude Design designs within this envelope; it is not asked to emit Elementor JSON.
