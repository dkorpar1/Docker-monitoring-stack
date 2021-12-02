# Docker-monitoring-stack

📈 A simple, single-node, Docker-based Prometheus monitoring stack

## Stack overview

- [Prometheus server](https://prometheus.io/docs/introduction/overview/)
- Prometheus [Alertmanager](https://prometheus.io/docs/alerting/alertmanager/)
- [Grafana](http://grafana.org/) for visualization
- Nginx reverse proxy 
- Forward alerts to Teams (WIP)

## Features

- Well known monitoring stack.
- Almost no configuration.
- Minimal requirements.
- High portability.

## Requisites

Only Docker and Docker compose are required to build the entire stack.
Check out the [installation instructions](https://docs.docker.com/compose/install/).

## Installation and usage

From the root directory of this repo, run the command below:

```shell
$ docker-compose up -d
```

