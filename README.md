[![CodeFactor](https://www.codefactor.io/repository/github/sergeevpasha/laravel-docker-image/badge)](https://www.codefactor.io/repository/github/sergeevpasha/laravel-docker-image)
![Docker Image CI](https://github.com/sergeevpasha/laravel-docker-image/workflows/Docker%20Image%20CI/badge.svg)

# A docker image for Laravel

Built on PHP 7.4-FPM image

Main locale: en_US.UTF-8

## PHP Modules

* bcmath       
* Core
* ctype
* curl
* date
* dom
* exif
* fileinfo
* filter
* ftp
* gd
* gettext
* hash
* iconv
* imap
* intl
* json
* libxml
* mbstring
* mysqli
* mysqlnd
* openssl
* pcntl
* pcre
* PDO
* pdo_mysql
* pdo_pgsql
* pdo_sqlite
* Phar
* posix
* readline
* redis
* Reflection
* session
* SimpleXML
* soap
* sodium
* SPL
* sqlite3
* standard
* tokenizer
* xml
* xmlreader
* xmlwriter
* zip
* zlib

Example configuration for docker-compose.yml
```
app:
    image: sergeevpasha/laravel:latest
    tty: true
    volumes:
        - ./:/var/www
    networks:
        - some-network
```