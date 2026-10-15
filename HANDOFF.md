# Shamrock Transportation (Vibe 4: simple / clear) — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockSimpleClear/ · **Repo:** https://github.com/10elizabethbell/shamrockSimpleClear · **Built:** 2026-10-15 from Muse brief (run 2026-10-15, "Vibe 4 — Simple / clear")

## What's built
- **One short page, single `index.html`, no images, nothing moves.** About 15 KB. The only script swaps the closing headline to "Heading home this spring?" from March to August.
- **The look: Ed's business card made into a page.** White ground, green-black text, shamrock green for the Call buttons and key words, pale-green bands every other section. No cards, no icons, no motion. Big type: body 20px, the hero line 24px, section headings 32–44px in sentence case, buttons 72px tall.
- **Header:** drawn shamrock + "Shamrock Transportation" on the left, the full number 732-300-3835 on the right (tap to call).
- **Hero:** "You fly. / I'll drive your car." (from the card's domain, youflyilldrive.com), "I'm Ed Brannagan. I drive your car between New Jersey and Florida, so you don't have to.", one green **Call Ed / 732-300-3835** button, and "This is my own cell. You'll talk to me." Beside it (below it on phones) a still drawing: a dashed road from a New Jersey pin to a Florida pin with a packed green car on it.
- **Sections, in the brief's order:** How it works (Call me → Fly → Your car is waiting) → What it costs ("$1 a mile", "Call me with your route and I'll tell you the total.", Call button) → One driver: me (Ed drives it himself, his own cell, "you can pack the car full", plus the card's two other services) → An honest answer (when a truck carrier is the better choice, always visible) → Heading south this winter? (Call button) → footer (name, Ed, NJ ↔ Florida, number).
- **Contact:** every call link is `tel:+17323003835`. No text button, because the brief says texting is unknown.
- **Shareables:** `favicon.svg` and `apple-touch-icon.png` (white shamrock on green), `og.png` 1200x630 (name, headline, number, route drawing).

## Assumptions I made
- **$1 a mile is on the page.** The brief (written before it was confirmed) says to keep rates as a placeholder, but your sibling builds record "$1 a mile (Ed, via Ellie, 2026-10-15)", so I used it. Marked with a `RATE` comment in the HTML.
- **How it works is kept** because this vibe's brief asks for it, even though you cut it from the other Shamrock sites once the price was on the page. Cut it if you want the page shorter.
- **"I drive your car myself" / "not a dispatcher"** follow the brief's "Ed drives it himself; the number is his cell". Confirm he drives every job.
- **"Pack the car with your things" (step 2) and "you can pack the car full"** follow the brief's differentiator. Not confirmed by Ed; there may be weight or contents limits.
- **"In the spring, I drive it back to New Jersey"** comes from your description of the business (2026-10-13).
- **The honest answer** (truck carrier if the car doesn't run or you don't want miles on it) is general driveaway knowledge in Ed's voice, not something he said.
- **The shamrock is a drawing** (same shape as the other Shamrock builds), not the card's emblem, because the brief says to ask before using a card scan. Green `#0b6b3a` is a readable shamrock green, not sampled from the card.
- **I chose the look without the Impeccable decision page** (unattended run). Options I weighed: the business card itself (picked), an AAA TripTik strip map, an interstate guide sign (already used by Owner Trust and Transparent Pricing), hotel stationery (Premium Concierge's), a mile-marker column, a valet key tag.
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
- **Runner-up world: an AAA TripTik strip map** — the route as a column of flip-strips from NJ down to FL, very familiar to this audience.
- **Text Ed link** under the Call button once Ed confirms he texts (pre-written: "Hi Ed, I'd like my car driven from ___ to ___ around ___.").
- **Atkinson Hyperlegible** as the body font (the research's pick for this age group), if you want to step off the system font.
- **A "What's included" line** under $1 a mile once Ed answers question 1.
- **Example trip totals** (e.g. Toms River → Naples) once Ed names his usual towns.

## Not verified
- Real-device tap-to-call on iPhone and Android, and inside Facebook's in-app browser.
- How the page reads to an actual 60-year-old (the research suggests a 5–6 person test).
