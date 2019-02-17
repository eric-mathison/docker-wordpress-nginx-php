# docker-wordpress-nginx-php

A docker compose build for local wordpress development. 

Nginx, MariaDB, PHPFPM with FastCgi Caching

Preinstalls most common used plugins and themes and mounts ```/var/www/html``` locally for ease of development with IDEs.

## Install

Clone the repository to a directory
```
git clone https://github.com/eric-mathison/docker-wordpress-nginx.php.git
```

## Usage

```
docker-compose up
```

Connect using ```http://localhost```
