---
name: Xagni — Slush Inflatable Sticker System
description: Tactile inflatable sticker-book system on pastel paper bands with 1px black outlines, 3D electric blue ribbons, and crushed condensed display typography.
colors:
  carbon: "#000000"
  paper-white: "#ffffff"
  sky-wash: "#dceeff"
  concrete-gray: "#cccccc"
  soft-mist: "#e9e9e9"
  electric-blue: "#4da2ff"
  mint-pop: "#55db9c"
  lavender: "#e9ccff"
  ember: "#fb4903"
  sunburst: "#ffd731"
  voltage-violet: "#5c4ade"
typography:
  display:
    fontFamily: "'Barlow Condensed', 'Antonio', sans-serif"
    fontSize: "clamp(82px, 14vw, 198px)"
    fontWeight: 800
    lineHeight: 0.78
    letterSpacing: "0em"
  headline:
    fontFamily: "'Barlow Condensed', 'Antonio', sans-serif"
    fontSize: "clamp(58px, 9.2vw, 134px)"
    fontWeight: 800
    lineHeight: 0.79
    letterSpacing: "0em"
  title:
    fontFamily: "'Satoshi', ui-sans-serif, system-ui, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  body:
    fontFamily: "'Satoshi', ui-sans-serif, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.39
    letterSpacing: "-0.01em"
    fontFeature: "\"ss01\" on, \"tnum\""
  label:
    fontFamily: "'Satoshi', ui-sans-serif, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "0.032em"
rounded:
  wallet-icon: "16px"
  cards: "20px"
  body: "30px"
  cards-elevated: "40px"
  pills: "1600px"
  buttons: "1600px"
  nav: "1600px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "80px"
components:
  button-primary:
    backgroundColor: "{colors.carbon}"
    textColor: "{colors.paper-white}"
    rounded: "{rounded.cards-elevated}"
    padding: "12px 18px"
  button-primary-hover:
    backgroundColor: "{colors.voltage-violet}"
    textColor: "{colors.paper-white}"
  button-ghost:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.carbon}"
    rounded: "{rounded.buttons}"
    padding: "11px 16px"
  pill-nav-btn:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.carbon}"
    rounded: "{rounded.nav}"
    padding: "12px 14px"
  card-sticker:
    backgroundColor: "{colors.lavender}"
    textColor: "{colors.carbon}"
    rounded: "{rounded.body}"
    padding: "24px"
  card-qr-brief:
    backgroundColor: "{colors.voltage-violet}"
    textColor: "{colors.paper-white}"
    rounded: "{rounded.cards}"
  input-field:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.carbon}"
    rounded: "{rounded.cards}"
    padding: "13px 16px"
---

# Design System: Xagni

## Overview

**Creative North Star: "Inflatable Sticker Universe on Pastel Paper"**

Xagni presents short-form multi-page distribution as a physical collage of hand-cut stickers, oversized crushed display blocks, and grainy 3D inflatable Electric Blue ribbons pinned across alternating full-bleed pastel bands. Rather than mimicking dark neon video editors or soft gray SaaS dashboards, every surface pairs solid flat color fills with crisp 1px Carbon (`#000000`) outlines.

All dimensional weight lives inside the three 3D-rendered matte vinyl ribbons (`assets/ribbon-hero.png`, `assets/ribbon-arc.png`, `assets/ribbon-loop.png`), leaving cards, pills, and stickers completely flat with zero drop shadows and zero gradients.

**Key Characteristics:**
- Full-bleed alternating pastel ground bands (`#dceeff` → `#ffffff` → `#cccccc`) replacing dividers and shadows
- Crushed `800`-weight condensed uppercase display blocks (`0.78` line-height) layered in front of 3D Electric Blue (`#4da2ff`) inflatable ribbons
- Universal `1px solid #000000` hand-cut outlines across every button, pill, sticker, input, and card
- Shared six-color sticker palette (`#4da2ff`, `#55db9c`, `#e9ccff`, `#fb4903`, `#ffd731`, `#5c4ade`) applied across every band

## Colors

The palette pairs three full-bleed pastel/neutral grounds with six vivid sticker colors anchored by pure Carbon (`#000000`) outlines and ink.

### Primary
- **Carbon** (`#000000`): Primary text, universal `1px` hand-cut outlines, top marquee strip, footer band, and primary filled CTA buttons (`#000000` fill with `#ffffff` text).
- **Electric Blue** (`#4da2ff`): Signature 3D inflatable ribbon color and Premium tier card surface wash (always paired with `#000000` ink, never used as a CTA fill or link color).

### Secondary
- **Voltage Violet** (`#5c4ade`): Deep sticker accent for the split QR Brief Card, Clipper CTA box, primary CTA hover state, and hero cap sticker (paired with `#ffffff` ink).
- **Mint Pop** (`#55db9c`): Decorative highlight wash for checkmark stickers, capability cards, pipeline capacity bars, and testimonial cards (never used for semantic success states).
- **Lavender** (`#e9ccff`): Soft sticker wash for the featured Growth tier card, collage cards, and pill hover states.
- **Ember** (`#fb4903`): High-energy sticker badge fill for `"Most Popular"`, `"10 Reels / Wk"` rocket sticker, and validation error alerts (paired with `#000000` ink for >= 4.5:1 contrast).
- **Sunburst** (`#ffd731`): Graphic coin emblem fill and text-selection highlight (never used behind body copy).

### Neutral
- **Paper White** (`#ffffff`): Alternating full-bleed band ground, ghost pill fill, nav pill fill, and interactive card surfaces.
- **Sky Wash** (`#dceeff`): Hero poster ground, alternating full-bleed section band, active pipeline state, and intake band.
- **Concrete Gray** (`#cccccc`): Full-bleed interlude band ground for Pipeline and Clippers/FAQ sections.
- **Soft Mist** (`#e9e9e9`): Recessed panel ground inside the pipeline stage viewer and platform cards.

### Named Rules
**The Zero-Blue-Action Rule.** Electric Blue (`#4da2ff`) is reserved strictly for 3D ribbons and decorative card washes; interactive CTAs use only Carbon (`#000000`) fills or Paper White (`#ffffff`) fills with `1px solid #000000` borders.
**The Shared Sticker Set Rule.** Every section pulls from the six-color sticker palette together rather than isolating a single brand accent.

## Typography

**Display Font:** `Barlow Condensed`, `Antonio`, sans-serif (`800` weight)
**Body & UI Font:** `Satoshi`, ui-sans-serif, system-ui, sans-serif (`500` and `700` weights)

**Character:** Ultra-condensed crushed uppercase blocks act like physical poster lettering stacked behind stickers and in front of 3D ribbons, balanced by crisp geometric UI type (`"ss01" on, "tnum"`) with generous tracking on pill controls.

### Hierarchy
- **Display** (`800`, `clamp(82px, 14vw, 198px)`, `line-height: 0.78`): Hero sculptural headline (`ONE VIDEO. 75 PAGES.`).
- **Headline** (`800`, `clamp(58px, 9.2vw, 134px)`, `line-height: 0.79`): Full-bleed section poster banners.
- **Title** (`700`, `24px`, `line-height: 1.2`, `-0.01em`): Tagline subheads and card titles.
- **Body** (`500`, `15px`, `line-height: 1.39`, `-0.01em`): Card descriptions, FAQs, and workflow steps (`65–75ch` max measure).
- **Label** (`700`, `12px`, `letter-spacing: 0.032em`, uppercase): Pill nav links, marquee text, sticker tags, and form labels.

### Named Rules
**The Crushed Leading Rule.** Display headlines always sit at `0.75–0.80` line-height so stacked words behave as unified sculptural blocks.

## Layout

Full-bleed vertical scroll composed of alternating edge-to-edge color bands (`#dceeff` → `#ffffff` → `#cccccc` → `#dceeff` → `#ffffff` → `#cccccc` → `#dceeff` → `#000000`) with zero horizontal dividers. Content aligns inside a `1440px` max-width container (`32px` desktop horizontal padding, `16px` mobile padding) using asymmetric splits, staggered 2-column collages, and 3-column pricing/proof grids.

## Elevation & Depth

No box shadows and no gradients appear anywhere in the system. Depth and hierarchy are communicated exclusively through full-bleed background color bands, `1px solid #000000` outlines, slight collage rotations (`-8deg` to `+10deg`) on decorative stickers, and z-layered 3D inflatable ribbon plates behind display type.

### Named Rules
**The Flat-Paper Rule.** Zero `box-shadow` and zero CSS gradients on every element; only the 3D ribbon assets carry volumetric shading.

## Shapes

Every surface is soft-cornered and black-outlined (`1px solid #000000`):
- **Nav pills, buttons, tags, and marquee dots:** `1600px` pill radius
- **Primary filled CTAs & elevated containers (`.pipeline-board`, `.price-card`, `.intake-card`):** `40px` radius
- **Body/collage cards (`.collage-card`, `.quote-sticker-card`, `.stage-viewer`):** `30px` radius
- **Standard cards, stickers, QR brief card, and inputs:** `20px` radius
- **Platform/deliverable icon boxes:** `16px` radius

## Components

### Buttons
- **Primary Filled CTA:** `40px` radius, `#000000` background, `#ffffff` uppercase `Satoshi 700` `13px` (`0.032em` tracking), `12px 18px` padding, `1px solid #000000` border; shifts to `#5c4ade` on hover.
- **Ghost Pill Button:** `1600px` radius, `#ffffff` background, `#000000` ink, `1px solid #000000` border, `11px 16px` padding; shifts to `#e9ccff` Lavender on hover.

### Navigation
- **Top Pill Bar:** Circular `'X'` logo badge + `Xagni` pill left, inline `1600px` pill links (`4px` gap) center, `#000000` filled CTA + circular `+` full-screen menu trigger right. Collapses cleanly below `1120px` into logo + `+` drawer trigger.

### QR Brief Card
- **Split Sticker Card:** `20px` radius, `1px solid #000000` border, split between a `#ffffff` geometric QR square panel (`10px` padding) and a `#5c4ade` Voltage Violet action panel with `#ffffff` copy and CTA pill.

### Cards & Stickers
- **Sticker Badges & Collage Cards:** `20px–40px` radius, `1px solid #000000` border, solid fills from the six-color palette, slight rotation on hero/quote stickers (`-8deg` to `+10deg`), flattening to `0deg` on hover and mobile (`<= 720px`).

### Inputs & Accordions
- **Form Fields & FAQ Cards:** `20px` radius, `#ffffff` fill, `1px solid #000000` border, `2px` Carbon focus ring (`offset: 2px`), Ember (`#fb4903`) / Lavender (`#e9ccff`) validation states.

## Do's and Don'ts

### Do:
- **Do** pair `Barlow Condensed` `800` display text at `0.78` line-height with a 3D Electric Blue (`#4da2ff`) ribbon behind it in every major section.
- **Do** keep `1px solid #000000` borders on every button, pill, sticker, input, and card.
- **Do** alternate full-bleed band backgrounds across `#dceeff`, `#ffffff`, and `#cccccc` without horizontal rules or shadows.
- **Do** keep all `>= 4.5:1` contrast pairings intact (`#000000` ink on `#fb4903`, `#4da2ff`, `#55db9c`, `#e9ccff`; `#ffffff` ink on `#5c4ade` and `#000000`).

### Don't:
- **Don't** add `box-shadow` or CSS gradients to any element.
- **Don't** use Electric Blue (`#4da2ff`) as a button or link action color.
- **Don't** use Sunburst (`#ffd731`) behind readable text or Mint Pop (`#55db9c`) as a semantic success state.
- **Don't** use border-radius below `16px` on cards/icons or below `1600px` on pill buttons/tags.
