# Docker Nginx Web Stack

## Verzije
- Nginx 1.13
- MySQL 5.7
- PHP 7.0 - fpm

## Usage

Start containers:

```shell
$ docker-compose up -d
```
or 

```shell
$ docker-compose up
```

Stop containers:

```shell
$ docker-compose down -v
```

*Flag `-v` deletes docker volumes. *

## Details and credentials

### nginx

- **Port:** 80

### PHP-FPM

- **Port:** 9000

### MySQL

- **Host:** localhost
- **Port:** 3306
- **Username:** root
- **Password:** root
- **Database:** web

### phpMyAdmin

- **Port:** 8080
- **Username:** root
- **Password:** root