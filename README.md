# Go Microservices

A production-ready Go microservices template with gRPC and REST support.

## Features
- gRPC service definitions with protobuf
- REST API gateway
- Docker multi-stage builds
- Health checks and graceful shutdown
- Structured logging with zerolog
- Configuration via environment variables

## Quick Start
```bash
docker-compose up -d
```

## Architecture
```
api-gateway → user-service (gRPC)
            → order-service (gRPC)
            → notification-service (gRPC)
```

## License
MIT
