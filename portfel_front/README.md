# PortFel · Frontend

Клиентская часть приложения для учёта инвестиционных портфелей: React, TypeScript, Redux Toolkit, Material UI и визуализация финансовых показателей.

Описание возможностей, скриншоты, архитектура и полный порядок настройки находятся в [корневом README](../README.md).

## Запуск

Нужны Node.js 20+ и npm. Сначала настройте и запустите Django-сервер по инструкции в корневом README.

Из каталога `portfel_front`:

```bash
npm ci
npm start
```

Клиент открывается на **http://localhost:3000/**. Адрес API задаётся в [`src/config.ts`](src/config.ts), по умолчанию — `http://localhost:8000/`.

## Команды

| Команда | Назначение |
| --- | --- |
| `npm start` | Сервер разработки |
| `npm run build` | Сборка приложения в `build/` |
| `npm test` | Jest через `react-scripts` |

Страницы находятся в `src/pages`, компоненты — в `src/components`, состояние — в `src/store`, HTTP-клиент и методы API — в `src/api`.
