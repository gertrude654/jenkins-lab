# Java Application CI/CD Pipeline

This repository contains the CI/CD pipeline for automating the build, test, and deployment processes of a Java application using Jenkins and Docker.

## Overview

The CI/CD pipeline includes:
- **Jenkins Pipeline**: Defines stages for building, testing, and deploying the application.
- **Docker Image**: Containerizes the Java application for consistent deployment.
- **Deployment**: Automates deployment to the target environment.
## Key Components

1. **Jenkinsfile**: The pipeline definition.
2. **Dockerfile**: Instructions for building the Docker image.

## Getting Started

To set up the pipeline:

1. Clone this repository:
   git clone <repository-url>
   cd <repository-directory>
### Document link
https://docs.google.com/document/d/17r41zwE_1z3bA_0VPE5Bh7K1KK54SdaLhgPW7hhON9Y/edit?usp=sharing


# Kubernetes Deployment for Java Application

This section explains how to deploy and manage a Java application on Kubernetes using the Docker image created through the CI/CD pipeline.

## Prerequisites

Ensure you have the following installed and configured:

-**Kubernetes Cluster**: You can use a local Kubernetes cluster (e.g., Minikube) or a cloud-based solution (e.g., Google Kubernetes Engine, AWS EKS).
-**kubectl**: The Kubernetes command-line tool for interacting with the cluster.
-**Docker**: Ensure the application is containerized and the image is available in a Docker registry.
Kubernetes Components
#### 1. Deployment**
The Deployment manages the pods for running your application. It ensures that the desired number of replicas of the application are running.
#### 2. Service**
The Service exposes your application to be accessed externally. In this example, we use a NodePort service, which maps a port on your Kubernetes nodes to your application.

### Document link
https://docs.google.com/document/d/1s6VVu1DRwEtPTa93Apdz9Nq_tC-hSMEknm8cyvKfLJw/edit?usp=sharing
