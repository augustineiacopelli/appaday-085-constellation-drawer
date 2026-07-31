# 085 &middot; Constellation Drawer

Tap points on a night sky to place glowing stars and link them into a constellation. Anchor to any star to branch, name your figure, and save a shareable PNG with the name set in a star-chart serif. A calm, single-purpose creative toy that keeps your sketch on-device.

**Category:** Interactive (I)
**Live:** https://augustineiacopelli.github.io/appaday-085-constellation-drawer/
**Part of:** [AppADay](https://augustineiacopelli.github.io/appaday/)

## What it does

The whole screen is the sky. Tap open space to place a star, and each new star links to your current anchor so a real figure grows as you go. Tap an existing star to make it the anchor and branch a new line from it. Tap that same star again to release the anchor, so your next tap starts a fresh, disconnected line. Name the constellation and it appears beneath your drawing in a classical star-chart serif.

## Controls

Undo peels off the last star and the line it drew. Clear empties the sky after a confirmation. Save Image composes a higher-resolution PNG of your constellation with its name and a small AppADay credit, then shows it in a panel with a Download button and a long-press hint so it saves cleanly on a phone.

Your current sketch, name included, is saved in the browser and restored the next time you open the app.

## Notes

One self-contained file of vanilla HTML, CSS, and JavaScript. The sky, stars, lines, and export image are all drawn on a single canvas. Google Fonts is the only external resource: Cinzel for the constellation name and Josefin Sans for the interface. No build step, no dependencies, no account, and nothing leaves your device.

---

*Part of AppADay: one complete, mobile-friendly web app shipped every day.*
