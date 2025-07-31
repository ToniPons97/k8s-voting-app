# Kubernetes Voting App

This is a deployment of the [Docker Voting App](https://github.com/dockersamples/example-voting-app) using raw Kubernetes manifests.

## Components

- `vote`: Frontend voting app
- `result`: Backend result viewer
- `redis`: Queue
- `db`: PostgreSQL database
- `worker`: Job processor

## Usage

Run with:

```bash
kubectl apply -f .
```