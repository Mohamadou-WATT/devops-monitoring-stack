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
```

## Services

Grafana: http://localhost:3000  
Prometheus: http://localhost:9090  

Default Grafana credentials:

```
user: admin
password: admin
```

## Monitoring Stack

Prometheus collects metrics from the system using Node Exporter.  
Grafana visualizes these metrics through dashboards.

## CI/CD Pipeline

A simple CI pipeline is implemented using GitHub Actions.

```
.github/workflows/ci.yml
```

Each push to the repository automatically triggers the CI pipeline.

## Project Structure

```
devops-monitoring-stack
│
├── docker-compose.yml
├── prometheus
│   └── prometheus.yml
├── .github
│   └── workflows
│       └── ci.yml
└── README.md
```

## Author

Mohamadou Watt  
Master Cybersecurity & Networks
