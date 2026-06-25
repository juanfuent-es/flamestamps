---
version: "alpha"
name: Flame Stamps
description: "Design system for the Flame Stamps seasonal mobile-first concept."
colors:
  primary: "#1C0F0A"
  secondary: "#652F23"
  tertiary: "#B53015"
  neutral: "#FFFFF6"
  on-primary: "#FFFFF6"
  on-secondary: "#FFFBC3"
  on-tertiary: "#FFFFF6"
  night: "#1C0F0A"
  burgundy: "#652F23"
  brown: "#563621"
  flame-red: "#B53015"
  flame-orange: "#EC4321"
  soft-yellow: "#FFFBC3"
  cream: "#FFFFF6"
  sage: "#C3C8A7"
  olive: "#6E795D"
  ink: "#2A1812"
  black-logo: "#000000"
typography:
  display-hero:
    fontFamily: "Awesome Serif"
    fontSize: 4.75rem
    fontWeight: 540
    lineHeight: "1.05"
    letterSpacing: 0
    fontVariation: "'wght' 540, 'hght' 1000"
  display-emphasis:
    fontFamily: "Awesome Serif"
    fontSize: 4.75rem
    fontWeight: 380
    lineHeight: "1.05"
    letterSpacing: 0
    fontVariation: "'wght' 380, 'hght' 1000"
  heading-section:
    fontFamily: "Awesome Serif"
    fontSize: 2.375rem
    fontWeight: 320
    lineHeight: "1.22"
    letterSpacing: 0
    fontVariation: "'wght' 320, 'hght' 1000"
  body-lg:
    fontFamily: "Awesome Serif"
    fontSize: 1.125rem
    fontWeight: 120
    lineHeight: "1.75"
    letterSpacing: 0
    fontVariation: "'wght' 120, 'hght' 1000"
  body-md:
    fontFamily: "Awesome Serif"
    fontSize: 1rem
    fontWeight: 120
    lineHeight: "1.75"
    letterSpacing: 0
    fontVariation: "'wght' 120, 'hght' 1000"
  label-italic:
    fontFamily: "Amiri"
    fontSize: 0.9375rem
    fontWeight: 400
    lineHeight: "1.55"
    letterSpacing: 0.02em
    fontFeature: "ital"
  meta:
    fontFamily: "Awesome Serif"
    fontSize: 0.8125rem
    fontWeight: 120
    lineHeight: "1.45"
    letterSpacing: 0.02em
    fontVariation: "'wght' 120, 'hght' 1000"
  button-label:
    fontFamily: "Awesome Serif"
    fontSize: 1.125rem
    fontWeight: 480
    lineHeight: "1.2"
    letterSpacing: 0
    fontVariation: "'wght' 480, 'hght' 700"
rounded:
  xs: 4px
  sm: 6px
  md: 10px
  lg: 14px
  xl: 34px
  pill: 40px
  circle: 999px
spacing:
  2xs: 4px
  xs: 6px
  sm: 8px
  md: 14px
  lg: 18px
  xl: 22px
  2xl: 28px
  3xl: 46px
  4xl: 64px
  section-sm: 90px
  section-md: 110px
  section-lg: 130px
components:
  page-shell:
    backgroundColor: "{colors.night}"
    textColor: "{colors.neutral}"
    typography: "{typography.body-lg}"
  hero-section:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.display-hero}"
    padding: "{spacing.section-sm}"
  section-dark:
    backgroundColor: "{colors.night}"
    textColor: "{colors.cream}"
    typography: "{typography.body-lg}"
    padding: "{spacing.section-lg}"
  section-collective:
    backgroundColor: "{colors.sage}"
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
    padding: "{spacing.section-lg}"
  eyebrow:
    backgroundColor: "{colors.night}"
    textColor: "{colors.soft-yellow}"
    typography: "{typography.label-italic}"
  eyebrow-light:
    backgroundColor: "{colors.sage}"
    textColor: "{colors.burgundy}"
    typography: "{typography.label-italic}"
  button-primary:
    backgroundColor: "{colors.flame-red}"
    textColor: "{colors.cream}"
    typography: "{typography.button-label}"
    rounded: "{rounded.pill}"
    padding: 16px
  button-primary-hover:
    backgroundColor: "{colors.flame-orange}"
    rounded: "{rounded.pill}"
    padding: 16px
  phone-frame:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.cream}"
    rounded: "{rounded.xl}"
    width: 236px
    height: 486px
  phone-splash:
    backgroundColor: "{colors.burgundy}"
    textColor: "{colors.soft-yellow}"
    typography: "{typography.label-italic}"
    padding: 30px
  phone-viewfinder:
    backgroundColor: "{colors.brown}"
    textColor: "{colors.cream}"
    padding: 18px
  viewfinder-pill:
    backgroundColor: "{colors.brown}"
    textColor: "{colors.soft-yellow}"
    typography: "{typography.label-italic}"
    rounded: "{rounded.pill}"
    padding: 5px
  stamp-card:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.flame-red}"
    typography: "{typography.meta}"
    rounded: "{rounded.sm}"
    padding: 26px
  album-tile:
    backgroundColor: "{colors.brown}"
    textColor: "{colors.soft-yellow}"
    rounded: "{rounded.md}"
    padding: 9px
  share-template:
    backgroundColor: "{colors.soft-yellow}"
    textColor: "{colors.burgundy}"
    typography: "{typography.meta}"
    rounded: "{rounded.sm}"
    padding: 24px
  logo-horizontal:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.flame-red}"
    width: 2344px
    height: 1301px
  logo-vertical:
    backgroundColor: "{colors.night}"
    textColor: "{colors.soft-yellow}"
    width: 928px
    height: 1180px
  logo-mark:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.black-logo}"
    width: 1187px
    height: 1244px
  petal-flame-red:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.flame-red}"
    width: 495px
    height: 930px
  petal-soft-yellow:
    backgroundColor: "{colors.night}"
    textColor: "{colors.soft-yellow}"
    width: 495px
    height: 930px
  petal-burgundy:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.burgundy}"
    width: 560px
    height: 734px
  petal-light-green:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.sage}"
    width: 560px
    height: 734px
  accent-circle:
    backgroundColor: "{colors.olive}"
    textColor: "{colors.cream}"
    rounded: "{rounded.circle}"
    width: 424px
    height: 425px
---

## Overview

Flame Stamps is an editorial, mobile-first seasonal system. It should feel like
a ritual object rather than a utility: quiet, warm, botanical, cinematic, and
slightly handmade. The current `index.html` establishes the core behavior:
full-bleed sections, serif-led storytelling, floating cutout petals, a phone
prototype, low-opacity grain, and a collective tree made from repeated bloom
marks.

The design rules follow the `DESIGN.md` model from `@google/design.md`: exact
tokens live in YAML, while the markdown explains how to apply them. The broader
Google Design influence is to keep the system expressive but structured:
accessible color choices, reusable components, motion that respects reduced
motion preferences, and typography as a functional part of the interface.

Source assets in `img/` extend the page into a fuller brand system:
horizontal, vertical, and mark-only logo lockups; Flame Red, Light Yellow, and
Black logo variants; color PDFs for primary, secondary, accent, and
combinations; primary typography folders for Awesome Serif and Doran Variable;
secondary and tertiary folders for Lyon Arabic Text and Suisse Int'l; cutout
photography; and vector petals/circle assets in Flame Red, Soft Yellow,
Burgundy, and Light Green.

## Colors

The palette is dark, botanical, and heat-driven. Use Night as the default page
field, Cream as the main readable foreground, Burgundy and Brown for depth, and
Flame Red/Flame Orange for active energy.

- **Night (#1C0F0A):** Primary surface. Use for page background, hero depth,
  footer, and immersive dark sections.
- **Cream (#FFFFF6):** Primary text on dark surfaces. It should replace pure
  white to preserve the warm seasonal tone.
- **Soft Yellow (#FFFBC3):** Secondary text, logo variant, labels, metadata,
  highlights, and share surfaces.
- **Burgundy (#652F23):** Deep brand field for splash screens, gradients, and
  premium contrast against Soft Yellow.
- **Brown (#563621):** Organic middle depth for viewfinders, album tiles, and
  trunk-like visual support.
- **Ink (#2A1812):** Near-dark UI surface used inside phone frames and dense
  components.
- **Flame Red (#B53015):** Default interaction color for text-bearing controls
  because it keeps Cream text above WCAG AA contrast.
- **Flame Orange (#EC4321):** Expressive heat accent. Use for large CTAs,
  hover glow, petals, selection states, and non-text visual energy. Avoid it as
  a normal-size text button background with Cream text.
- **Sage (#C3C8A7):** Collective/public-space section background. Pair with
  Ink or Burgundy, never with Cream body text.
- **Olive (#6E795D):** Secondary green accent from the brand set. Use sparingly
  for supporting marks, quiet separators, or muted botanical states.
- **Black (#000000):** Reserved for logo applications only, based on the
  Black logo variants in `img/01_Logo`.

Color combinations should stay few and deliberate: Night/Cream,
Night/Soft Yellow, Burgundy/Soft Yellow, Cream/Flame Red, Sage/Ink, and
Soft Yellow/Burgundy. Do not introduce blue, purple, synthetic gradients, or
neutral gray UI chrome.

## Typography

Awesome Serif is the primary voice in the current page. It should handle
display, body, labels, and buttons through variable weight and height rather
than by switching families. The page uses a light default body setting
(`'wght' 120, 'hght' 1000`), tall display settings, and heavier button labels.

Use Amiri only for short italic labels in the current implementation:
"Dubai - Flame Tree Season", captions, and poetic microcopy. Keep it small,
warm, and secondary.

The `img/03_Typography` folder defines broader brand intent:

- **Awesome Serif:** Primary Latin editorial voice and current page font.
- **Doran Variable:** Primary Arabic-capable variable webfont asset. Use for
  Arabic or right-to-left seasonal extensions, with OpenType features such as
  `kern`, `liga`, and `dlig` enabled.
- **Lyon Arabic Text:** Secondary Arabic text direction from the brand folder.
  Use when a more text-forward Arabic composition is needed.
- **Suisse Int'l:** Tertiary sans-serif option. Use only for utilitarian UI,
  legal, technical labels, or app-store style metadata where a serif would
  reduce clarity.

Typography should stay editorial. Avoid uppercase UI shouting, condensed
marketing sans-serif, negative letter spacing, and decorative font mixing. Do
not scale type directly with viewport width outside existing `clamp()` ranges.

## Layout

The system is mobile-first and sectional. Full-width sections carry the mood;
inner content stays constrained with `.wrap` widths of 560px, 680px, 920px, or
1180px depending on density.

Core structure:

- Hero: minimum full viewport height, centered content, floating petals, 90px
  top padding, and enough lower padding to reveal motion/scroll context.
- Intro and CTA: dark editorial blocks with 110px to 130px vertical rhythm.
- Screens: a flexible row of five phone cards with 46px gaps and centered
  labels.
- Collective: Sage field with constrained editorial copy and a generated
  bloom canopy.
- Footer: compact, dark, and low-contrast.

Spacing should be generous at the section level and tight inside phone UI.
Use 28px horizontal page padding, 18px to 30px component padding, 46px card
gaps, and 64px section header separation. Preserve `overflow-x: hidden` because
the concept uses off-canvas decorative petals.

## Elevation & Depth

Depth is atmospheric, not card-heavy. The system uses gradients, shadows,
opacity, and grain rather than stacked panels.

- Use radial or directional gradients only when they simulate seasonal heat or
  camera/viewfinder depth.
- Phone frames may use strong soft shadows such as `0 30px 60px -20px` on
  black.
- CTAs may glow with Flame Orange shadow, especially on hover.
- Grain should remain low opacity around `0.045` with `mix-blend-mode:
  overlay`.
- Decorative visual assets may use drop shadows, but content containers should
  not become floating cards.

Motion should be restrained: scroll reveal, slight vertical translation, and
hero parallax. Always preserve a reduced-motion path equivalent to the current
`prefers-reduced-motion` rule.

## Shapes

Shape language comes from flame tree petals and the logo mark. Use organic
botanical silhouettes for visual identity, then keep UI primitives simple.

- Logo lockups come in horizontal, vertical, and mark-only variants. Use
  horizontal for footer and wide brand moments, vertical for splash/hero, and
  mark-only for app icons or compact stamps.
- Petal vectors appear as Petal 1 and Petal 2 in Flame Red, Soft Yellow,
  Burgundy, and Light Green. Use them for masks, album tiles, viewfinder shapes,
  and collective-tree blooms.
- Cutout images are large photographic assets. Use them as hero floaters,
  masked stamp captures, or immersive seasonal texture, not as generic stock
  imagery.
- Phone frames use 34px radius. Image clips use 6px. Album tiles use 10px.
  Pills use 40px or full circular rounding.
- Avoid generic rounded cards for page sections. The brand shape should come
  from petals, marks, stamps, and bloom scatter.

## Components

The design system is centered on a few reusable components:

- **Hero:** Full-screen seasonal field with vertical logo, eyebrow, large
  serif title, italic emphasis, floating cutouts, and a minimal scroll line.
- **Editorial Section:** Constrained prose block on Night with Cream text and
  optional low-opacity watermark mark.
- **Phone Frame:** Fixed-ratio prototype frame with notch, rounded shell,
  dark inner surface, and app-state screens.
- **Splash Screen:** Burgundy field with Flame Red or Soft Yellow mark,
  Amiri label, and short italic guidance.
- **Viewfinder Screen:** Brown-to-Ink depth, centered petal mask, Soft Yellow
  pill, dots, and circular shutter.
- **Stamp Screen:** Cream card with clipped photo, Flame Red caption, and Ink
  metadata.
- **Album Grid:** Two-column grid, Brown tiles, contained petal/capture assets,
  and tight 9px gaps.
- **Share Template:** Soft Yellow field with Flame Red logo, clipped capture,
  Burgundy metadata, and compact publisher mark.
- **CTA Button:** Text-bearing default uses Flame Red plus Cream. Flame Orange
  may be used for hover, glow, or large-display treatment.
- **Collective Tree:** Sage field, Brown trunk/mark, Flame Orange and Soft
  Yellow blooms, faded rejected submissions in grayscale/low opacity.

Component implementation should prefer real assets from `img/` or existing SVG
paths over new illustrations. If a new screen is added, it should reuse one of
the existing petal shapes before inventing a new mark.

## Do's and Don'ts

Do:

- Use the exact color tokens above before creating any new color.
- Keep Night/Cream as the primary reading mode.
- Use Flame Red for accessible text controls and Flame Orange for heat,
  emphasis, hover, selection, and large-display moments.
- Keep typography serif-led and variable, with Amiri reserved for short poetic
  labels.
- Respect `prefers-reduced-motion`.
- Use `img/01_Logo` variants according to background contrast: Flame Red on
  light fields, Light Yellow on dark/burgundy fields, Black for neutral brand
  applications.
- Use `img/04_Visual Elements` petals and cutouts as the recognizable visual
  system.
- Keep page sections full-width and unframed.

Don't:

- Do not introduce generic SaaS cards, blue/purple gradients, glassmorphism, or
  neutral gray component chrome.
- Do not use Flame Orange with Cream for small normal-weight text.
- Do not turn every block into a rounded rectangle.
- Do not mix in new icon systems unless the UI requires a functional control.
- Do not replace the brand petals with abstract blobs or unrelated flowers.
- Do not use Black as a general UI background; reserve it for logo assets and
  formal brand applications.
- Do not remove the warm grain unless the surface becomes visually noisy.
