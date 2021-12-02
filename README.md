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

## References

https://github.com/danguita/prometheus-monitoring-stack/edit/master/README.md
https://github.com/PagerTree/prometheus-grafana-alertmanager-example#datasource-configuration
https://github.com/docker/awesome-compose/tree/master/nginx-golang
https://git.web.rug.nl/HPC/prometheus
https://awesome-prometheus-alerts.grep.to/rules.html#docker-containers
https://dev.to/ablx/minimal-prometheus-setup-with-docker-compose-56mp
https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/
https://github.com/Einsteinish/Docker-compose-Nginx-Reverse-Proxy
