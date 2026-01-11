# DevOps Test Task — Reverse proxy + app (Docker Compose) + optional Kind/Kubernetes

## Prereqs
Mandatory:
- Docker Engine
- docker-compose v1 (this repo uses `docker-compose`; Docker Compose v2 plugin is optional)
- curl
- jq (for `make test` output)

Bonus (optional):
- kind
- kubectl
- helm

## Docker Compose (mandatory)

### Setup
```bash
cp .env.example .env
# optionally edit ENV_NAME in .env


