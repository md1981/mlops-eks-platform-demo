# mlops-eks-platform-demo

Simple FastAPI + worker deployed with Docker and Kubernetes.

## Structure
- app/        API
- worker/     background worker
- docker/     Dockerfiles
- k8s/        Kubernetes manifests

## Run locally
uvicorn app.main:app --reload
