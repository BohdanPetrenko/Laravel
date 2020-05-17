#### После установки проекта прописать:

`php -r "file_exists('.env') || copy('.env.example', '.env');"
`
#### Билдим и запускаем докер контейнер

`make up`

#### Заходим в контейнер

`make connect`

#### Устанавливаем пакеты композера

`composer install`

#### Генерируем ключ:

`php artisan key:generate`