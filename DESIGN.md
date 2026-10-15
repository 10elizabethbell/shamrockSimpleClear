---
name: Shamrock Transportation
description: A private-club card for a personal driver. Bottle green, ivory, a touch of brass, engraved serif type; simple and clear first, luxurious through restraint.
colors:
  bottle-green: "#123d2e"
  bottle-green-deep: "#0c2b20"
  brass: "#a8834a"
  brass-ink: "#8a6a36"
  brass-light: "#c9a76b"
  ivory: "#f4efe4"
  ivory-muted: "#cfc8b6"
  paper: "#fbfaf7"
  stone: "#f1eee7"
  ink: "#1a211d"
  ink-soft: "#4a524d"
typography:
  display:
    fontFamily: "Marcellus, \"Trajan Pro\", Georgia, serif"
    fontSize: "clamp(2.75rem, 1.9rem + 4vw, 4.5rem)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  price:
    fontFamily: "Marcellus, \"Trajan Pro\", Georgia, serif"
    fontSize: "clamp(3.25rem, 2.4rem + 4vw, 4.75rem)"
    fontWeight: 400
    lineHeight: 1
  headline:
    fontFamily: "Marcellus, \"Trajan Pro\", Georgia, serif"
    fontSize: "clamp(2rem, 1.5rem + 2.2vw, 2.75rem)"
    fontWeight: 400
    lineHeight: 1.15
  title:
    fontFamily: "Marcellus, \"Trajan Pro\", Georgia, serif"
    fontSize: "1.5rem"
    fontWeight: 400
    lineHeight: 1.3
  numeral:
    fontFamily: "Marcellus, \"Trajan Pro\", Georgia, serif"
    fontSize: "1.75rem"
    fontWeight: 400
    lineHeight: 1.3
  wordmark:
    fontFamily: "Marcellus, \"Trajan Pro\", Georgia, serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: "0.1em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0.16em"
  phone:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "0.04em"
    fontFeature: "\"tnum\""
rounded:
  square: "2px"
spacing:
  gutter: "24px"
  gutter-desktop: "56px"
  xs: "4px"
  sm: "12px"
  md: "16px"
  lg: "28px"
  xl: "36px"
  section: "80px"
  section-desktop: "112px"
components:
  button-call:
    backgroundColor: "{colors.bottle-green}"
    textColor: "{colors.ivory}"
    typography: "{typography.label}"
    rounded: "{rounded.square}"
    padding: "14px 20px"
    height: "76px"
    width: "100%, max 24rem"
  button-call-hover:
    backgroundColor: "{colors.bottle-green-deep}"
    textColor: "{colors.ivory}"
  button-call-on-green:
    backgroundColor: "{colors.ivory}"
    textColor: "{colors.bottle-green}"
    typography: "{typography.label}"
    rounded: "{rounded.square}"
    padding: "14px 20px"
    height: "76px"
  button-call-on-green-hover:
    backgroundColor: "#ffffff"
    textColor: "{colors.bottle-green}"
  header-bar:
    backgroundColor: "{colors.bottle-green}"
    textColor: "{colors.ivory}"
    height: "76px"
  band:
    backgroundColor: "{colors.stone}"
    textColor: "{colors.ink}"
    padding: "80px 0"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "The Private-Club Card"**

The page reads like a heavy engraved card handed across a club table: bottle green stock at the top and bottom, warm paper and stone between, an engraved Roman serif for the name and the headings, and a hairline of brass. It is luxurious only through restraint. There are no effects to carry the feeling; the materials, the spacing and the type do it all.

Simple and clear comes first. The reader is 40 to 70, on a phone, often inside Facebook's browser, deciding whether to trust one man with their car. So body type is large (20px), contrast is high, every section says one thing, and the only action anywhere is a square-cornered button that calls Ed and carries his number on its face. Nothing moves, nothing is hidden, nothing sticks to the screen.

The structure is one column of full-width bands that becomes a heading-left / content-right ledger at 1024px. The single illustrative element is a still fine-line drawing of the road from New Jersey to Florida, in ivory and brass on the green.

**Key Characteristics:**
- Bottle green grounds the header, hero, closing band and footer; paper and stone alternate between.
- Marcellus (engraved Roman capitals) for headings, the name and numerals; system sans for everything read at length.
- Brass is a hairline material: the short rule, Roman numerals, list dashes, the road, and the single focus/hover outline.
- Flat, square-cornered (2px) buttons with letterspaced capitals and the phone number set below.
- Zero motion beyond a 0.15s background color change; nothing hidden, no sticky elements.

## Colors

A three-material palette: bottle green as the ground, ivory and warm paper as the stock, brass as the engraving.

### Primary
- **Bottle Green** (#123d2e): the ground of the header bar, hero, closing band, and the fill of the Call button on light bands. Also the color of the price on paper. It carries the brand's green without the old shamrock-bright tone.
- **Deep Bottle Green** (#0c2b20): footer ground and the hover/active state of the green Call button. Only ever a darker step of the primary, never a separate surface idea.

### Secondary
- **Brass** (#a8834a): the outline color for every hover and focus state, the short rule on light bands, and the dash markers in plain lists. Never used for text or fills larger than a hairline.
- **Brass Ink** (#8a6a36): a darkened brass for text-weight use on light grounds, specifically the Roman step numerals (28px serif, large-text contrast on stone).
- **Light Brass** (#c9a76b): the brass that sits on green: the hero rule, the dashed road line, the Florida end-point, the stem of the shamrock mark.

### Neutral
- **Ivory** (#f4efe4): text and headings on green, the fill of the Call button on green, the shamrock leaves, the road's base stroke.
- **Muted Ivory** (#cfc8b6): secondary text on green (the hero's "My own cell" note, footer lines).
- **Paper** (#fbfaf7): the page ground; a warm near-white, never pure white.
- **Stone** (#f1eee7): alternating bands ("How it works", "One driver"), the only tonal separation on light sections.
- **Ink** (#1a211d): headings and primary text on paper and stone; a green-black, not neutral black.
- **Soft Ink** (#4a524d): body paragraphs, step descriptions, list items and notes on light grounds.

### Named Rules
**The Brass Is Engraving Rule.** Brass appears only as hairlines, numerals and outlines: the 56px x 2px rule, the I-II-III numerals, 1px list dashes, the road drawing, and the 2px focus/hover outline. It never fills a button, a band, or a block of text.

**The One Outline Rule.** Brass (#a8834a) is the single hover and focus outline color across the whole page: 2px solid, 4px offset, on every link and button. No second focus color, no glow, no ring of another hue.

**The Green Ground Rule.** Green is a ground, not an accent. It covers whole bands edge to edge (header, hero, close, footer) or fills the Call button; it is not sprinkled on icons, borders or inline words.

## Typography

**Display Font:** Marcellus (with "Trajan Pro", Georgia, serif), self-hosted from fonts/marcellus-latin.woff2, single weight 400
**Body Font:** System sans stack (-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif)

**Character:** Marcellus is an inscriptional, flared Roman: it gives the name and headings the look of an engraved card at a single regular weight. The system sans does all the reading and all the numbers, so long text and the phone number stay plain, familiar and legible for an older reader.

### Hierarchy
- **Display** (Marcellus 400, clamp(2.75rem, 1.9rem + 4vw, 4.5rem), 1.08): the hero headline only, each sentence on its own balanced line.
- **Price** (Marcellus 400, clamp(3.25rem, 2.4rem + 4vw, 4.75rem), 1): the rate line in bottle green; the figure itself ("$1") is set in the sans at 500 with -0.02em tracking inside the serif line.
- **Headline** (Marcellus 400, clamp(2rem, 1.5rem + 2.2vw, 2.75rem), 1.15): section headings, balanced wrap.
- **Title** (Marcellus 400, 1.5rem, 1.3): step titles in "How it works".
- **Numeral** (Marcellus 400, 1.75rem, 1.3, brass ink): Roman step numerals I, II, III in a 3.25rem gutter column.
- **Wordmark** (Marcellus 400, 1.0625rem, 0.1em tracking, uppercase): "Shamrock Transportation" in the header and footer. Tightens to 0.9375rem/0.08em under 400px and 0.875rem/0.04em under 380px; the text hides below 340px, leaving the mark.
- **Lead** (sans 400, 1.375rem, 1.55, max 30em): the hero's introductory sentence.
- **Body** (sans 400, 1.25rem, 1.65, max 32em, pretty wrap): all paragraphs. Never below 18px anywhere on the page.
- **Label** (sans 600, 1.125rem, 1.2, 0.16em tracking, uppercase): the action word on the Call button ("CALL ED", "CALL FOR YOUR TOTAL").
- **Phone** (sans 400, 1.25rem, 0.04em, tabular figures): the number under the label inside the Call button; the header number uses sans 600 at 1.125rem with the same tabular figures.

### Named Rules
**The Figures Are Sans Rule.** Every number a reader must read or dial (the phone number, the price figure) is set in the system sans with tabular or tightened figures, even when it sits inside a serif line. Marcellus is reserved for words and Roman numerals.

**The Single Weight Serif Rule.** Marcellus is used at its one weight (400). Hierarchy comes from size, tracking and case, never from faux bold.

## Layout

One centered column, max 44rem with 24px gutters on phones, built from full-width bands. Bands alternate paper and stone between a green hero and a green close; section padding is 80px vertical on phones and 112px from 1024px.

From 1024px the column widens to 72rem with 56px gutters and every non-hero section becomes a two-column ledger: heading left (0.8fr), content right (1.2fr), 72px column gap, heading spanning the content rows. The hero becomes a 1.3fr / 0.7fr grid with the road drawing to the right of the text (56px gap); on phones the road sits below the call button.

Vertical rhythm inside sections: 28px under headings and around the brass rule, 16px between paragraphs and under the button for its note, 36px above each Call button, 32px between steps, 24px above plain lists. Touch targets are at least 48px tall (header links, footer number); the Call button is 76px tall and up to 24rem wide. A landscape-phone override (max-height 500px) shrinks the hero headline and padding so the call button stays in the first view.

There is no sticky bar, no fixed element and no collapsed content: everything is in normal flow and visible on load.

## Elevation & Depth

Fully flat. There are no box-shadows anywhere in the system. Depth is conveyed only by tonal grounds: green bands against paper, stone bands against paper, and one 1px ivory hairline at 14% opacity under the green header. Hover and focus never lift anything; they recolor and outline.

### Named Rules
**The Flat Card Rule.** Nothing casts a shadow, nothing lifts, nothing translates. A card is printed, not stacked.

## Shapes

Square-cornered throughout. The only radius in the system is 2px on the Call button, just enough to soften the cut edge of a card. There are no cards, chips, pills, or framed containers: sections are edge-to-edge bands, and structure comes from hairlines (the 56px x 2px brass rule, 1px brass list dashes) rather than borders or boxes. The one curved form is the road drawing: a single swept path with round caps and two circular end-points.

## Components

### Call Button
The one action on the page; a printed plate that dials Ed.
- **Shape:** square, nearly sharp corners (2px), full width up to 24rem, minimum 76px tall, 14px 20px padding.
- **Content:** two stacked lines, centered, 4px apart: the action in letterspaced sans capitals (label style), then the phone number in tabular sans (phone style). The number is always printed on the button.
- **On light bands:** bottle green fill, ivory text.
- **On green bands (hero, close):** ivory fill, bottle green text.
- **Hover / Focus:** fill darkens to deep bottle green (or lightens to white on green bands) with a 0.15s background-color transition, plus the brass 2px outline at 4px offset. No shadow, no movement.
- **Note:** an optional 1.125rem soft-ink (or muted-ivory on green) line sits 16px below, e.g. "My own cell. You'll speak with me directly."

### Header Bar
- **Style:** bottle green, 76px minimum height, ivory text, 1px translucent ivory hairline below. Not sticky.
- **Content:** the drawn shamrock mark (30px, ivory leaves, light-brass stem) with the wordmark on the left; the full phone number on the right in sans 600, tabular, 0.04em. Both are 48px-tall tap targets.
- **Hover:** the number gains a brass underline (0.25em offset); focus uses the brass outline.

### Roman Numeral Steps
A three-row ordered list: a 3.25rem left column holding the Roman numeral in brass-ink Marcellus, spanning the title (Marcellus 1.5rem) and the soft-ink description. 32px between steps. No icons, no circles, no connecting lines.

### Price Line
The rate as a single large serif line in bottle green with the figure swapped into sans 500 ("$1" in sans, "per mile" in Marcellus). Followed by a plain body line and the Call button.

### Brass-Dash List
Unbulleted list in soft ink where each item is marked by a 0.75em x 1px brass hairline, 1.5em indent. Used for short service lines.

### Road Drawing (signature)
One still SVG line drawing on the green hero: a wide ivory road at 28% opacity under a dashed light-brass centerline (2.2px, 3/7 dash), an outlined ivory start point and a solid light-brass end point, with "New Jersey" and "Florida" set in Marcellus 26px ivory. Max 30rem on phones; fills its grid column on desktop. It does not animate.

### Footer
Deep bottle green, muted-ivory text at 1.125rem, the wordmark in ivory Marcellus caps, the phone number as a 48px-tall ivory link.

## Do's and Don'ts

### Do:
- **Do** keep body text at 1.25rem (20px) sans with 1.65 line height; nothing a reader must read drops below 18px.
- **Do** print the phone number on every Call button, under the letterspaced label, in tabular sans figures.
- **Do** use brass (#a8834a) as the one hover and focus outline color: 2px solid, 4px offset.
- **Do** keep buttons flat and square-cornered (2px), bottle green on light bands and ivory on green bands.
- **Do** set headings, the name and Roman numerals in Marcellus 400, and every dialable or priced figure in the sans.
- **Do** alternate paper and stone bands between the green hero and the green close, and switch to heading-left / content-right at 1024px.
- **Do** keep every touch target at least 48px tall.

### Don't:
- **Don't** add motion: no entrance animations, scroll effects, parallax, or animated drawings. The only transition is the 0.15s button color change. The audience is 40 to 70 and the page must sit still.
- **Don't** hide content: no accordions, tabs, carousels, popups or "read more".
- **Don't** add a second action. Call is the only action; no forms, email, chat or text buttons.
- **Don't** add a sticky or fixed bar of any kind; the header scrolls away with the page.
- **Don't** put shadows on buttons or anything else, and don't lift or translate on hover.
- **Don't** introduce rounded pills, cards, framed boxes, icon sets or photos-as-decoration; structure comes from bands and brass hairlines.
- **Don't** use brass as a fill or for body text, and don't introduce a second outline or focus color.
- **Don't** bold Marcellus or set phone numbers and prices in the serif.
