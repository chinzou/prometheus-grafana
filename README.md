# Prometheus & Grafana

Prometheus and Grafana server to explore dumped prometheus snapshot

### Requirements
- docker
- docker-compose

### Guide

- Place the content of the snapshot folder (usually named "`<date>-<16digits>`") in `metrics/`
- Make sure the folder have the right permissions
```
sudo chwon root:root -R metrics/*
```
- run the services
```
docker-compose up
```

Grafana should be accessible through: http://localhost:3000