# DockerTask
## Задача
Напишите многоконтейнерное приложение, используя Docker Compose, и разверните его на локальной машине.
## Требования:
Создайте несколько сервисов (например, веб-сервер, база данных) в вашем приложении.
Напишите файл docker-compose.yml, описывающий структуру вашего приложения.
Используйте сети Docker Compose для обеспечения взаимодействия между сервисами.
Проверьте работоспособность вашего приложения, запустив его с помощью Docker Compose.
## Использование

1. Клонирование репозитория:

    ```bash
    git clone git@github.com:aslelekova/DockerTask.git
    cd DockerTask
    

2. Запуск приложения:

    ```bash
    docker-compose up -d
    

3. Проверка работоспособности:

    Откройте веб-браузер и перейдите по адресу http://localhost:80. Вы должны увидеть страницу приветствия Nginx.

## Остановка приложения:

```bash
docker-compose down
