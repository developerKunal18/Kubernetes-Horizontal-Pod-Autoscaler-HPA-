# Kubernetes Horizontal Pod Autoscaler

A Kubernetes project demonstrating automatic scaling for a Flask application.

## Features

- Kubernetes Deployment
- Horizontal Pod Autoscaler
- CPU-based scaling
- Health probes
- NodePort Service

## Technologies Used

- Kubernetes
- Flask
- Docker

## Installation

Deploy all resources:

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f hpa.yaml
```
