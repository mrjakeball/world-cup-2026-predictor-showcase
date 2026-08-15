<p align="center">
  <img src="./assets/header.svg" alt="World Cup 2026 Predictor" width="100%" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/РУССКИЙ-8B5CF6?style=for-the-badge" alt="Русский" height="29" /></a>
  &nbsp;
  <a href="./README_EN.md"><img src="https://img.shields.io/badge/ENGLISH-21262D?style=for-the-badge" alt="English" height="29" /></a>
</p>

<p align="center">
  <a href="https://courageous-elf-34b597.netlify.app"><img src="https://img.shields.io/badge/▶_ОТКРЫТЬ_ПРОЕКТ-8B5CF6?style=for-the-badge" alt="Открыть проект" height="27" /></a>
  <a href="https://github.com/mrjakeball/portfolio"><img src="https://img.shields.io/badge/📚_ВСЕ_ПРОЕКТЫ-21262D?style=for-the-badge" alt="Все проекты" height="27" /></a>
  <a href="https://github.com/mrjakeball"><img src="https://img.shields.io/badge/↩_ПРОФИЛЬ-21262D?style=for-the-badge&logo=github&logoColor=white" alt="Профиль" height="27" /></a>
</p>

---

# 🏆 World Cup 2026 Predictor

> **Клиентский конструктор турнирного прогноза от группового этапа до плей-офф, наград и экспорта результата.**

<p>
  <img src="https://img.shields.io/badge/React_19-21262D?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-21262D?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
  <img src="https://img.shields.io/badge/Zustand-21262D?style=flat-square&logo=react&logoColor=8B5CF6" alt="Zustand" />
  <img src="https://img.shields.io/badge/Vitest-21262D?style=flat-square&logo=vitest&logoColor=6E9F18" alt="Vitest" />
</p>

> ⚠️ Неофициальный fan-made проект без связи, партнёрства или одобрения FIFA и организаторов турнира. Данные на демонстрационных экранах используются только для показа интерфейса.

## 🎯 Задача проекта

Собрать сложную турнирную логику в один последовательный пользовательский маршрут.

Прогноз должен сохранять целостность от первых результатов групп до финальной сетки, наград и экспорта.

## 📌 Коротко

| | |
| :--- | :--- |
| ⚽ **Формат** | Интерактивный tournament predictor |
| 🚦 **Статус** | Рабочая версия опубликована |
| 🌐 **Публичная версия** | [Открыть сайт ↗](https://courageous-elf-34b597.netlify.app) |
| 🧠 **State** | Zustand |
| 🧪 **Тесты** | Vitest · 26 тестов |
| 🔒 **Исходники** | Приватные; здесь публичная витрина |

## 🖼️ Интерфейс

<p align="center">
  <a href="./assets/cover.jpg"><img src="./assets/cover.jpg" alt="World Cup 2026 Predictor" width="700" /></a>
</p>

<p align="center">
  <a href="./assets/screen-awards-desktop.jpg"><img src="./assets/screen-awards-desktop.jpg" alt="Экран наград" width="700" /></a>
</p>

<p align="center">
  <a href="./assets/screen-player-selected.jpg"><img src="./assets/screen-player-selected.jpg" alt="Выбор игрока" width="520" /></a>
</p>

<p align="center">
  <a href="./assets/screen-awards-mobile.jpg"><img src="./assets/screen-awards-mobile.jpg" alt="Награды на телефоне" width="220" /></a>
</p>

## 🧭 Турнирный маршрут

1. ⚽ заполнить результаты групп;
2. 📊 определить проходящие команды;
3. 🥉 рассчитать лучшие третьи места;
4. 🌳 построить сетку плей-офф;
5. 🏅 выбрать индивидуальные награды;
6. 💾 сохранить прогноз;
7. 📤 экспортировать результат.

## 🧠 Состояние и логика

### 🔗 Связанное состояние

Изменение ранних результатов может влиять на последующие этапы, поэтому данные нельзя рассматривать как независимые формы.

### ♻️ Миграции

Старые локальные сохранения должны переживать изменения структуры состояния.

### 🧪 Тесты

Ключевые правила перехода между этапами покрываются автоматическими проверками.

## 📤 Экспорт

Проект предусматривает сохранение и передачу результата, включая share-code и экспорт пользовательского прогноза.

---

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio"><img src="https://img.shields.io/badge/←_КАТАЛОГ_ПРОЕКТОВ-8B5CF6?style=for-the-badge" alt="Каталог проектов" height="30" /></a>
</p>

<p align="center">
  <a href="https://github.com/mrjakeball"><strong>Профиль GitHub ↑</strong></a>
</p>
## Состояние и проверки

Zustand управляет связанным состоянием интерфейса, миграции поддерживают старые сохранения, а тесты проверяют ключевые правила перехода между этапами.

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio">← Вернуться к списку проектов</a>
</p>
