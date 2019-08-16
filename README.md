## FuelPHP Development With Docker Compose and Machine

Featuring:

- Docker v1.11.2
- Docker Compose v1.7.1
- Docker Machine v0.7.0
- PHP 5.6.29
- FuelPHP 1.8

### OS X Instructions

1: Create FuelPHP New Project
```
$ curl https://get.fuelphp.com/oil | sh
$ oil create fuel_project
```

2: Start services for development
```
$ docker-compose up --build
```

3: Grab IP - `docker-machine ip default` - and view in your browser
