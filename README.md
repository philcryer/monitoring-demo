# monitoring-demo
Monitoring demo using the TICK stack and Grafana on Docker.

## Getting started

* install docker
* install docker-compose
* checkout code
```
git clone https://github.com/philcryer/monitoring-demo.git
```
* change into project directory
```
cd monitoring-demo
```
* run it via docker-compose
```
docker-compose up
```
* watch for errors, if you don't have any, open your browser to [http://127.0.0.1](http://127.0.0.1) and follow the directions.

_NOTE:_ to run this stack in the background, run docker-compose with with the detach flag
```
docker-compose up -d
```


_NOTE_ to run in the background, run docker-compose with with the detach flag
=======
_NOTE_ to run this stack in the background, run docker-compose with with the detach flag
>>>>>>> ccc1d5fd0d40463265105787b12b14898aefbee1
```
docker-compose up -d
```

## Dashboard
In Grafana, get into the Dashboard section, choose `Import` and point to the `grafana-docker-dashboard.json` file to use my base Docker dashboard.
