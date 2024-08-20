環境構築
Dockerビルド
git clone git@github.com:coachtech-material/laravel-docker-template.git
docker-compose up -d --build

Laravel環境構築
docker-compose exec php bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed

使用技術
PHP 8.0
Laravel 10.0
MySQL 8.0
URL
開発環境: http://localhost
phpMyAdmin: http://localhost:8080
