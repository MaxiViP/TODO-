# 🧠 Todo App (Fullstack)

Fullstack приложение для управления задачами с авторизацией, поиском,фильтрацией и современным UI.

## 📦 Структура проекта

```
backend/         → Node.js + Express API
todo-frontend/   → Nuxt 4 клиент
```

---

## 🚀 Стек

### Backend

- Node.js + Express
- SQLite
- JWT (Access + Refresh)
- Zod
- Pino

### Frontend

- Nuxt 4
- Pinia
- Tailwind CSS
- Axios

---

## ⚙️ Установка

### 1. Клонирование

```
git clone https://github.com/MaxiViP/TODO-.git
cd TODO-
```

---

### 2. Установка зависимостей

#### Backend

```
cd backend
npm install
```

#### Frontend

```
cd ../todo-frontend
npm install
```

---

## 🔐 Настройка .env

### Backend

Создать файл `.env`:

```
PORT=3001
JWT_SECRET=your_secret
```

### Frontend

```
API_URL=http://localhost:3001
```

---

## ▶️ Запуск

### Backend

```
cd backend
npm run dev
```

### Frontend

```
cd todo-frontend
npm run dev
```

---

## 🔐 Авторизация

- Access token (15 мин)
- Refresh token (cookie + DB)
- Автоматическое обновление токена

Тестовые аккаунты:

```
admin@test.com / admin123
user@test.com / 123456
```

---

## 📡 API

Основные эндпоинты:

### Auth

- POST /api/auth/login
- POST /api/auth/register
- POST /api/auth/refresh
- POST /api/auth/logout

### Tasks

- GET /api/tasks
- POST /api/tasks
- PUT /api/tasks/:id
- DELETE /api/tasks/:id

👉 Подробно см. `backend/README.md`

---

## 💻 Frontend

- Nuxt 4 (SSR)
- Pinia store
- Pagination, фильтры, поиск
- Авто refresh токена
- QR login

👉 Подробно см. `todo-frontend/README.md`

---

## 🛠️ Возможности

- JWT авторизация
- Роли (user / admin)
- CRUD задач
- Пагинация, фильтрация, поиск
- Безопасные cookies
- Современный UI

---

## 🚀 Планы

- Docker
- TypeScript backend
- WebSockets
- Rate limit

---

## 👤 Автор

Максим Поляков
📧 [batti@ya.ru](mailto:batti@ya.ru)
