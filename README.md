# janote-docker

```
git clone https://github.com/kasuta96/janote-docker.git
cd janote-docker
```

.env.example -> rename to .env and edit
- MYSQL_ROOT_PASSWORD= [password]
- MYSQL_PASSWORD= [password]
```
docker-compose build
docker-compose up -d

docker-compose exec app bash
composer create-project --prefer-dist laravel/laravel janote "6.*"
cd janote
```

src/janote/.env.example  -> rename to .env and edit:
- APP_NAME=janote
- DB_HOST=db
- DB_DATABASE=janote
- DB_PASSWORD= [password]
```
php artisan migrate
```
- app http://localhost:8000/
- phpMyAdmin http://localhost:8080/
