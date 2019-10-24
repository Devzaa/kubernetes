# kubernetes
Kubernetes Dashboard

Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters. It allows users to manage applications running in the cluster and troubleshoot them, as well as manage the cluster itself.

Getting Started
IMPORTANT: Read the Access Control guide before performing any further steps. The default Dashboard deployment contains a minimal set of RBAC privileges needed to run.

To deploy Dashboard, execute following command:

$ kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v1.10.1/src/deploy/recommended/kubernetes-dashboard.yaml
