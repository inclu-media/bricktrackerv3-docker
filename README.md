Bricktracker V3 Docker Commands
===============================
Martin Melcher <martin@inclumedia.at>

DEV Environment
---------------

```
$ docker-compose -f docker-compose.yml -f docker-compose.dev.yml build
$ docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d
$ docker-compose -f docker-compose.yml -f docker-compose.dev.yml stop
```

PROD Environment
----------------

Connecting

```
$ ssh -i "btv3-keypair.pem" ec2-user@52.21.77.232
```

Getting Docker Config

```
$ git clone https://github.com/inclu-media/bricktrackerv3-docker.git
```

Running

```
$ docker-compose build
$ docker-compose up -d
$ docker-compose stop
```