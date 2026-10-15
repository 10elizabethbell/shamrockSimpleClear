---
name: Shamrock Transportation
description: Ed's business card made into a calm one-page site. White stock, shamrock green, big plain words, one action (call Ed).
colors:
  shamrock-green: "#0b6b3a"
  shamrock-green-deep: "#08532d"
  leaf: "#2f9a5a"
  focus-blue: "#1f5fbf"
  card-white: "#ffffff"
  mist: "#f2f7f3"
  rule: "#d5e3d9"
  ink: "#16261e"
  ink-soft: "#3c4d44"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.6rem, 1.6rem + 4.6vw, 4.25rem)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  figure:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(3.5rem, 2.4rem + 5vw, 5rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 1.4rem + 2.6vw, 2.75rem)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 700
    lineHeight: 1.25
  lead-large:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.2
rounded:
  focus: "6px"
  link: "8px"
  button: "14px"
spacing:
  gutter: "22px"
  gutter-desktop: "48px"
  step-gap: "28px"
  heading-gap: "24px"
  action-gap: "32px"
  column-gap: "64px"
  band: "72px"
  band-desktop: "104px"
components:
  button-call:
    backgroundColor: "{colors.shamrock-green}"
    textColor: "{colors.card-white}"
    typography: "{typography.title}"
    rounded: "{rounded.button}"
    padding: "12px 20px"
    height: "72px"
    width: "100%"
  button-call-hover:
    backgroundColor: "{colors.shamrock-green-deep}"
    textColor: "{colors.card-white}"
  header-phone:
    textColor: "{colors.shamrock-green}"
    rounded: "{rounded.link}"
    padding: "0 4px"
    height: "48px"
  band-mist:
    backgroundColor: "{colors.mist}"
    padding: "{spacing.band} 0"
  step-number:
    textColor: "{colors.shamrock-green}"
    size: "2.4rem"
  footer:
    textColor: "{colors.ink-soft}"
    typography: "{typography.label}"
    padding: "32px 0 44px"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "The Business Card, Enlarged"**

The page is Ed Brannagan's business card blown up to the size of a phone screen and read slowly: white card stock, a green shamrock, the name, the number, and a few plain sentences. Everything is set large for readers aged 40 to 70 who open the link from Facebook on a phone. The density is low on purpose: one idea per band, generous margins, and one green Call button wherever a decision happens.

The world has two materials: the card itself (shamrock green on white) and the trip it promises, drawn once as a still route line from New Jersey down to Florida with a packed car on it. Nothing else decorates the page. There are no cards, no icons, no photos (yet), no animation, nothing that hides or pops up, and no sticky bar. Calm comes from stillness and size, not from ornament.

Built type uses the platform's own system face (house style), so the page reads like the phone's own text, heavy-weighted (800) for headings so the hierarchy comes from size and weight alone.

**Key Characteristics:**
- White card stock with alternating pale-green (mist) bands; flat, no layered surfaces.
- One accent (shamrock green) for every action and every key number; one separate blue reserved for hover and focus outlines.
- Large system type: 20px body, 18px floor, headings 32 to 68px.
- One action only: call Ed. The number is visible in the header on the first screen and printed on every Call button.
- Nothing moves on its own; nothing is hidden behind a toggle, tab, or popup.

## Colors

A two-green card palette on white, with one off-palette blue that exists only to show where the reader's pointer or keyboard is.

### Primary
- **Shamrock Green** (shamrock-green): the action color. Fills every Call button, colors the header phone number, links, the hero headline's second line, step numerals, the price, and the route line and car. White on it passes AA comfortably.
- **Deep Shamrock** (shamrock-green-deep): the Call button's hover and pressed fill. Never used as a standalone surface.

### Secondary
- **Leaf** (leaf): the brighter shamrock of the drawn emblem, also used for the round bullet dots in short lists. Decorative only; never carries text.

### Tertiary
- **Focus Blue** (focus-blue): the only non-green hue. Used exclusively for hover and keyboard-focus outlines so "where am I" never competes with "what do I tap".

### Neutral
- **Card White** (card-white): page background and text on green buttons.
- **Mist** (mist): pale shamrock band background, alternating with white to separate sections without lines or boxes.
- **Rule** (rule): the hairline under the header and over the footer; also the road bed under the route line.
- **Ink** (ink): body and heading text. A green-black, never pure black.
- **Ink Soft** (ink-soft): secondary text (step descriptions, notes under buttons, list items, footer). About 9:1 on white, so "secondary" never means faint.

### Named Rules
**The One Green Voice Rule.** Shamrock green marks what to tap and what to remember (the number, the price, the step order). It is never a background band, never body text, never decoration.

**The Blue Means Here Rule.** Focus Blue appears only as an outline on hover or keyboard focus. Every interactive element uses it; nothing else on the page is blue.

## Typography

**Display Font:** system UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** the same stack
**Label/Mono Font:** none distinct; prices and phone numbers use tabular figures where they sit in buttons.

**Character:** One family, the phone's own. Hierarchy is built from weight (400 / 700 / 800) and a big size gap, not from a second typeface.

### Hierarchy
- **Display** (800, clamp 2.6rem to 4.25rem, line-height 1.05, tracking -0.02em): the hero headline only. Its second clause sits on its own line in shamrock green.
- **Figure** (800, clamp 3.5rem to 5rem, line-height 1, tracking -0.02em, shamrock green): the price. The largest thing on the page after the headline, because the number is the decision.
- **Headline** (800, clamp 2rem to 2.75rem, line-height 1.15, tracking -0.01em): one per band, balanced wrapping, phrased as plain statements or questions.
- **Title** (700, 1.5rem, line-height 1.25): step titles and the "Call Ed" label inside the button.
- **Lead Large** (400, 1.5rem, line-height 1.5): the hero's one introducing sentence.
- **Body** (400, 1.25rem, line-height 1.6): all running text; leads capped at 34em, pretty wrapping.
- **Label** (400 or 700, 1.125rem, line-height 1.2): the phone number under button labels, notes, footer, brand name. This is the floor.

### Named Rules
**The 18px Floor Rule.** No reading text is set below 1.125rem (18px); body is 1.25rem (20px). The only step down is the brand name at 1rem on screens 400px wide or less, so the full phone number still fits beside it.

**The Weight Does The Work Rule.** One system family; headings are 800, sub-titles 700, everything else 400. Do not add a display face to create hierarchy.

## Layout

One narrow column of large type with wide margins. The content wrapper is 44rem wide with a 22px gutter on phones. Sections are full-bleed bands (72px vertical padding) that alternate white and mist; the hero is tighter (44px top, 56px bottom) so the Call button lands in the first phone viewport. Rhythm inside a band: headline then 24px, steps spaced 28px apart, a Call button 32px below the content it follows, its note 14px under it.

**Desktop (1024px and up).** The wrapper widens to 72rem with 48px gutters and bands grow to 104px padding. The hero becomes two columns (1.1fr text, 0.9fr route drawing, 64px gap, vertically centered). Every other band becomes a heading column and a content column (0.8fr / 1.2fr, 64px gap): the headline sits alone on the left, top-aligned, and everything else, including the Call button, stacks in the right column.

**Phone held sideways (landscape, height 500px or less).** The hero compresses (24px / 32px padding, headline fixed at 2.5rem, lead at 1.25rem) so the Call button stays on the first screen.

**Narrow phones.** At 400px or less the brand name and emblem shrink and the header number steps to 1.125rem; the header wraps rather than truncates.

### Named Rules
**The Call On Screen One Rule.** On any phone, in either orientation, the first viewport shows the name, the full number, the headline, and the green Call button. Spacing gives way before the button does.

**The No Sticky Rule.** The header scrolls away with the page. There is no sticky bar, floating button, or fixed widget; the Call button is repeated in place at each decision point instead.

## Elevation & Depth

Flat. Surfaces are white or mist and sit on one plane; sections are separated by tone, and the header and footer by a single 1px rule hairline. The only raised object on the page is the Call button, which carries a soft green ambient shadow (0 8px 18px -10px, deep green at 55%) so it reads as the one thing to press.

### Named Rules
**The One Raised Thing Rule.** Only the Call button has a shadow. No other element floats, and no container is lifted to look like a card.

## Shapes

Gently rounded where the reader touches, square everywhere else. The Call button uses a 14px radius; the header phone link an 8px radius on its outline; focus outlines round to 6px. Bands, the header, and the footer are full-bleed and square. The only circles are the bullet dots (leaf green) and the route's endpoint markers. There are no bordered boxes.

## Components

### Buttons
The Call button is the only button and the only action. It is big, green, and states its own number.
- **Shape:** gently rounded (14px), full width up to 26rem, at least 72px tall.
- **Primary:** shamrock green fill, white text, two lines centered: a 1.5rem bold verb ("Call Ed", "Call for your total") over the full number at 1.125rem in tabular figures. Always a tel: link to the same number.
- **Hover / Focus:** fill darkens to deep shamrock and a 3px Focus Blue outline appears 3px outside the edge. The fill and shadow ease over 150ms; nothing slides, scales, or animates.
- **Note:** an optional single line of soft-ink 1.125rem text sits 14px below the button ("This is my own cell. You'll talk to me.").
- **Secondary / Ghost:** none. There is no second action.

### Header
- Name and emblem on the left (34px drawn shamrock, bold 1.125rem name), the full phone number on the right in bold 1.25rem shamrock green, both with 48px touch targets in a 68px-tall bar, hairline below. Hovering the number underlines it and draws a 2px Focus Blue outline. Not sticky.

### Numbered Steps
- A plain ordered list: each step is a large 2.4rem shamrock-green numeral (800) in its own column, beside a bold 1.5rem title and a soft-ink sentence. No circles, badges, or connectors.

### Price Figure
- The rate is set in the Figure style in shamrock green directly under the band headline, followed by one plain sentence and a Call button.

### Bands
- Full-width sections alternating white and mist. One headline per band. The band itself is the only container; there are no cards inside it.

### Leaf-Dot List
- Short unordered lists use small round leaf-green dots (0.42em) in place of glyph bullets, text in soft ink.

### Route Drawing (signature)
- One still SVG: a wide rule-colored road bed with a dashed shamrock-green line on top, ringed endpoints, a side-view packed car in shamrock green with its wheels in ink, and bold 21px place labels in ink ("New Jersey", "Florida"). It is drawn, never photographed, never animated, and appears once.

### Footer
- Hairline above, soft-ink 1.125rem text: business name in bold ink, owner and driver line, service area and the number as a tel: link with a 48px tap target.

## Do's and Don'ts

### Do:
- **Do** put the full phone number on every Call button and in the header, as a tel: link with a 48px or larger tap target.
- **Do** use Focus Blue (3px outline, 3px offset) for every hover and keyboard-focus state, and only for that.
- **Do** separate sections with mist and white bands, not borders or boxes.
- **Do** keep body text at 1.25rem and nothing readable below 1.125rem.
- **Do** keep the world to its two materials: the green shamrock on white, and the still drawn route.

### Don't:
- **Don't** animate anything: no scroll reveals, no entrance effects, no moving route, no parallax. The only time-based change is the Call button's 150ms color ease on hover.
- **Don't** hide content behind accordions, tabs, carousels, popups, or "read more".
- **Don't** add a sticky bar, floating call button, or fixed chat widget.
- **Don't** add a second action (form, email, text, social link); call is the only action.
- **Don't** put content in cards, add icons, or introduce a web font; the system stack is house style.
- **Don't** use shamrock green as a band background or for body text, or use any blue except for outlines.
