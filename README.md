# Docker Compose Wordpress Dev

A simple docker compose deployment for local wordpress development. 

Nginx, MariaDB, PHPFPM with FastCgi Caching

Preinstalls most common used plugins and themes and mounts `/var/www/html` locally for ease of development with IDEs.

## Install

Clone the repository to a directory
```
gh repo clone eric-mathison/dockercompose-wordpress-dev
```

## Usage

```
docker-compose up
```

Connect using `http://localhost`
