
# Cloudit Allocation ML

**AI-Powered Multi-Cloud Orchestrator**

Cloudit Allocation ML predicts workload demand and dynamically allocates resources across AWS, Azure, and GCP. By combining machine learning forecasts with Kubernetes orchestration and Terraform provisioning, Cloudit reduces cloud costs, automates deployments, and streamlines multi-cloud management.

---

## 🚀 Features

- **Predictive Scaling**: Uses ML models (TensorFlow/PyTorch) to forecast demand.
- **Multi-Cloud Orchestration**: Unified control of EKS/GKE/AKS via Kubernetes.
- **Automated Provisioning**: Infrastructure-as-code with Terraform.
- **Cost Optimization**: Dynamically shift workloads to the lowest-cost provider.
- **Real-Time Dashboard**: Visualize allocations and forecasts.

---

## 🛠️ Tech Stack

| Layer         | Technologies                             |
| ------------- | ---------------------------------------- |
| Frontend      | React • D3.js • Recharts • Material-UI   |
| Backend       | Node.js • Express • TensorFlow • PyTorch |
| Database      | PostgreSQL • MongoDB • Redis • InfluxDB  |
| Orchestration | Kubernetes • Docker                      |
| IaC           | Terraform                                |
| CI/CD         | GitHub Actions • Jenkins                 |

---

## 💾 Installation

1. **Clone the repo**  
```
bash
git clone https://github.com/your-org/cloudit-allocation-ml.git
cd cloudit-allocation-ml
```
   
3. **Backend Setup**
```
cd backend
npm install
pip install -r requirements.txt
```

3. **Configure environment**
   · Copy ```env.example```

