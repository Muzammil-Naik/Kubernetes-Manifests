# Kubernetes ReplicaSet Configuration

This repository contains a Kubernetes ReplicaSet configuration file (`replicaset.yaml`) that deploys an NGINX application with multiple pod replicas in a specified namespace.

## Contents

- `replicaset.yaml`: Kubernetes ReplicaSet manifest file

## Prerequisites

- A running Kubernetes cluster (Minikube, EKS, GKE, AKS, etc.)
- `kubectl` configured to interact with your cluster
- Namespace `dev` already created in the cluster

## Usage

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
