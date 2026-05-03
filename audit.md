# Fincantieri Marine Group — Website Audit

**Date:** 2026-05-03
**URL audited:** https://fincantierimarinegroup.com/
**Niche:** Defense / commercial shipbuilding (B2B, government contracts)
**Tech stack observed:** WordPress + Oxygen Builder, last major image uploads dated 2019-2021

---

## Phase 0 — Real website?

**YES.** Functional WordPress site on owned domain. Continue to Phase 1 audit.

## Phase 1 — Display audit

| # | Category | Score /10 | Notes |
|---|---|---|---|
| 1 | **Photo quality** | 3 | This is the prospect's biggest weakness, called out explicitly. Vessel imagery uploaded 2019-2021 is small (likely 800-1200px wide), inconsistent crop ratios, weak compression. Multiple H2s appear duplicated suggesting label-on-image template artifact. For a defense contractor selling $billion-plus contracts, the photography fails the brand. |
| 2 | **Information architecture** | 4 | Mega-dropdown with 50+ menu items hidden behind product taxonomy. No vessel-grid scannable summary on the homepage — visitors must drill into the menu. Markets (Navy/CG/Commercial/Government) are surfaced but vessel types beneath them are buried. |
| 3 | **Pricing transparency** | N/A | Skip — defense / commercial shipbuilding pricing is contract-bid by definition. Score against PORTFOLIO transparency instead → ~5/10 (vessel pages exist but case studies / spec sheets are thin). |
| 4 | **CTA per item** | 4 | Generic "Contact" page is the only CTA. No per-vessel "Request capabilities document" or "Schedule a yard tour". |
| 5 | **Mobile display** | 5 | Oxygen Builder mobile-responsive defaults, but the mega-menu is unwieldy on mobile and the small vessel photos look even worse at narrow widths. |
| 6 | **Trust signals near items** | 6 | Strong client logos (US Army, Crowley, Moran Towing, Interlake Steamship, Washington Island Ferry) but they sit in a separate strip. Not contextual to specific vessel categories. |

**Total: 27 / 60** (excluding pricing column N/A — normalized: ~22/50)

## Phase 2 — Decision

**BUILD: display demo + hero teaser** (score in 0-23 normalized range when adjusted for N/A pricing).

The user explicitly flagged image quality as the weakest point, which the audit confirms. The build focuses on:
1. Cinematic hero with a slow-zoom Ken Burns effect on a high-resolution warship-at-sea photo.
2. Vessel showcase with consistent 4:5 cinematic cards using high-quality maritime photography.
3. Three-shipyard capabilities section (Marinette, Sturgeon Bay, Green Bay) — currently underweight on their site.
4. Premium navy/gold/steel palette that reads "defense contractor" not "WordPress 2019".

## Override flags

- **In-house marketing team likely.** Fincantieri Marine Group is a $multi-billion subsidiary of Fincantieri S.p.A. (Italian state-controlled shipbuilder). They have internal communications staff. This means:
  - Selling them an SEO retainer is a long-shot. Their web presence isn't their bottleneck — government RFPs and Navy contracts are.
  - This demo is most useful as a **portfolio piece** for AG1 to show OTHER prospects what's possible, not as a serious sales pitch to FMG.
  - Recommended: build the demo for portfolio use, attempt outreach for completeness, but don't sink dream-deliverable effort into pursuit.

## What's in the demo

A single-page HTML demo at [index.html](index.html) showing:
- Cinematic Ken Burns hero with warship-at-sea photography
- 4-market grid (Navy, Coast Guard, Commercial, Government)
- 12-vessel showcase grid (frigate, polar cutter, LNG barge, ATB, PSV, wind farm vessel, research, dredge, ferry, repair, bulker, custom)
- 3-shipyard capabilities cards (Marinette / Sturgeon Bay / Green Bay)
- Client logo strip (text-based for now, real logos available from current site)
- Final CTA section with second cinematic background

## Pitch line if proceeding

> "We took your three-shipyard story and built it the way it deserves to be presented — cinematic, scannable, defense-grade. Your real photography slots straight in. Take a look."
