<p align="center">
  <img src="./assets/header.svg" alt="World Cup 2026 Predictor" width="100%" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/РУССКИЙ-21262D?style=for-the-badge" alt="Русский" height="29" /></a>
  &nbsp;
  <a href="./README_EN.md"><img src="https://img.shields.io/badge/ENGLISH-8B5CF6?style=for-the-badge" alt="English" height="29" /></a>
</p>

<p align="center">
  <a href="https://courageous-elf-34b597.netlify.app"><img src="https://img.shields.io/badge/▶_OPEN_PROJECT-8B5CF6?style=for-the-badge" alt="Open project" height="27" /></a>
  <a href="https://github.com/mrjakeball/portfolio/blob/main/README_EN.md"><img src="https://img.shields.io/badge/📚_ALL_PROJECTS-21262D?style=for-the-badge" alt="All projects" height="27" /></a>
  <a href="https://github.com/mrjakeball"><img src="https://img.shields.io/badge/↩_PROFILE-21262D?style=for-the-badge&logo=github&logoColor=white" alt="Profile" height="27" /></a>
</p>

---

# 🏆 World Cup 2026 Predictor

> **A client-side tournament prediction builder covering the journey from the group stage to knockouts, awards and result export.**

<p>
  <img src="https://img.shields.io/badge/React_19-21262D?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-21262D?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
  <img src="https://img.shields.io/badge/Zustand-21262D?style=flat-square&logo=react&logoColor=8B5CF6" alt="Zustand" />
  <img src="https://img.shields.io/badge/Vitest-21262D?style=flat-square&logo=vitest&logoColor=6E9F18" alt="Vitest" />
</p>

> ⚠️ Unofficial fan-made project with no affiliation, partnership or endorsement from FIFA or tournament organisers. Demonstration data is used only to present the interface.

## 🎯 Project goal

Turn complex tournament logic into one continuous and understandable user journey.

A prediction needs to remain consistent from the first group-stage results through the knockout bracket, awards and final export.

## 📌 At a glance

| | |
| :--- | :--- |
| ⚽ **Format** | Interactive tournament predictor |
| 🚦 **Status** | Live build published |
| 🌐 **Live version** | [Open project ↗](https://courageous-elf-34b597.netlify.app) |
| 🧠 **State management** | Zustand |
| 🧪 **Tests** | Vitest · 26 tests |
| 🔒 **Source** | Private; this repository is a public showcase |

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
  <a href="./assets/screen-awards-mobile.jpg"><img src="./assets/screen-awards-mobile.jpg" alt="Awards on mobile" width="220" /></a>
</p>

## 🧭 Tournament journey

1. ⚽ enter group-stage results;
2. 📊 determine the advancing teams;
3. 🥉 calculate the best third-placed teams;
4. 🌳 generate the knockout bracket;
5. 🏅 select individual awards;
6. 💾 save the prediction;
7. 📤 export the result.

## 🧠 State and logic

### 🔗 Connected state

The different stages of the tournament depend on each other.

Changing a group-stage result can affect the teams that advance to the knockout stage and the later bracket, so the application's data is managed as one connected state.

**Zustand** is used for this state management.

### ♻️ Save migrations

Predictions are stored locally.

When the application's data structure changes, older saves need to remain compatible with the newer version, so migration logic is used to update stored data.

### 🧪 Automated tests

Key tournament logic is covered by automated tests:

- group standings;
- best third-place ranking;
- knockout bracket generation;
- saving and restoring data;
- share codes;
- player data;
- result export.

The current version passes **26 automated tests**.

## 📤 Export and persistence

The project supports saving and sharing a completed prediction.

It includes:

- 💾 local persistence;
- 🔗 share codes;
- 📋 final prediction summaries;
- 🏅 individual award selections;
- 📤 result export.

---

<p align="center">
  <a href="https://courageous-elf-34b597.netlify.app"><img src="https://img.shields.io/badge/▶_OPEN_PROJECT-8B5CF6?style=for-the-badge" alt="Open project" height="30" /></a>
  <a href="https://github.com/mrjakeball/portfolio/blob/main/README_EN.md"><img src="https://img.shields.io/badge/←_PROJECT_DIRECTORY-21262D?style=for-the-badge" alt="Project directory" height="30" /></a>
</p>

<p align="center">
  <a href="https://github.com/mrjakeball"><strong>GitHub profile ↑</strong></a>
</p>
