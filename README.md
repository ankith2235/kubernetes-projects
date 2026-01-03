# Kubernetes Assignment – 5 Projects

This repository contains Kubernetes assignments completed as part of my Cloud & DevOps training. These projects demonstrate hands-on experience with Kubernetes cluster setup, deployments, scaling, services, and service-to-service communication.

---

## 🔹 Project 1: Kubernetes Cluster Setup & NGINX Deployment
**Tasks Performed:**
1. Deployed a Kubernetes cluster with **3 nodes**
2. Created an **NGINX deployment** with **3 replicas**
3. Verified pod status and replica distribution across nodes

---

## 🔹 Project 2: Exposing NGINX Deployment Using NodePort
**Tasks Performed:**
1. Used the existing NGINX deployment
2. Created a Kubernetes **Service of type NodePort**
3. Accessed the application via browser using the NodePort
4. Verified external connectivity to the NGINX service

---

## 🔹 Project 3: Scaling the NGINX Deployment
**Tasks Performed:**
1. Used the existing NGINX deployment
2. Scaled the deployment replicas from **3 to 5**
3. Verified the new pods were running successfully

---

## 🔹 Project 4: Changing Service Type to ClusterIP
**Tasks Performed:**
1. Used the existing NGINX deployment
2. Modified the service type from **NodePort to ClusterIP**
3. Verified internal cluster access to the service

---

## 🔹 Project 5: Service-to-Service Communication Using Ingress / Proxy
**Tasks Performed:**
1. Used the existing Kubernetes deployment
2. Deployed an additional **NGINX deployment** with **3 replicas**
3. Created an **NGINX service of type ClusterIP**
4. Configured **Ingress / Apache-to-Apache / NGINX-to-NGINX** service routing
5. Verified successful service-to-service communication

---

## 🛠 Tools & Technologies Used
- Kubernetes  
- Docker  
- Amazon Web Services (AWS) – EC2  
- Linux  
- Git & GitHub  

---

## 🎯 Summary
These projects provided practical experience in Kubernetes workload management, scaling applications, exposing services, and implementing internal and external traffic routing using Kubernetes services and ingress mechanisms.
