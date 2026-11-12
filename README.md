# StickShot 🏀

A mobile-first, cartoon-style stickman basketball arcade game built with plain HTML, CSS, and JavaScript.

## Play locally
Open `index.html` in a modern browser. No build step, framework, account, or database is required.

## Controls
- Touch, click, or drag on the court to aim.
- Pull away from the ball to set the shot direction, then release.
- Score baskets to build streaks and increase your level.
- You have three lives per run.

## Features
- Responsive mobile-first layout and touch controls
- Moving hoop and progressively increasing difficulty
- Score, best score, lives, streaks, and restart
- Best score saved in the browser with localStorage
- Lightweight synthesized sound effects with a sound toggle

## Deploy free with Cloudflare Pages
1. In Cloudflare, open **Workers & Pages** → **Create** → **Pages**.
2. Choose **Connect to Git** and select `AJ1716-QA/stickshot`.
3. Use the `main` branch.
4. Since this is a static site, leave the build command empty.
5. Set the build output directory to `/` (repository root), then deploy.

## Monetization status
There are currently **no ads or ad SDKs** in the game. Ad placements should only be added after an ad network or game portal approves the game and provides its official integration code. Never promise earnings: revenue depends on approval, traffic, geography, and ad performance.

## Privacy
The current version does not send gameplay data to a server. The personal best is stored only in the player's browser.
