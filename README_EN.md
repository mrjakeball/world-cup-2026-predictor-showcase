<p align="center">
  <img src="./assets/header.svg" alt="World Cup 2026 Predictor — unofficial prediction builder" width="94%" />
</p>

<p align="center">
  <a href="./README.md">Русский</a> · <strong>English</strong> · <a href="https://github.com/mrjakeball/portfolio">All projects</a>
</p>

# World Cup 2026 Predictor

A client-side tournament prediction builder that moves from the group stage through the knockouts, individual awards and final export.

> An unofficial fan-made project with no affiliation, partnership or endorsement from FIFA or tournament organisers. All on-screen data is demonstrational.

| Match centre | Details |
|---|---|
| Format | Interactive prediction builder |
| State | In development; no public build yet |
| Technology | `React 19` `TypeScript` `Vite` `Zustand` `Vitest` |
| Source | Private; this repository contains only the showcase |

<p align="center">
  <a href="./assets/cover.jpg"><img src="./assets/cover.jpg" alt="Unofficial World Cup 2026 Predictor start screen" width="380" /></a>
  <a href="./assets/screen-awards-desktop.jpg"><img src="./assets/screen-awards-desktop.jpg" alt="Demonstration tournament awards panel" width="380" /></a>
</p>

<p align="center">
  <a href="./assets/screen-player-selected.jpg"><img src="./assets/screen-player-selected.jpg" alt="Player selection from the demonstration dataset" width="400" /></a>
</p>

<p align="center">
  <a href="./assets/screen-awards-mobile.jpg"><img src="./assets/screen-awards-mobile.jpg" alt="Demonstration tournament awards view on mobile" width="180" /></a>
</p>

## Prediction journey

Groups, best third-placed teams, the knockout bracket and awards form one continuous flow that can be saved and resumed later.

## Tournament logic

- group-stage result selection;
- advancing-team and bracket calculations;
- player search for demonstration awards;
- local saves, export and share codes.

## State and checks

Zustand manages interconnected interface state, migrations preserve older saves, and tests cover the key rules between tournament stages.

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio">← Back to all projects</a>
</p>
