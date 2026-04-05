# mlops-eks-platform-demo

This project is a simple example of deploying backend services on Kubernetes.

It includes a FastAPI service and a worker, both containerized using Docker and deployed using Kubernetes.

## What it does

- FastAPI API handles requests
- Worker runs background tasks
- Kubernetes manages deployment and scaling

## Tech used

- Python (FastAPI)
- Docker
- Kubernetes
- HPA for scaling

## Structure

- app/        API
- worker/     background service
- docker/     Dockerfiles
- k8s/        Kubernetes configs

## Run locally

uvicorn main:app --reload
