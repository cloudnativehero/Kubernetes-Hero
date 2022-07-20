# Kubernetes Hero

### Background
- What is Kubernetes?
- The Borg Heritage
### Kubernetes Architecture and Components
- Control Plane
- Nodes
### Deployment Configurations
### Setting up Kubernetes
### Kubernetes Objects
- Workloads
- Services
- Ingress
- Storage
- Configuration
- HPA & VPA
### Add-Ons
- DNS
- Web UI (Dashboard)
- Container Resource Monitoring
- Cluster-level Logging
### Helm
### Managed Kubernetes Services
### Security in Kubernetes
### Understanding Kubernetes Attack Surface
### Cluster Setup and Hardening
- Introduction
- CIS Benchmarks
- CIS benchmark for Kubernetes
- Kube-bench
- Kubernetes Security Primitives
- Authentication
- Article on Setting up Basic Authentication
- Service Accounts
- TLS Introduction
- TLS Basics
- TLS in Kubernetes
- TLS in Kubernetes – Certificate Creation
- View Certificate Details
- Certificates API

### System Hardening
- Introduction
- Least Privilege Principle
- Minimize host OS footprint Intro
- Limit Node Access
- SSH Hardening
- Privilege Escalation in Linux
- Remove Obsolete Packages and Services
- Restrict Kernel Modules
- Identify and Disable Open Ports
- Minimize IAM roles
- Minimize external access to the network
- UFW Firewall Basics
- Linux Syscalls

### Microservices Vulnerabilities
- Introduction
- Security Contexts
- Admission Controllers
- Validating and Mutating Admission Controllers
- Pod Security Policies
- Open Policy Agent
- OPA in Kubernetes
- OPA Gatekeeper in Kubernetes
- Manage Kubernetes secrets
- Container Sandboxing
- gVisor
- kata Containers

### Supply Chain Security
- Introduction
- Minimize base image footprint
- Image Security
- Whitelist Allowed Registries – Image Policy Webhook
- Use static analysis of user workloads (e.g.Kubernetes resources, Docker files)
- Scan images for known vulnerabilities (Trivy)

### Monitoring, Logging and Runtime Security
- Introduction
- Perform behavioral analytics of syscall process
- Falco Overview and Installation
- Use Falco to Detect Threats
- Falco Configuration Files
- Mutable vs Immutable Infrastructure
- Ensure Immutability of Containers at Runtime
- Use Audit Logs to monitor access Service Mesh (Istio)

### Service Mesh Pre-requisites
- Introduction
- Pre-requisites
- Kubernetes Services
- Sidecars
- Envoy

### Istio 
- Introduction
- Monoliths & Microservices
- Service Mesh
#### Istio
- Installing Istio – Introduction
- Installing Istioctl
- Installing Istio on Your Cluster
- Deploying Our First Application on Istio
- Visualizing Service Mesh with Kiali
- Installing Kiali
- Create Traffic Into Your Mesh
#### Traffic Management
- Introduction
- Gateways
- Virtual Services
- Destination Rules
- Gateways
- Virtual Services
- Destination Rules
- Fault Injection
- Timeouts
- Demo: Timeouts
- Retries
- Circuit Breaking
- A/B Testing
#### Security
- Introduction
- Security in Istio
- Istio Security Architecture
- Authentication
- Authorization
- Certificate Management
#### Observability
- Introduction
- Visualizing Metrics with Prometheus and Grafana
- Demo: Visualizing Metrics with Prometheus and Grafana
- Distributed Tracing with Jaeger
- Observability Lab
- Kiali in Detail
- A Quick Note on Service Mesh Interface
 
### Kubernetes on Windows
- The challenges
- Options on Windows
- Installing Docker for Windows With WSL 2 or Hyper-V
- What options do you have for installing Kubernetes on Windows 10?
- Installing Kubernetes on Windows Minikube
- Installing WSL 2
- Installing Chocolatey Migration K8 On-Premise to Cloud

### Migrate K8 On-Premise to Cloud
- Use-Cases