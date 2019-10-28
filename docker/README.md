
## for start LEMP:
```bash
docker-compose up -d --build
docker-compose exec service composer install -vvv
docker-compose exec service php bin/console server:start *:80
```

### for stop LEMP:
`` docker-compose down``