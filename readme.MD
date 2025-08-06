# 🚀 Kubernetes Helm: Roboshop Microservices

This repository contains **Helm charts** to deploy **Roboshop** microservices on a Kubernetes cluster.

✅ Helm-based microservices setup

📦 Project structure

🧪 Deployment steps

🗂️ Install CSI Drivers

🧭 Kubernetes namespace usage

🗃️ EBS StorageClass YAML (ebs-sc.yaml) info


---

## 🔧 What's Included?

Each microservice is packaged into its own Helm chart for modular, reusable deployment.

| 🔢 Service      | 🧠 Purpose                          |
|----------------|-------------------------------------|
| 🗂️ MongoDB      | NoSQL DB for users & products       |
| 🧠 MySQL        | Shipping database                   |
| ⚡ Redis        | In-memory DB for cart               |
| 📨 RabbitMQ     | Message broker for services         |
| 📦 Catalogue    | Manages product APIs                |
| 👤 User         | Handles login/registration          |
| 🛒 Cart         | Stores shopping cart data           |
| 🚚 Shipping     | Shipping details & logistics        |
| 💳 Payment      | Payment processing logic            |
| 🌐 Frontend     | Node.js UI for the app              |

---

Each directory includes:
- `Chart.yaml` – Metadata
- `values.yaml` – Configurable parameters
- `templates/` – Kubernetes manifests (Deployment, Service, etc.)

---

## 📦 Install Services (Using Helm)

```bash
helm upgrade --install <Server name> .
helm list
kubectl get pods

### ✅ This version is:
- Shorter and cleaner
- Table-driven for quick scanning
- Ideal for portfolios, GitHub, or demo projects

Let me know if you'd like:
- 💡 Each chart’s sample `values.yaml`
- 🧵 Integration with CI/CD
- 📊 Diagram of service architecture

I can also generate a **third version** focused only on `developers` or `DevOps deployment automation` if you'd like.
