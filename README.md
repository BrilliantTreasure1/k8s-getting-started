# Kubernetes Getting Started with Minikube

Welcome to this hands-on repository designed to help you learn and practice Kubernetes basics using Minikube on a local machine.

---

## 🚀 What You Will Learn

- Setting up a local Kubernetes cluster using Minikube
- Managing Pods, Deployments, and Services with `kubectl`
- Understanding and practicing core Kubernetes concepts like scaling, rolling updates, and service types
- Writing and applying Kubernetes manifests in YAML format
- Using ConfigMaps and Secrets (upcoming)
- Debugging and inspecting Kubernetes resources
- Accessing your deployed applications via NodePort and Minikube service

---

## 📅 Learning Progress Overview

| Day | Topic                          | Commands & Concepts                                  |
|------|--------------------------------|-----------------------------------------------------|
| 1    | Minikube installation & start | `minikube start`, `kubectl cluster-info`            |
| 2    | Pods and basic operations      | `kubectl run`, `kubectl get pods`, `kubectl logs`    |
| 3    | Deployments and Services       | `kubectl create deployment`, `kubectl scale`, `kubectl expose` |
| 4    | ConfigMaps and Secrets         | Defining, mounting as env variables or files         |
| 5    | YAML files and resource management | `kubectl apply -f`, `kubectl describe`, `kubectl delete` |

---

## ⚙️ How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/k8s-getting-started.git
   cd k8s-getting-started
Follow the exercises day by day. Each day contains:

Step-by-step instructions

Sample YAML manifests

Useful kubectl commands

Apply manifests to your Minikube cluster:

bash
Copy
Edit
kubectl apply -f day3-deployment.yaml
Inspect your cluster’s resources and logs to understand what’s happening.

🛠️ Prerequisites
Minikube installed

kubectl command-line tool installed

Docker installed and running (for Minikube Docker driver)

Basic knowledge of containers and command-line operations

🤝 Contributing
Feel free to open issues, suggest improvements, or submit pull requests!
If you find this repository helpful, please ⭐️ it and share with others.

📬 Connect with Me
I’m always open to discuss Kubernetes, DevOps, and Cloud Native technologies.
Let’s connect and grow together!
LinkedIn | Twitter

📜 License
This repository is licensed under the MIT License. See the LICENSE file for details
