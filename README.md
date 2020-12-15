# GKE Ingress Tests

This repo contains a basic deployment with ingress and SSL certificate to use for some testing in GCP.

### Minikube

```
❯ minikube start --vm=true

❯ minikube addons enable ingress

❯ kubectl apply -f namespace.yaml

❯ krane deploy alex-gke-ingress-test minikube -f deploy

```