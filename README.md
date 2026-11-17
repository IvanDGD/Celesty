# Celesty

Сервис сбора отзывов с настраиваемой страницей оценки.

## Структура
- `apps/web`: Next.js (кабинет, билдер, страница оценки)
- `apps/api`: ASP.NET Core
- `packages/theme-schema`: схема темы и пресеты
- `packages/css-fixtures`: тестовые CSS для санитайзера
- `infra`: Docker, туннель, деплой

## Запуск
pnpm install
pnpm dev:web