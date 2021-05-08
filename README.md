# janote-docker

```
git clone https://github.com/kasuta96/janote-docker.git
cd janote-docker
```

.env.example -> rename to .env and add db password

```
docker-compose build
docker-compose up -d

docker-compose exec app bash
composer create-project --prefer-dist laravel/laravel janote "6.*"
cd janote
```

src/janote/.env.example  -> rename to .env and add db password
```
php artisan migrate
```
go http://localhost:8000/
