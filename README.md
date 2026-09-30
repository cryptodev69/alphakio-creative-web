# AlphaKio — Founding Traders landing page

A single-file landing page (`index.html`) for AlphaKio's Founding Traders / Cohort #1 campaign. No build step, no dependencies beyond Google Fonts.

**Sections:** noise→signal particle hero (cursor lens + scroll resolve), pinned Record → Blueprint → Alpha → Practice pipeline, interactive dual-track grading lab with re-ranking leaderboard, flip-card Signal School, offer vs. roadmap ledger, 100-seat grid, application form.

**Run locally:** open `index.html`, or `python3 -m http.server` and visit `http://localhost:8000`.

**Before launch:** wire the application form to a real intake endpoint (see the `TODO` in the script). Concept features are labelled as such on the page; keep it that way until they ship.

## Funnel pages

- `lastcall/` — for traders displaced by TradingView retiring public chats (Sep 30, 2026). Auto-playing intro film (chat wall → RETIRED stamp → CRT switch-off → flashlight in the dark → door of light you scroll through), a live example room, room-host pitch, a Discord band, and a just-for-fun ticket that hands off to the 7-day free trial onboarding (nothing is submitted).
- `scroll/` — "The Way", an alternate Founding Traders page (ink & paper). Canvas brush engine paints an ensō hero, a sideways-scrolling paper scroll with five chapters, a sword-cut workflow scene, hanko-seal offer cards and a brush signature pad. Apply form is client-side only (see `TODO`).
