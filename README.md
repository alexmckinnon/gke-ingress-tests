# GKE Ingress Tests

This repo contains a basic deployment with ingress and SSL certificate in order to test issues with GCP load balancer serving wrong certificates.

Deployments of ingress resources with no modifications is triggering setSslCertificate events, sometimes resulting in load balancers serving requests with incorrect SSL certificates.

