# Real GitHub Project Structure

### flask-voting-app

```bash
aws-flask-voting-devops-project/

├── terraform/
│   ├── provider.tf
│   ├── vpc.tf
│   ├── ec2.tf
│   ├── ecr.tf
│   ├── variables.tf
│   └── outputs.tf
│
├── docker/
│   ├── vote/
│   ├── worker/
│   └── result/
│
├── kubernetes/
│   ├── vote-deployment.yaml
│   ├── redis-deployment.yaml
│   ├── worker-deployment.yaml
│   ├── postgres-deployment.yaml
│   ├── result-deployment.yaml
│   ├── ingress.yaml
│   └── helm-chart/
│
├── monitoring/
│   ├── prometheus-values.yaml
│   └── grafana-values.yaml
│
├── cicd/
│   └── github-actions.yml
│
├── scripts/
│   ├── install-docker.sh
│   ├── install-k3s.sh
│   └── install-helm.sh
│
└── README.md
```
🧱 Infrastructure You Will Create (Terraform)

Terraform will create:

VPC
Public Subnet
Internet Gateway
Route Table
Security Group
EC2 Instance (t3.medium)
Elastic IP
ECR Repositories

This is real cloud engineering.

🔁 CI/CD Pipeline Workflow

Using GitHub Actions

Push Code
    ↓
Build Docker Images
    ↓
Push Images → AWS ECR
    ↓
Deploy to Kubernetes
    ↓
Verify Deployment

This demonstrates:

✅ Continuous Integration
✅ Continuous Deployment

📊 Monitoring Stack Deployment

Deploy via Helm:

Prometheus
Grafana
Node Exporter
Alertmanager

Dashboards will show:

CPU usage
Memory usage
Pod health
Node metrics

These screenshots are very powerful in interviews.

🧪 Kubernetes Objects You Will Create
Deployments
Services
Ingress
ConfigMaps
Secrets
Horizontal Pod Autoscaler

This makes your Kubernetes knowledge look real.