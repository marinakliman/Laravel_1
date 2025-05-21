```
docker compose up --build
```

### Работа в php-cli
Заходим в контейнер с php-cli:
>docker compose exec php-cli bash

Установка Laravel:
```
composer create-project laravel/laravel example-app
```

Меняем доступ к папке "storage/":
```
chmod 777 -R storage/
```
![img1](https://github.com/user-attachments/assets/f4a0cc07-2e50-42c6-b03d-3ce94c835a33)
