#### После установки проекта прописать:

`php -r "file_exists('.env') || copy('.env.example', '.env');"
`
#### Билдим и запускаем докер контейнер

`docker-compose up -d
`
#### Заходим в контейнер

`docker-compose exec sr-app bash`

#### Устанавливаем пакеты композера

`composer install`

#### Генерируем ключ:

`php artisan key:generate`