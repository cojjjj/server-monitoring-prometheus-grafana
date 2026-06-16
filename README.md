# Server Monitoring with Prometheus and Grafana

This project demonstrates a complete monitoring solution using Prometheus and Grafana for collecting, visualizing, and analyzing system metrics.

## Features

* Prometheus metric collection
* Grafana dashboards
* Node Exporter system metrics
* Nginx application monitoring
* CPU monitoring
* Memory monitoring
* Disk monitoring
* Network monitoring

## Architecture

Client
|
v
Grafana
|
v
Prometheus
|
+--> Node Exporter
|
+--> Nginx Application

## Running the Project

Start the stack:

```bash
docker compose up -d
```

Access Grafana:

```text
http://localhost:3000
```

Access Prometheus:

```text
http://localhost:9090
```

Access Nginx:

```text
http://localhost:8080
```

## Prometheus Configuration

The monitoring stack uses a 15-second scrape interval and collects metrics from:

* Prometheus
* Node Exporter

## Concepts Demonstrated

* Infrastructure Monitoring
* Observability
* Metrics Collection
* Grafana Dashboards
* Prometheus
* Node Exporter
* DevOps Fundamentals

## Project URL

https://github.com/cojjjjj/server-monitoring-prometheus-grafana

