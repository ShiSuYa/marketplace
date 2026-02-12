# marketplace

## Запуск User Service

### Требования
- Docker
- Docker Compose

### Клонирование проекта
```bash
git clone https://github.com/ShiSuYa/marketplace.git
cd marketplace
```

### Запуск
docker-compose up --build

### Проверка
Открыть в браузере:

http://localhost:8000/health

Ожидаемый ответ:

{"status":"OK"}

Остановка
docker-compose down
