<p align="center">
  <img src="./assets/header.svg" alt="World Cup 2026 Predictor — неофициальный конструктор прогноза" width="94%" />
</p>

<p align="center">
  <strong>Русский</strong> · <a href="./README_EN.md">English</a> · <a href="https://github.com/mrjakeball/portfolio">Все проекты</a>
</p>

# World Cup 2026 Predictor

Клиентский конструктор турнирного прогноза: пользователь проходит путь от группового этапа до плей-офф, индивидуальных наград и итогового экспорта.

> Неофициальный fan-made проект без связи, партнёрства или одобрения FIFA и организаторов турнира. Все данные на экранах демонстрационные.

| Матч-центр | Детали |
|---|---|
| Формат | Интерактивный конструктор прогноза |
| Состояние | В разработке; публичной версии пока нет |
| Технологии | `React 19` `TypeScript` `Vite` `Zustand` `Vitest` |
| Исходники | Приватны; этот репозиторий содержит только витрину |

<p align="center">
  <a href="./assets/cover.jpg"><img src="./assets/cover.jpg" alt="Стартовый экран неофициального World Cup 2026 Predictor" width="380" /></a>
  <a href="./assets/screen-awards-desktop.jpg"><img src="./assets/screen-awards-desktop.jpg" alt="Демонстрационная панель турнирных наград" width="380" /></a>
</p>

<p align="center">
  <a href="./assets/screen-player-selected.jpg"><img src="./assets/screen-player-selected.jpg" alt="Выбор игрока из демонстрационного набора" width="400" /></a>
</p>

<p align="center">
  <a href="./assets/screen-awards-mobile.jpg"><img src="./assets/screen-awards-mobile.jpg" alt="Демонстрационная панель турнирных наград на телефоне" width="180" /></a>
</p>

## Сценарий прогноза

Группы, лучшие третьи места, сетка плей-офф и награды складываются в единый последовательный маршрут, который можно сохранить и продолжить позже.

## Турнирная логика

- выбор результатов группового этапа;
- расчёт проходящих команд и сетки;
- поиск игроков для демонстрационных наград;
- локальные сохранения, экспорт и share-code.

## Состояние и проверки

Zustand управляет связанным состоянием интерфейса, миграции поддерживают старые сохранения, а тесты проверяют ключевые правила перехода между этапами.

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio">← Вернуться к списку проектов</a>
</p>
