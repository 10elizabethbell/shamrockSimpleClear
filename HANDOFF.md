# Shamrock Transportation (Vibe 4: simple / clear) — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockSimpleClear/ · **Repo:** https://github.com/10elizabethbell/shamrockSimpleClear · **Built:** 2026-10-15 from Muse brief (run 2026-10-15, "Vibe 4 — Simple / clear")

## What's built
- **Elevated restyle (Ellie, 2026-10-15: "too relaxed… simple, clear, elevated, elegant, like this is a luxury").** Three hero drafts went on Impeccable's decision page; Ellie picked **A, deep green hero**, then asked for **C's fine-line road** inside it. The comps are kept in `.impeccable/mocks/decision/`. The previous "business card" version is in git history (commit before "Elevated restyle").
- **One short page, single `index.html`, nothing moves.** About 15 KB plus one 14 KB font file (`fonts/marcellus-latin.woff2`, Marcellus, SIL OFL). The only script swaps the closing headline to "Heading home to New Jersey?" from March to August.
- **The look: a private-club card.** Bottle green `#123d2e` for the header, hero and close; near-white paper and stone bands between; ivory text on green; brass only for the short rule under the headline, the Roman numerals and the hover/focus outlines. Headings and the name in Marcellus (an engraved, Trajan-like serif); body in the system sans at 20px; button labels in letterspaced capitals on square-cornered buttons.
- **Header (green):** ivory shamrock + "SHAMROCK TRANSPORTATION" only. **No phone number in the header** (Ellie, 2026-10-15: it repeated the Call button just below). This overrides the older-audience rule "phone in the header"; the number is still on the first screen inside the hero button.
- **Hero (green):** "You fly. / I'll drive your car.", brass rule, "I'm Ed Brannagan, and I personally drive your car between New Jersey and Florida.", ivory **CALL ED / 732-300-3835** button, "My own cell. You'll speak with me directly." **The open road** (Ellie's pick from a second hero round, 2026-10-15; comps in `.impeccable/mocks/hero-road/`): a faint ivory band with a brass dotted centre line. On desktop it runs the full height of the hero on the right, off the top and bottom edges, with New Jersey near the top and Florida near the bottom. On phones it sweeps full-width under the button, off both sides. Drawn once, still.
- **Sections:** How it works (I A call · II Your flight · III Your car, waiting) → The rate ("$1 per mile", "Call for your total") → One driver ("I drive your car myself. It never goes on a truck, so it can travel packed with your things." + the card's other two services) → When a truck is the better choice (answer always showing) → Heading south this winter? (green, ivory Call button) → footer (deep green).
- **Layout:** one column on phones; from 1024px each band puts its heading on the left and content on the right. A phone held sideways gets a tighter hero so Call stays on the first screen.
- **Contact:** every call link is `tel:+17323003835`. No text button (texting unknown).
- **Shareables:** `favicon.svg` and `apple-touch-icon.png` (copied byte for byte from shamrockElegant: the engraved line shamrock in ivory on its deep-green rounded square), `og.png` 1200x630 (green, headline, number, the road).

## Assumptions I made
- **$1 a mile is on the page.** The brief (written before it was confirmed) says to keep rates as a placeholder, but your sibling builds record "$1 a mile (Ed, via Ellie, 2026-10-15)", so I used it. Marked with a `RATE` comment in the HTML.
- **How it works is kept** because this vibe's brief asks for it, even though you cut it from the other Shamrock sites once the price was on the page. Cut it if you want the page shorter.
- **"I drive your car myself" / "not a dispatcher"** follow the brief's "Ed drives it himself; the number is his cell". Confirm he drives every job.
- **"You can pack it full"** follows the brief's differentiator. Not confirmed by Ed; there may be weight or contents limits.
- **"In the spring, I drive it back to New Jersey"** comes from your description of the business (2026-10-13).
- **The honest answer** (truck carrier if the car doesn't run or you don't want miles on it) is general driveaway knowledge in Ed's voice, not something he said.
- **The shamrock is the engraved line drawing Ellie picked for all the Shamrock builds (2026-10-15, from shamrockElegant):** one fine outline of three heart leaves with a vein in each, the stem tucked behind the lower leaf, It is not the card's emblem (the brief says to ask before using a card scan). The files are the exact drawing from `shamrockElegant/brand/` (see its README): the header and og.png inline the fine-line `shamrock-ivory.svg` with only its `color` set to this palette's ivory #f4efe4 (Ellie preferred its look to the heavier small file even at 30px, 2026-10-15); `favicon.svg` and `apple-touch-icon.png` are copied unchanged. Never redraw or reweight it.
- **Marcellus** was my pick for the serif: engraved and classical, and sturdier for older eyes than thin luxury serifs (Premium Concierge already uses Cormorant). Easy to swap: one `@font-face` and `--serif`.
- **Copy got more formal** for the restyle ("I'll advise you honestly", "$1 per mile", "My own cell. You'll speak with me directly."), still first person as Ed.
- **The card tagline ("Life is a Highway... Drive it All Night Long") is left off.** "All night long" could worry a careful 60+ customer about a tired driver. Easy to add to the footer if you or Ed want it.

## Placeholders and gaps
- **No photo of Ed.** The research says his face is the strongest trust signal. There's no visible placeholder (to keep the page clean); `<!-- PHOTO -->` comments mark where a portrait goes (One driver section) and where a photo of Ed with a car could replace the hero drawing.
- **No email and no Facebook**, so the footer email and the "see more of my work" Facebook link are absent by design.
- **Not on the page, on purpose:** insurance, what the $1 a mile includes, hours, years in business, reviews, exact towns.
- **youflyilldrive.com** may be unregistered (brief: RDAP 404 on 2026-10-13, inconclusive recheck). Verify at a registrar before offering it.

## Questions for the owner
1. Does $1 a mile include gas, tolls and your trip back? Is there a minimum (airport runs, short local trips)?
2. Do you take texts? (If yes, a "Text Ed" link can sit under the Call button.)
3. What insurance covers the car and what's inside it while you drive?
4. Do you drive every car yourself?
5. Any packing limits (weight, valuables, nothing blocking the mirrors)?
6. What does "Airport services anywhere in Florida" mean in practice?
7. Can we use the shamrock from your card, and a photo of you (ideally beside a car)?
8. Which months do you head south and north? How much notice do you need?
9. Years doing this, and a couple of customers willing to be quoted?
10. Want youflyilldrive.com registered and pointed here?

## Ideas not built (yours to pick)
- **The unchosen road heroes from the second round:** E, the road on a framed map plate ("THE ROUTE"), and F, an itinerary road with FROM New Jersey / TO Florida. Comps in `.impeccable/mocks/hero-road/`.
- **The other two heroes from the first decision round:** B, an ivory itinerary ("From New Jersey / To Florida" with a dotted brass line), and C, the ivory fine-line road on its own. Comps in `.impeccable/mocks/decision/`.
- **Text Ed link** under the Call button once Ed confirms he texts (pre-written: "Hi Ed, I'd like my car driven from ___ to ___ around ___.").
- **Atkinson Hyperlegible** as the body font (the research's pick for this age group), if you want to step off the system font.
- **A "What's included" line** under $1 a mile once Ed answers question 1.
- **Example trip totals** (e.g. Toms River → Naples) once Ed names his usual towns.

## Not verified
- Real-device tap-to-call on iPhone and Android, and inside Facebook's in-app browser.
- How the page reads to an actual 60-year-old (the research suggests a 5–6 person test).
