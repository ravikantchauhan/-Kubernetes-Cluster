# Installing Kubernetes Cluster on Ubuntu 22.04

## Introduction

Kubernetes is a powerful container orchestration platform used for automating the deployment, scaling, and management of containerized applications. This guide will walk you through the step-by-step process of installing Kubernetes on Ubuntu 22.04. The cluster configuration includes a master node and worker nodes, allowing you to harness the full power of Kubernetes.

## Kubernetes Nodes

In a Kubernetes cluster, you will encounter two distinct categories of nodes:

- **Master Nodes**: These nodes play a crucial role in managing the control API calls for various components within the Kubernetes cluster.
  
- **Worker Nodes**: Worker nodes are responsible for providing runtime environments for containers. They host the actual applications.

## Prerequisites

Before diving into the installation, ensure that your environment meets the following prerequisites:

- An Ubuntu 22.04 system.
- Privileged access to the system (root or sudo user).
- Active internet connection.
- Minimum 2GB RAM or more.
- Minimum 2 CPU cores (or 2 vCPUs).
- 20 GB of free disk space on /var (or more).

## Step-by-Step Installation Guide

### Step 1: Update and Upgrade Ubuntu (all nodes)

```bash
sudo apt update
sudo apt upgrade
