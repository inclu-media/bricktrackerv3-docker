Bricktracker V3 Docker Commands
===============================
Martin Melcher <martin@inclumedia.at>

DEV Environment
---------------

```
> docker-compose -f docker-compose.yml -f docker-compose.dev.yml build
> docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d
> docker-compose -f docker-compose.yml -f docker-compose.dev.yml stop
```

PROD Environment
----------------

```
> docker-compose build
> docker-compose up -d
> docker-compose stop
```