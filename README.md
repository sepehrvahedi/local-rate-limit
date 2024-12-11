# User-Based Rate Limiting System

Enterprise-grade rate limiting solution for microservice architectures.

## Core Features
- Uses envoy Proxy to limit the requests
- User-based traffic control
- Token bucket algorithm implementation
- Istio service mesh integration
- Real-time traffic monitoring

## Tech Stack
- Envoy Proxy
- Istio Service Mesh
- Lua
- Docker
- Kubernetes

## Architecture
- Distributed rate limiting
- Microservice-level control
- Token-based user identification
- Configurable rate limits

## Versions

- V1
This version limits all requests and does not filter any certain API
- V1.1
This version limits the APIs given to it

## License
MIT License
