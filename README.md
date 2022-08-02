# docker-monitoring-grafana-prometheus-influxdb-cadvisor

# 🚀 Docker-Monitoring based on Cadvisor, InfluxDB, and Grafana 🚀

https://github.com/coding-to-music/docker-monitoring-grafana-prometheus-influxdb-cadvisor

From / By Brian Christner https://github.com/vegasbrianc

https://github.com/vegasbrianc/docker-monitoring

https://brianchristner.io/how-to-setup-docker-monitoring/

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/docker-monitoring-grafana-prometheus-influxdb-cadvisor.git
git push -u origin main
```

## Results

cAdvisor http://localhost:8080/containers/

Grafana http://localhost:3000 (Dashboard yml files (2) - need to paste them in manually - could add them via docker-compose)

https://brianchristner.io/how-to-setup-docker-monitoring/ (2015 article - Shows views of the 2 available dashboards.)

json files of the two dashboards are available in the repo

Note they are from a legacy version of Grafana (2? 3?) and now there is a time-series chart-type and so the manual queries are allowed but old.

Work item: They could be added automatically via the docker compose

## Docker Monitoring Grafana JSON Dashboard

[![Build Status](https://travis-ci.org/vegasbrianc/docker-monitoring.svg?branch=master)](https://travis-ci.org/vegasbrianc/docker-monitoring)

After publishing the article for Docker Monitoring based on cAdvisor, InfluxDB, and Grafana the request came up to share the Grafana Dashboards that were referenced in the article - [Docker Monitoring Article](https://www.brianchristner.io/how-to-setup-docker-monitoring/)

Please take a look a the Docker-Monitoring-xx.json file to view the Grafana Dashboard's json file and check out the queries folders for screenshots of the queries in each graph.

Also added the docker-compose.yml file to easily stand up the entire Monitoring Stack.

![Docker Grafana Monioring Dashboard](https://raw.githubusercontent.com/vegasbrianc/docker-monitoring/master/Docker_Monitoring.png)
