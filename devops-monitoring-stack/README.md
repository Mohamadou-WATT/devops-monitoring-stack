# DevOps Monitoring Stack

This project demonstrates a simple **DevOps monitoring stack** using Docker.

## Technologies

- Docker
- Prometheus
- Grafana
- Node Exporter
- GitHub Actions (CI/CD)

## Architecture

Application → Node Exporter → Prometheus → Grafana

Prometheus collects metrics from the system and Grafana visualizes them through dashboards.

## Run the project

Start the monitoring stack:

```bash
docker compose up -d

![Grafana Dashboard](images/grafana-dashboard.png)

