# Dobrodon Frontend

Это приложение на Next.js для проекта Dobrodon, построенное с использованием современных веб-технологий и оптимизированное для производительности.

## 🚀 Возможности

- Next.js 15 с App Router
- TypeScript для типобезопасности
- TailwindCSS для стилизации
- Генерация и сканирование QR-кодов
- Интеграция с бэкенд-сервисами

## 📋 Требования
- npm
- node.js

## 🛠 Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/dobrodon/front-dobrodon
cd front-dobrodon
```
2. Установите зависимости:
```bash
npm install
```

## 🚀 Разработка

Запустите сервер разработки:
```bash
npm run dev
```

Приложение будет доступно по адресу [http://localhost:3000](http://localhost:3000).

## ☢️ Сервер

Запустите бекенд:
```bash
uvicorn main:app --reload --port 8023 --host <айпи сервера>
```

Сайт хостится на домене https://junior.enotgpt.ru

## 🔧 Конфигурация

Приложение настроено на подключение к бэкенд API по адресу:
http://<айпи сервера>:8023

Вы можете изменить адрес API в файле src/lib/api/config.ts при необходимости.

## 📦 Доступные скрипты

- npm run dev - Запуск сервера разработки с Turbopack
- npm run build - Сборка приложения для продакшена
- npm run start - Запуск продакшен-сервера
- npm run lint - Запуск ESLint для проверки качества кода

## 🛠 Технологический стек

- Фреймворк: Next.js 15
- Язык: TypeScript
- Стилизация: TailwindCSS
- UI Компоненты: Heroicons
- QR-код: qrcode.react, jsqr
- Утилиты: Lodash

## 📚 Документация
- [Презентация](https://github.com/dobrodon/.github/blob/1c0618cd1d67bdd5356d1d71d2889512d7282a0e/DobroDon-presentation.pdf)
- [Документация фронтенда](https://github.com/dobrodon/.github/blob/0e8d21d9fb6d1da7981013a1dc8b5e5956d07e5a/DobroDon-documentation-frontend.docx)
- [Документация бекенда](https://github.com/dobrodon/.github/blob/92861500797e49afd159936fe21034c8ba07eee0/Dobrodon-documentation-backend.docx)

## 🤝 Участие в разработке

1. Форкните репозиторий
2. Создайте ветку для вашей функции (git checkout -b feature/amazing-feature)
3. Зафиксируйте изменения (git commit -m 'Добавлена потрясающая функция')
4. Отправьте изменения в ветку (git push origin feature/amazing-feature)
5. Откройте Pull Request


