# Court Case Management System (CCMS) – Production Deployment Guide

This repository provides the full production-grade deployment documentation for the CCMS application using:

- Kubernetes (RKE2 or K3s or RKE1)
- Rancher 2.x (Cluster Management)
- CloudNativePG (CNPG) Operator for PostgreSQL
- MinIO Operator for S3-compatible object storage
- HAProxy Load Balancers
- GitHub Actions CI/CD
- Ingress-NGINX

This documentation covers VM layout, networking, storage, deployment, CI/CD, and operational procedures.

## Directory Overview

- **architecture/**: High-level system design and network topology.
- **infrastructure/**: Server/VM setup, HAProxy, Kubernetes, CNPG, MinIO.
- **deployment/**: Deploying the CCMS application, ingress, namespaces, GitHub Actions.
- **operations/**: Backup/restore, scaling, security, and DR.

## Audience

DevOps Engineers, System Engineers, and Software Engineers working on OCCMS infrastructure and Kubernetes-based deployments.

