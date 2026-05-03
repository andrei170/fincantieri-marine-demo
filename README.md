# Fincantieri Marine Group — Product Display Demo v1

**Status:** BUILT
**Audit score:** 27 / 60 (normalized ~22/50 excluding N/A pricing column)
**Decision:** Build display demo + cinematic hero. Their image quality is the weakest part of the current site, called out explicitly by Andrei.
**What we built:** Cinematic Ken Burns hero + 12-vessel showcase grid + 3-shipyard capabilities section, all on a defense-grade navy/gold palette.

## What's in the demo

A standalone HTML demo (`index.html`) presenting Fincantieri's vessel portfolio with the production quality the brand deserves:

- Slow-zoom cinematic warship hero with parallax-style Ken Burns animation
- Markets bar (Navy / Coast Guard / Commercial / Government) with hover photo reveal
- 12 vessel cards in a 3-col grid: Constellation Frigate, Polar Security Cutter, LNG Bunker Barge, Articulated Tug Barge, Platform Support Vessel, Wind Farm Vessel, Research Vessel, Cutter-Suction Dredge, Passenger Ferry, Repair & Maintenance, Self-Unloading Bulker, Custom Build inquiries
- Three-yard capabilities section (Marinette Marine, Bay Shipbuilding, ACE Marine) with founding dates and specialties
- Client logo strip (Navy, Coast Guard, Army, Crowley, Moran Towing, Interlake)
- Final CTA section with shipyard photography background

## Tech notes

- Single self-contained `index.html` (no external CSS/JS files needed)
- Pure HTML + CSS, vanilla. No frameworks, no build step.
- Bebas Neue (display) + Inter (body) via Google Fonts
- Maritime photography from Unsplash (12 verified URLs)
- Mobile responsive: 1320px / 1024px / 640px breakpoints

## Deploy

**Option A — Netlify Drop (fastest):** Drag this folder into [https://app.netlify.com/drop](https://app.netlify.com/drop) → live URL in ~10 seconds.

**Option B — GitHub Pages:** Push to `andrei170.github.io/fincantieri-demo` or similar repo path.

**Option C — Just open it:** Double-click `index.html`. Loads in browser instantly. Good for screen-share without deploying.

## Pitch context

Important caveat: Fincantieri Marine Group is a multi-billion-dollar subsidiary of Italian state shipbuilder Fincantieri S.p.A. with in-house marketing staff. The realistic value of this build is:

1. **Portfolio piece** — Show OTHER prospects what AG1 can produce when given a real visual brand to work with. The defense-grade aesthetic translates well to legal, financial, custom builders, luxury hospitality.
2. **Long-shot outreach** — Send the URL to FMG marketing. Even if they don't engage, it demonstrates competence at a defense-contractor level.
3. **Style reference** — Use this as the "Tier S premium / industrial" visual reference in the prospect-website-rebuild skill's tier list section.

## Pitch line (if approaching FMG)

> "We took your three-shipyard story and built it the way it deserves to be presented — cinematic, scannable, defense-grade. Your real photography slots straight in. Take a look."

## Pitch line (using as portfolio for OTHER prospects)

> "Here's what we built for a Wisconsin shipbuilder — same level of polish we'd ship for your [inventory / menu / rooms]."
