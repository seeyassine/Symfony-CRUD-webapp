# Symfony-CRUD-webapp
Complete CRUD Application in just 6 min

All CM you need to do the same project 

create a project --> php .\composer.phar create-project symfony/skeleton:"^6.3" project-name

for monolitique --> php  .\composer.phar require webapp

Configure database --> DATABASE_URL="mysql://root@127.0.0.1:3306/app?serverVersion=8.0.30&charset=utf8mb4"

create antity --> php .\bin\console make:entity

create database --> php bin/console doctrine:database:create

create table --> php .\bin\console doctrine:schema:update --dump-sql --force

create crud --> php .\bin\console make:crud

cd .\public\ --> and php -S localhost:8000