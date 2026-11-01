# Bhavesh Patil
**SRE / Platform Engineer** · Kubernetes (AKS, GKE) · Terraform · Azure & GCP

I run production Kubernetes for a multi-tenant fintech platform: five environments,
cross-region DR, first-line on-call. Before that, GKE for JioCinema through IPL 2024.

### Things that broke, and what I learned
- [An Elasticsearch cluster went red and the autoscaler never noticed](link): ECK, soft anti-affinity, disk watermarks
- [An API server allowlist that locked out its own nodes](link): AKS authorized IP ranges vs NAT Gateway egress
- [Kafka "GC pauses" that were really CPU throttling](link): Strimzi, leadership skew

### Things you can run
- [terraform-azurerm-aks-platform](link): private AKS, App Gateway + WAF, NAT Gateway, tested in CI
- [k8s-failure-labs](link): the incidents above, reproduced on kind
- [aks-cni-ip-planner](link): how many IPs your Azure CNI subnet actually needs

### What I run in production
Kubernetes · Terraform · Kong · Istio · Strimzi Kafka · ECK · Prometheus · Alertmanager · Azure DevOps

[Blog](https://paranerdzops.hashnode.dev/) · [LinkedIn](https://www.linkedin.com/in/bp2000/)
