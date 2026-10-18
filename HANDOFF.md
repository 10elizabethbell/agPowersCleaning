# A&G Power's Cleaning Services — handoff at ~60%

**Live:** https://10elizabethbell.github.io/agPowersCleaning/ · **Repo:** https://github.com/10elizabethbell/agPowersCleaning · **Built:** 2026-10-18 from Muse brief (run 2026-10-18, Facebook group sweep)

## What's built
- One page, single file (`index.html`, ~44 KB, no images to load), phone first. Header with an A&G lettermark and `201-306-3891` (tap-to-call) in the top right.
- **World: a window mid-clean.** The hero is a dirty window in a white frame; a yellow-and-green kitchen sponge wipes it by itself, and the visitor takes over by dragging in any direction (finger or mouse). Clean glass shows a sunny sky, a neighbour's house and trees; soap bubbles come off the sponge and get pushed by the finger; grime creeps back as specks. Tunables at the top of `windowPane()` (`REGROW`, `REGROW_SPECKS`, `BRUSH_PHONE/DESK`, `IDLE_RESUME`, `AUTO_SPEED`, `BUBBLES_MAX`).
- Section edges are animated wet "squeegee" seams (`seams()`: `SPEED`, `AMP`).
- Headline is their own slogan: "A clean space is a happy space." Hero buttons: **Text us for a free estimate** (sms with a prefilled message) and an outlined **Fill out the estimate form**.
- What we clean: 5 rows, each opens a text naming the service. On a computer (where `sms:` does nothing) a row jumps to the form with that service ticked.
- How it works (3 steps), Our promise (Reliable / Friendly / Detail-oriented: their own three words), "See our work on Instagram" card.
- Free estimate form: name, service chips, town (required); size, when, notes (optional). It composes a text to 201-306-3891; there's a copy-message fallback if the texting app doesn't open. This is the after-hours capture Muse flagged as the selling point.
- Footer: name, slogan, call/text number, Instagram, "Residential & commercial cleaning in New Jersey."
- Favicon / home-screen icon / og:image (1200x630) are in the repo; og points at the live URL.

## Assumptions I made
- **Voice "we"**: the ad says "Message us".
- **Colors** (deep teal `#0f3b40`, mint, sponge yellow `#ffc94d`, accent `#0b7770`): no brand colors exist; chosen to read "fresh and clean" with a warm sponge accent.
- **Promise copy** ("on time, friendly, and down to the corners nobody checks", "Baseboards, light switches, behind the faucet", "When we give you a day and a time, that's when we're at your door"): expansions of their own "Reliable, friendly, and detail-oriented" line. Owner should confirm they're comfortable promising these.
- **How it works**: inferred from "Message us for a FREE estimate" (text → estimate → clean). Not stated by them.
- **"Commercial cleaning"** row stands in for their "Residential & Commercial Cleaning" item (homes are already covered by the other rows).
- **Not a 40+ audience**: general homeowners, so the moving signature stays.

## Placeholders and gaps
- **No logo**: favicon and header mark use the site's own "A&G" lettering.
- **No photos, no before/afters, no reviews**: no proof section. The Instagram card stands in for "see more of our work".
- **Instagram @powerscleaningservices is unverified** (from the ad; Instagram returns a blank shell to anything not logged in). If it's wrong or empty, remove the card and footer link.
- **No Facebook business page.** The ad came from a personal profile whose link to the business isn't stated, so nothing links to Facebook.
- **No email** (the footer would carry it), **no towns**, **no hours**, **no prices**, **no owner name**.

## Questions for the owner
- Who runs it (name for the page), and is the posting profile theirs?
- Which towns/counties do you cover?
- Email to put in the footer?
- Can you send 6–10 photos of real jobs, ideally before/after pairs from the same spot?
- Any reviews (Google, Facebook, texts from happy customers) we can quote word for word?
- Hours, or do you answer texts any time?
- Which service matters most (deep clean vs regular vs move-out vs offices)?
- Is the Instagram handle right?

## Ideas not built (yours to pick)
- **Runner-up world:** dust motes drifting in a sunbeam across a clean room, scattering away from the finger.
- Soap-bubble puff when a service chip is ticked and when "Your message is ready" appears (like Sunny Side's splash).
- Reward for cleaning the window: once ~60% is clean, the sun brightens and a few bubbles rise.
- Suds/bubbles riding the section seams so the material carries past the hero.
- A wet edge where the wiped area meets the grime.
- Before/after sliders in the window frame once real photos arrive.
- Spanish toggle if the customer base wants it (unknown).

## Not verified
- Real-device touch (iPhone Safari / Facebook in-app browser on iOS and Android). Tested with simulated touch and mouse sweeps in headless Chrome at 360 and 390px.
- Real SMS handoff on iOS/Android (the `sms:+12013063891?&body=` format is the one that worked on earlier builds).
- Frame rate on older phones.
- Impeccable detector ran in full (not degraded) mode; remaining flags: `flat-type-hierarchy` on body sizes (15/17/19/24; accepted), `cramped-padding` on the service list (false positive). `overused-font roboto` suppressed: it's the Android fallback in the required system font stack.
