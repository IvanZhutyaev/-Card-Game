# Seka Card Game

Карточная игра, разработанная как Telegram Mini App.

## Описание

Seka Card Game - это современная карточная игра, доступная через Telegram. Игра предлагает увлекательный игровой процесс, систему достижений, рейтинги и социальные функции.

## Основные возможности

- 🎮 Увлекательный игровой процесс
- 👥 Мультиплеер
- 🏆 Система достижений
- 📊 Рейтинги игроков
- 💬 Встроенный чат
- 🔔 Уведомления
- 🌐 Интеграция с Telegram

## Технологии

- JavaScript (ES6+)
- Jest для тестирования
- Telegram Mini Apps API
- WebSocket для реального времени

## Структура проекта

```
seka-card-game/
├── modules/
│   ├── components/     # UI компоненты
│   ├── services/       # Бизнес-логика
│   └── utils/          # Вспомогательные функции
├── tests/             # Тесты
├── assets/            # Статические ресурсы
└── docs/              # Документация
```

## Установка и запуск

1. Клонируйте репозиторий:
```bash
git clone https://github.com/your-username/seka-card-game.git
cd seka-card-game
```

2. Установите зависимости:
```bash
npm install
```

3. Запустите тесты:
```bash
npm test
```

4. Запустите приложение:
```bash
npm start
```

## Разработка

### Требования

- Node.js 14+
- npm 6+

### Команды

- `npm test` - запуск тестов
- `npm run test:watch` - запуск тестов в режиме наблюдения
- `npm run test:coverage` - запуск тестов с отчетом о покрытии
- `npm start` - запуск приложения
- `npm run build` - сборка проекта

## Тестирование

Проект использует Jest для тестирования. Тесты находятся в директории `tests/`.

```bash
# Запуск всех тестов
npm test

# Запуск тестов в режиме наблюдения
npm run test:watch

# Запуск тестов с отчетом о покрытии
npm run test:coverage
```

## Архитектура

### Компоненты

- `ProfileComponent` - управление профилем пользователя
- `MenuComponent` - навигационное меню
- `SettingsComponent` - настройки приложения
- `HelpComponent` - справочная информация
- `NotificationsComponent` - уведомления
- `LeaderboardComponent` - таблица лидеров
- `ChatComponent` - чат
- `GameComponent` - игровой процесс

### Сервисы

- `ProfileService` - управление данными профиля
- `NavigationService` - навигация
- `SecurityService` - безопасность
- `StorageService` - хранение данных
- `ImageService` - работа с изображениями
- `SettingsService` - настройки
- `HelpService` - справочная информация
- `NotificationsService` - уведомления

## Лицензия

MIT

## Контакты

- Email: your-email@example.com
- Telegram: @your-username
