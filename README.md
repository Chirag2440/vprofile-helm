# vProfile Helm Charts

## Overview

This repository contains Helm charts used to deploy the application on Amazon EKS through ArgoCD following GitOps principles.

## Technologies Used

- Kubernetes
- Helm
- ArgoCD
- Amazon EKS

## Workflow

1. Jenkins updates the Docker image tag.
2. GitHub stores the updated Helm chart.
3. ArgoCD detects the change.
4. ArgoCD synchronizes the application.
5. Kubernetes deploys the updated version.

## Key Features

- Helm chart management
- GitOps deployment
- Automated synchronization
- Kubernetes application deployment

## Learning Outcomes

- Managed Kubernetes applications with Helm.
- Implemented GitOps using ArgoCD.
- Automated deployments from Git.