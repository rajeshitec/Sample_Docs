# Deployment

## CI/CD pipeline

- On push to `main`:
  - Run unit tests
  - Run static analysis
  - Build Docker images
  - Deploy to `dev` automatically
  - Manual approvals for `qa` and `prod`

## Kubernetes

- Minimum 2 replicas per core service
- Horizontal pod autoscaling on CPU and latency

