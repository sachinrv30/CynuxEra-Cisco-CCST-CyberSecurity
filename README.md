# 🛡️ CynuxEra Cisco CCST CyberSecurity Laboratory

An enterprise-grade network simulation and penetration testing environment developed as part of the Cisco Certified Support Technician (CCST) Cybersecurity Skill Development Program. This repository serves as the central documentation hub for the infrastructure architecture, security configurations, and deployment guidelines.

---

## 🖥️ Lab Infrastructure & Virtual Machines

> ⚠️ **Storage & Deployment Notice:** The core virtual machine environments for this project total **2.22 GB** and contain pre-configured network topologies, firewall rules, and security appliances. Due to GitHub's file size limitations, the active `.ovf`, `.mf`, and `.vmdk` files are hosted via a secure mirror.

### 📥 Enterprise Deployment Package
You can access and download the fully compiled laboratory directory here:
👉 **[Click Here to Access the Project Storage Hub on Google Drive](https://drive.google.com/drive/folders/1x0A_VAqLpz_9GvyX2oYmsNqW089uk0Ta?usp=sharing)**

### 📦 Virtual Appliance Directory
*   **🥷 WestWild Node:** Advanced penetration testing suite and routing node configured to simulate external/internal attack vectors.
*   **🎯 Dhanush Target Machine:** A deliberately vulnerable training target deployed to evaluate exploit vectors and security posture.
*   **🽈 Server Base:** The central log management, directory services, and endpoint defense infrastructure hub.

---

## 📝 Skill Development Program (SDP) Executive Report

### 1. 🎯 Project Objectives
The objective of this deployment is to engineer a sandboxed enterprise environment to test real-world defensive and offensive cybersecurity principles aligned with the Cisco CCST framework. This includes validating firewall access-control lists, monitoring malicious traffic payloads, and auditing log irregularities.

### 2. 🛡️ Implemented Security Controls & Methodologies
*   **🌐 Network Segmentation:** Isolated routing domains using dedicated virtual interfaces to prevent lateral movement during simulated breaches.
*   **🔍 Vulnerability Management:** Mapping target nodes using specialized discovery toolkits to detect legacy services, weak authentication protocols, and unpatched daemons.
*   **🪵 Endpoint & Log Auditing:** Hardening core operating systems and tracking event streams to establishing baseline telemetry for threat detection.

### 3. 🚀 Engineering Outcomes
The laboratory effectively validated security policies against a variety of network threats. Future iterations of this project will integrate automated intrusion prevention mechanisms (IPS) and centralized Security Information and Event Management (SIEM) pipelines.
