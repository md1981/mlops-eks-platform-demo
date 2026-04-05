# mlops-eks-platform-demo

<<<<<<< HEAD
Simple FastAPI + worker deployed with Docker and Kubernetes.

## Structure
- app/        API
- worker/     background worker
- docker/     Dockerfiles
- k8s/        Kubernetes manifests

## Run locally
uvicorn app.main:app --reload
=======
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

app/        API  
worker/     background service  
docker/     Dockerfiles  
k8s/        Kubernetes configs  

## Run locally

uvicorn app.main:app --reload

## Note

This is a simplified version of a larger system built using Kubernetes, CI/CD, and cloud infrastructure.
>>>>>>> 3d1700f853b07643bf22cc982cf7fa589530e340
