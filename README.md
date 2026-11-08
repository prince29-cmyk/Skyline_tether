# Skyline Tether

A web-swinging rooftop runner set in a city at dusk. Fire a tether, swing between skyscrapers, smash drones and take down the Warden network.

Runs in any modern browser on **phones, tablets and laptops**. No install and no build step: it's a single `index.html` file.

## Play

- **Online:** turn on GitHub Pages (see below) and open `https://<your-username>.github.io/<repo-name>/`
- **Offline:** download the repo and open `index.html` in your browser

## Controls

| Action | Phone | Laptop |
| --- | --- | --- |
| Swing | Touch and hold | Hold mouse button or Space |
| Let go / fling | Lift your finger | Release |
| Jump (on a roof) | Tap | Click or Space |
| Climb a wall | Hold against the wall | Hold against the wall |
| Pause | II button | P or Esc |
| Sound on/off | SND button | M |

On phones the game plays in landscape.

## Features

- **Endless mode:** cycles through 6 districts (Downtown, The Docks, Riverside Park, Subway Line, Rooftop Festival, The Spire District), with dusk, night and rainy-storm skies
- **Story mode:** 6 chapters with comic-panel cutscenes, civilians to rescue and a boss at the end of each chapter, ending with a climb up the Spire to fight Warden Prime
- **Combos** up to x5, slow-motion takedowns, shooting drones and a searchlight chopper
- **Missions** that reward orbs, plus **6 unlockable suits**
- **Leaderboard** of your top 5 runs and today's best
- Music and sound effects made in the browser (Web Audio)
- Pauses automatically when you switch apps or tabs, and lowers graphics quality on slower phones

Progress is saved in your browser's local storage.

## Put it online with GitHub Pages

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
4. After a minute, your game is live at `https://prince29-cmyk.github.io/<repo-name>/`.

## Tech

Plain HTML, CSS and JavaScript with Canvas 2D and the Web Audio API. No frameworks or dependencies. The only external request is for Google Fonts, and the game still works without it.
