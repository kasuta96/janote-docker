# janote-docker

git clone https://github.com/kasuta96/janote-docker.git
`cd janote-docker`

rename to .env and edit db infomation: .env.example

```docker-compose build```
`docker-compose up -d`

`docker-compose exec app bash`
`composer create-project --prefer-dist laravel/laravel janote "6.*"`
`cd janote`

rename to .env and edit db infomation: src/janote/.env.example
php artisan migrate
go http://localhost:8010/
