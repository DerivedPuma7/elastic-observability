## Instructions

> 1: create manually the network
```console
docker network create observability 
```

> 2: permissions to config files
```console
chmod go-w beats/heartbeat/heartbeat.yml
```
```console
chmod go-w beats/metric/metricbeat.yml
```
```console
chmod go-w apm/apm-server.yml
```
```console
chmod go-w nginx/filebeat.yml
```

> 3: start
```console
docker compose up -d
```
```console
cd app
docker compose up -d
```