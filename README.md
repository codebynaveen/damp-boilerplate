# DAMP (Docker + Apache + MySQL + PHP) Boilerplate

Customizable docker boilerplate for PHP and MySQL based projects.

Originaly designed as a wordrpress plugin development envioronment but easisy adaptable for any kind of PHP project.

## Contains
* PHP
* Apache2
* MySQL
* PhpMyAdmin


Warning: Not suitable for production environment.

## Requirements
* Docker

## Configuration
Create .env file with project information

```
IP=127.0.0.1
APP_NAME=myapp
DOMAIN=myapp.local
DB_HOST=mysql
DB_NAME=myapp
DB_USER=myapp
DB_PASSWORD=password
DB_ROOT_PASSWORD=password
DB_TABLE_PREFIX=wp_
```

## CLI
Bootup Containers

`docker-compose up --build web`
