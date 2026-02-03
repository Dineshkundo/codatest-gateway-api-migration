# 🚀 Codatest Cluster Migration  
## NGINX Ingress ➜ Gateway API (Envoy Gateway)

![Kubernetes](https://img.shields.io/badge/Kubernetes-Gateway%20API-blue)
![Envoy](https://img.shields.io/badge/Envoy-Gateway-green)
![Status](https://img.shields.io/badge/Migration-SUCCESS-brightgreen)

---

## 🎯 Objective

Migrate **Codatest Kubernetes cluster** from **NGINX Ingress** to **Gateway API using Envoy Gateway** while:

✅ Preserving the **existing LoadBalancer IP (10.0.8.57)**  
✅ Avoiding DNS changes  
✅ Ensuring zero or near-zero downtime  
✅ Improving routing clarity, security, and scalability  

---

## 🧠 Why Gateway API?

| NGINX Ingress | Gateway API (Envoy) |
|--------------|---------------------|
| Annotation-driven | Strongly typed CRDs |
| Controller-centric | Role-based architecture |
| Hard to scale | Cloud-native & extensible |
| Limited observability | Envoy-level telemetry |

---

## 🏗️ Architecture Overview

### 🔴 BEFORE (Ingress)
