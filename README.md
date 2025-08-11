# DevOps Lab Starters

Quick starters for Docker, Terraform (AWS), and Kubernetes (kind) on WSL2.

## Prereqs
- Docker Desktop (WSL2 backend)
- Ubuntu 22.04 (WSL2)
- awscli, terraform, kubectl, kind

## Docker (Nginx)
```bash
cd docker
docker compose -f nginx-compose.yml up -d
curl -I localhost:8081
