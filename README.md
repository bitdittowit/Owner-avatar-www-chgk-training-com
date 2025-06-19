# CHGK Training Team App

Веб-приложение для тренировки команды ЧГК с синхронизацией в реальном времени.

## Архитектура
- **Frontend:** React (TypeScript), Vite, TailwindCSS, Zustand, Socket.IO-client
- **Backend:** Node.js (TypeScript), Express, Socket.IO
- **Хостинг:** Vercel/Netlify (frontend), Render/Fly.io (backend)

## MVP
- Создание и вход в комнату
- Кликабельный алфавит
- Таймеры для участников
- Мгновенная синхронизация через WebSocket

## Запуск
- `cd client && npm install && npm run dev` — фронтенд
- `cd server && npm install && npm run dev` — бэкенд 