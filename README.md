# Before90 Infrastructure

| Folder | Purpose |
|--------|---------|
| `docker/` | Service Dockerfiles, compose overrides |
| `kubernetes/` | K8s manifests, Helm charts |
| `terraform/` | Cloud provisioning (AWS/GCP) |
| `monitoring/` | Prometheus, Grafana, alerting |

Local development uses the root `docker-compose.yml` for PostgreSQL 16 and Redis 7.
