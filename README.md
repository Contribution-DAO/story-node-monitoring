# Story Node Monitoring
this repository contains the code and configuration for monitoring Story blockchain nodes. The monitoring setup is designed to ensure the reliability and availability of the nodes by providing real-time insights

## Features
- **Node Health Monitoring:** Tracks the health and status of Story blockchain nodes
- **Performance Metrics:** Collects key metrics such as CPU, memory, and disk usage.
- **Grafana Dashboard:** Visualizes metrics with pre-build Grafana dashboards.
- **Prometheus integration:** Gathers metrics using Prometheus for robust data collection and storage.

## Prerequisites
- Docker
- Docker Compose
- Access to a Story blockchain node
- Access to a Story Geth node

## Configuration
1. **Prometheus Configuration:** Modify the prometheus.yml file to include the target IP addresses and Port of you Story nodes.
2. **Grafana Configuration:** Modify the env file for change the Grafana username/password

## Start the service
```
docker compose up -d
```

