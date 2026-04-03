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