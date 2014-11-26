local-server
============

Local development environment

## Dependencies

* Docker
* Fig
* Private Server-Reposistory files in directory `./server/`
* Static content files in directory `./static-content/`

## Usage

```sh
$ fig up
```

## Components

* API-Webserver (HTTPS) - `localhost:1070`
* Static-Webserver - `localhost:1060`
* Mailcatcher-Webinterface - `localhost:1080`
* Supervisor-Webinterface - `localhost:1081`
* Beanstalk-Webinterface - `localhost:1082`
* MySQL-Database - `localhost:3306`
