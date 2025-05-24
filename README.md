# Seka Card Game

Карточная игра Seka - это увлекательная многопользовательская игра, разработанная с использованием современных веб-технологий.

## Особенности

- 🎮 Реалистичный игровой процесс
- 👥 Многопользовательский режим
- 💬 Чат между игроками
- 📊 Система рейтинга и статистики
- 🔔 Уведомления о событиях
- 📱 Адаптивный дизайн

## Технологии

- **Backend**: Python, FastAPI, PostgreSQL, Redis
- **Frontend**: HTML5, CSS3, JavaScript, WebSocket
- **DevOps**: Docker, Nginx, PM2
- **Тестирование**: pytest, Jest
- **Мониторинг**: Prometheus, Grafana

## Быстрый старт

### Требования

- Python 3.8+
- PostgreSQL 12+
- Redis 6+
- Node.js 14+
- npm 6+

### Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/your-username/seka-card-game.git
cd seka-card-game
```

2. Создайте виртуальное окружение:
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
.\venv\Scripts\activate   # Windows
```

3. Установите зависимости:
```bash
pip install -r requirements.txt
npm install
```

4. Настройте переменные окружения:
```bash
cp .env.example .env
# Отредактируйте .env файл
```

5. Инициализируйте базу данных:
```bash
python scripts/init_db.py
```

6. Запустите приложение:
```bash
# Режим разработки
python server.py
npm run dev

# Продакшен режим
pm2 start ecosystem.config.js
```

## Документация

- [Руководство по установке](docs/INSTALLATION.md)
- [Руководство по развертыванию](docs/DEPLOYMENT.md)
- [Руководство по разработке](docs/DEVELOPMENT.md)
- [Руководство по тестированию](docs/TESTING.md)
- [API документация](docs/API.md)

## Структура проекта

```
seka-card-game/
├── docs/                  # Документация
├── game/                  # Игровая логика
├── server/               # Серверная часть
├── static/               # Статические файлы
├── templates/            # HTML шаблоны
├── tests/                # Тесты
├── scripts/              # Скрипты
├── .env.example          # Пример конфигурации
├── requirements.txt      # Python зависимости
├── package.json          # Node.js зависимости
└── README.md            # Этот файл
```

## Разработка

### Запуск тестов

```bash
# Python тесты
pytest

# JavaScript тесты
npm test
```

### Линтинг

```bash
# Python
flake8
black .

# JavaScript
npm run lint
```

### Сборка

```bash
# Сборка фронтенда
npm run build

# Сборка Docker образа
docker build -t seka-game .
```

## Вклад в проект

1. Форкните репозиторий
2. Создайте ветку для новой функции (`git checkout -b feature/amazing-feature`)
3. Зафиксируйте изменения (`git commit -m 'Add amazing feature'`)
4. Отправьте изменения в репозиторий (`git push origin feature/amazing-feature`)
5. Создайте Pull Request

## Лицензия

Этот проект распространяется под лицензией MIT. Подробности в файле [LICENSE](LICENSE).

## Контакты

- Авторы: Жутяев Иван, Ломовской Артём
- Email: ivan.zhutyaev@mail.ru
- Проект: [https://github.com/IvanZhutyaev/seka-card-game](https://github.com/IvanZhutyaev/seka-card-game)

