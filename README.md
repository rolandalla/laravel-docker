# laravel-docker
Docker Configuration for Laravel, using : php , redis, nginx, mysql, phpmyadmin, selenium, laravel workspace
---
1- Run Docker:
```
cd docker
docker-compose up -d 
```

2-Update projects  .env to:
```
DB_HOST=mysql
REDIS_HOST=redis
QUEUE_HOST=beanstalkd
```
3- User Docker workspace for artisan commands
```
cd docker
docker-compose exec workspace bash
```

4- Use phpmyAdmin
Go to: 127.0.0.1:8080
use: mysql , root, root
