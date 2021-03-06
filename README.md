### DESCRIPTION
Настроить окружение.

### TASK
Приложение запустится и на ``GET http://localhost:9999/api/cards`` выдать JSON с картами:

![img.png](data/data/img.png)

### LAUNCH
1. Запускаем контейнер ``docker compose up``
1. Запускаем приложение ``java -jar db-api.jar``
1. Открываем в браузере http://localhost:9999/api/cards

### TOOLS
Docker, PostgreSQL