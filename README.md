# Couple App

Приложение-планер для пар.

## Структура

```
couple-app/
├── client/    # React-фронтенд
└── server/    # Express-бэкенд
```

## Установка

1. Склонируйте репозиторий
2. В папке `server` установите зависимости:
   ```bash
   npm install
   ```
3. В папке `client` установите зависимости:
   ```bash
   npm install
   ```

## Запуск

### Бэкенд
```bash
cd server
npm run dev
```
Сервер запустится на `http://localhost:3000`

### Фронтенд
```bash
cd client
npm run dev
```
Фронтенд запустится на `http://localhost:5173`

## API

- `GET /api/health` — проверка здоровья сервера
