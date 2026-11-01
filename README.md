# Bhavesh Patil
**SRE / Platform Engineer** · Kubernetes (AKS, GKE) · Terraform · Azure & GCP

I run production Kubernetes for a multi-tenant fintech platform: five environments,
cross-region DR, first-line on-call. Before that, GKE for JioCinema through IPL 2024.

**Now:** preparing for the CKA

### Highlights
- Migrated 21+ microservices from Azure App Services to AKS with zero downtime, cutting infra cost 50%+
- Built cross-region DR (Central India → South India) with Traffic Manager failover
- Cut critical vulnerabilities 90% with blocking DevSecOps gates (SonarQube, Fortify, Black Duck, Trivy)
- Root-caused a cluster-wide AKS outage: API server authorized IP ranges were missing the NAT Gateway egress IP
- Recovered a red Elasticsearch cluster (250 unassigned shards): disks past the high watermark, 3 ES pods packed onto 2 VMs
- Traced Kafka "GC pause" alerts to CPU throttling from leadership skew, not heap

### What I run in production
Kubernetes · Terraform · Kong · Istio · Strimzi Kafka · ECK · Prometheus · Alertmanager · Azure DevOps

[Blog](https://paranerdzops.hashnode.dev/) · [LinkedIn](https://www.linkedin.com/in/bp2000/)
