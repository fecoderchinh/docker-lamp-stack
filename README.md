# Docker LAMP stack
Linux / Apache / MySQL / PHP

## Ports

Ports used in the project:
| Software | Port |
|-------------- | -------------- |
| **apache** | 8080 |
| **mysql** | 3306 |
#### IF you are facing with PORT problems, then you should change the PORT number in `.env`
```
DB_PORT=3306
APACHE_PORT=8080
```

Clone `.env.example` to `.env` and set up as your prefer detail

## Running Docker
```
npm run docker:up
```
## Building Docker
```
npm run docker:build
npm run docker:rebuild
```
## Cleaning Docker
```
npm run docker:clean
```
## Run laravel artisan
```
npm run docker:bash:php
```
Then you can use your `artisan`
## Run database
```
npm run docker:bash:db
```
Then you can use `mysql -uroot -p`