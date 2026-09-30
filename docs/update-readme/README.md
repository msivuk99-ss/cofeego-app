# CoffeeGo — Мобільний додаток та веб-кабінет кав'ярень

## Опис проєкту
Проєкт призначений для швидкого попереднього замовлення кави без черг, використання накопичувальної системи бонусів та автоматизації роботи баристи і менеджера мережі[cite: 15, 22].

Тип системи: Cross-platform Mobile App (iOS/Android) + Web SPA (Панель баристи/менеджера) + REST API Backend.

---

## Стек технологій (Tech Stack)

### Client Side (Мобільний додаток & Web)
Mobile App: Flutter (Dart) — кросплатформова розробка під iOS (v14.0+) та Android (v9.0+).
Web UI (Кабінет баристи та менеджера): React.js / Vue.js — Single Page Application (SPA) для планшетів кав'ярні[cite: 18].
State Management: Provider / Bloc.

### Backend & Database
API Framework: Node.js (NestJS) / Python (FastAPI) — REST API сервіс[cite: 18].
Database: PostgreSQL — основна реляційна база даних для користувачів, замовлень та меню[cite: 18].
Authentication: JWT (JSON Web Tokens) + HTTPS (TLS 1.3)[cite: 18].

### Інтеграції та сервіси
POS-система: Двостороння інтеграція через REST API з POS-системою кав'ярні (Poster/iiko)[cite: 18].
Платіжний шлюз: Apple Pay, Google Pay SDK, LiqPay / MonoPay[cite: 18].
Push-сповіщення: Firebase Cloud Messaging (FCM) / Pusher для сповіщень про стан замовлення[cite: 18].
