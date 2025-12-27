# Kubernetes Search Engine Deployment

This project demonstrates deploying an open-source search engine (Meilisearch) on a real multi-node Kubernetes cluster running on AWS.

## Cluster Architecture
- 1 Control Plane Node
- 2 Worker Nodes
- Kubernetes installed using kubeadm
- Container runtime: containerd

## Search Engine
- Meilisearch
- 1 master with 2 replicas

## Deployment

```bash
kubectl apply -f meili.yaml
