## Instructions

> 1: create manually the network
```console
docker network create observability 
```

> 2: permissions to config files
```console
chmod go-w heartbeat.yml
```
```console
chmod go-w metricbeat.yml
```
```console
chmod go-w apm-server.yml
```