# CLCT Thermal

An interactive design mockup for a CLCT redesign — the Bitcoin art and collectibles market at clctibles.com.
Thermal-camera styling: heat columns, isobands, iris transitions, a thermal boot splash.

It covers live auctions (bid graph under the artwork, bids arriving, adaptive price, SOLD), cards with offers,
market stats, media, the sell flow and the account pages. Everything is simulated in the browser: nothing is
listed, bid or paid, and payment screens are marked **DEMO · NOT PAYABLE**.

## Looking around

- The **Demo** pill opens the demo console: guided tour, clock speed, theme, motion, replay splash.
- **Ctrl/⌘ K** or **/** opens search; **Shift D** toggles the D650 spec layer.

## Files

A static site with no build step: `index.html`, `img/`, `marks/`, `vercel.json`.
To run it locally, serve the folder (for example `npx serve .`) rather than opening the file directly.

## Deploying on Vercel

Add New… → Project → import this repository → Deploy. `vercel.json` selects the **Other** preset (no build)
and caches images for a day. Share the production domain (`<project>.vercel.app`): with Vercel's Standard
Protection, the long per-deployment URLs ask visitors to sign in.

The other styling, **CLCT Proof**, is in its own repository (mockproof).
