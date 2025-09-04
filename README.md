# Argo

This repository serves as a collection of proofs of concept (PoCs) for various Argo projects, including Argo CD, Argo Workflows, Argo Events, and Argo Rollouts. Each PoC is designed to demonstrate a specific use case or feature, helping to explore the capabilities of the Argo ecosystem.

## What is Argo?

Argo is a suite of open-source tools for Kubernetes that simplifies application deployment, management, and orchestration. The primary projects are:

- Argo CD: A declarative, GitOps continuous delivery tool.

- Argo Workflows: A workflow engine for orchestrating parallel jobs on Kubernetes.

- Argo Events: An event-based dependency manager for Kubernetes.

- Argo Rollouts: A controller that provides advanced deployment strategies like blue-green, canary, and A/B testing.

### Prerequisites

- kubectl (Kubernetes command-line tool)

- A running Kubernetes cluster

- Helm (optional, but recommended)

- The relevant Argo CLI tools (e.g., argocd, argo)