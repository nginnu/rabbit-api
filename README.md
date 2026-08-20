# Rabbit API Services

Go microservices for the Rabbit e-commerce platform.

## Services

- **notification**: Send email/SMS notifications
- **services**: Contains payment, product, order services

## Getting Started

```bash
make up
```

## Architecture

Multi-service deployment on Kubernetes (kind) with:
- MariaDB for persistent storage
- Redis for caching
- Traefik Gateway for routing
- OTEL collector for observability
