# BuyGen Backend Architecture

## High-Level Flow

Client → API Gateway → Backend Services

## Architecture Principles
- API Gateway as single entry point
- Database per service
- Synchronous REST communication
- Asynchronous messaging via Kafka (planned)
- Centralized authentication using Keycloak

## Observability
- Metrics via Prometheus
- Dashboards via Grafana
