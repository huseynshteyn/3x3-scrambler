# CubeScramble

A small, mobile-first 3×3 Rubik's Cube scramble generator and speed timer. It is a static PWA: no build step, framework, account, or backend required.

## Features

- 3×3 random-move scrambles (20, 25, or 30 moves)
- Copy scramble button
- Spacebar and touch-friendly timer
- Solve history, best time, and rolling Ao5 (trimmed mean of the latest five)
- Local storage: solve history stays on this device
- Installable PWA with an offline service worker

> Scrambles are generated as random legal face-turn sequences with no identical adjacent faces. They are useful for practice, but are not certified WCA random-state scrambles.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/ (root)**, then save.
4. Wait for GitHub Pages to publish the site. Open the URL shown in the Pages settings.

## Install on a phone

- **Android (Chrome):** open the published HTTPS site, then use the browser's **Install app** prompt or menu.
- **iPhone/iPad (Safari):** open the site, tap **Share → Add to Home Screen**.

The service worker needs HTTPS (GitHub Pages provides it) or localhost. After the first visit, the app shell is cached for offline use.