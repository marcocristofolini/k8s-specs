# Kubernetes Specs & Platform Lab

A hands-on Kubernetes reference repository containing manifests, platform experiments and infrastructure examples across multiple areas of the cloud-native stack.

This repository is intentionally broad: it is a **lab and reference workspace** used to explore Kubernetes primitives, networking, delivery, observability, storage and infrastructure automation.

## Repository map

```text
k8s-specs
├── auth/          # authentication and identity examples
├── aws/           # AWS-related Kubernetes resources
├── cd/            # continuous delivery examples
├── certs/         # certificate management
├── charts/        # Helm charts
├── crossplane/    # Crossplane examples
├── grafana/       # dashboards / observability
├── helm/          # Helm examples
├── ingress/       # ingress resources
├── istio/         # service mesh examples
├── linkerd/       # service mesh examples
├── logging/       # logging stack examples
├── mon/           # monitoring
├── network/       # networking resources
├── scaling/       # autoscaling examples
├── storage/       # persistent storage
├── terraform/     # infrastructure as code
└── ...            # Kubernetes workload primitives and supporting resources
```

## Areas covered

- Kubernetes workloads and controllers
- Services and ingress
- ConfigMaps and secrets
- Persistent volumes and storage
- Horizontal scaling
- Networking
- Helm
- Istio and Linkerd
- Monitoring and logging
- Grafana
- Crossplane
- Terraform
- CI/CD experiments
- Cloud-specific examples

## Purpose

The repository is useful as a reference when:

- validating Kubernetes behavior
- reproducing operational scenarios
- testing manifests before production use
- comparing platform components
- exploring service-mesh and networking patterns
- building troubleshooting labs
- preparing reusable platform patterns

## Production use

Examples in this repository should be reviewed before being applied to a production environment.

Production workloads typically require additional consideration for:

- security policies
- resource requests and limits
- disruption budgets
- availability zones and failure domains
- secrets management
- observability
- SLOs and alerting
- backup and disaster recovery
- upgrade strategy

## Engineering direction

The long-term direction of this repository is to become a reproducible **Kubernetes SRE lab**, with scenarios covering failure injection, incident investigation, autoscaling, networking failures and production-readiness validation.

---

Maintained by [Marco Cristofolini](https://github.com/marcocristofolini).
