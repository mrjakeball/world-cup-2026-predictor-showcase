<p align="center">
  <img src="./assets/header.svg" alt="World Cup 2026 Predictor" width="100%" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/РУССКИЙ-21262D?style=for-the-badge" alt="Русский" height="29" /></a>
  &nbsp;
  <a href="./README_EN.md"><img src="https://img.shields.io/badge/ENGLISH-8B5CF6?style=for-the-badge" alt="English" height="29" /></a>
</p>

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio/blob/main/README_EN.md"><img src="https://img.shields.io/badge/📚_ALL_PROJECTS-21262D?style=for-the-badge" alt="All projects" height="27" /></a>
  <a href="https://github.com/mrjakeball"><img src="https://img.shields.io/badge/↩_PROFILE-21262D?style=for-the-badge&logo=github&logoColor=white" alt="Profile" height="27" /></a>
</p>

---

# 🏆 World Cup 2026 Predictor

> **A client-side tournament prediction builder from the group stage to knockouts, awards and final export.**

<p>
  <img src="https://img.shields.io/badge/React_19-21262D?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-21262D?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
  <img src="https://img.shields.io/badge/Zustand-21262D?style=flat-square&logo=react&logoColor=8B5CF6" alt="Zustand" />
  <img src="https://img.shields.io/badge/Vitest-21262D?style=flat-square&logo=vitest&logoColor=6E9F18" alt="Vitest" />
</p>

> ⚠️ Unofficial fan-made project with no affiliation, partnership or endorsement from FIFA or tournament organisers. Demonstration data is used only to present the interface.

## 🎯 Project goal

Turn complex tournament logic into one continuous user journey.

A prediction needs to stay consistent from the first group results through the bracket, awards and export.

## 📌 At a glance

| | |
| :--- | :--- |
| ⚽ **Format** | Interactive tournament predictor |
| 🚦 **Status** | In development |
| 🌐 **Public build** | Not available yet |
| 🧠 **State** | Zustand |
| 🧪 **Tests** | Vitest |
| 🔒 **Source** | Private; this repository is a showcase |

## 🖼️ Interface

<p align="center">
  <a href="./assets/cover.jpg"><img src="./assets/cover.jpg" alt="World Cup 2026 Predictor" width="700" /></a>
</p>

<p align="center">
  <a href="./assets/screen-awards-desktop.jpg"><img src="./assets/screen-awards-desktop.jpg" alt="Awards screen" width="700" /></a>
</p>

<p align="center">
  <a href="./assets/screen-player-selected.jpg"><img src="./assets/screen-player-selected.jpg" alt="Player selection" width="520" /></a>
</p>

<p align="center">
  <a href="./assets/screen-awards-mobile.jpg"><img src="./assets/screen-awards-mobile.jpg" alt="Mobile awards view" width="220" /></a>
</p>

## 🧭 Tournament journey

1. ⚽ enter group-stage results;
2. 📊 calculate advancing teams;
3. 🥉 determine the best third-placed teams;
4. 🌳 build the knockout bracket;
5. 🏅 select individual awards;
6. 💾 save the prediction;
7. 📤 export the result.

## 🧠 State and logic

### 🔗 Connected state

Early results affect later stages, so the tournament cannot be treated as a collection of independent forms.

### ♻️ Migrations

Older local saves need to survive state-schema changes.

### 🧪 Tests

Automated checks cover the key rules between tournament stages.

## 📤 Export

The project supports saving and sharing results, including share codes and prediction export.

---

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio/blob/main/README_EN.md"><img src="https://img.shields.io/badge/←_PROJECT_DIRECTORY-8B5CF6?style=for-the-badge" alt="Project directory" height="30" /></a>
</p>

<p align="center">
  <a href="https://github.com/mrjakeball"><strong>GitHub profile ↑</strong></a>
</p>
## State and checks

Zustand manages interconnected interface state, migrations preserve older saves, and tests cover the key rules between tournament stages.

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio">← Back to all projects</a>
</p>
