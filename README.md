# 🧩 Multi-Tier DevOps Automation Lab

A **multi-tier web application automation project** demonstrating how to set up and manage a real-world application stack locally using **Infrastructure as Code (IaC)** concepts.

This project automates the provisioning of multiple virtual machines and services using **Vagrant**, **VirtualBox**, and **shell scripting**, providing a solid foundation for DevOps practices such as **automation, orchestration, and CI/CD**.

---

## 🚀 Project Overview

In this project, I automated the setup of a complete multi-service web application stack locally.  
Each virtual machine (VM) runs a specific service such as a web server, application server, caching system, message broker, or database — replicating a production-like architecture.

### **Objective**
- Automate the creation and configuration of virtual machines
- Establish a baseline for future DevOps projects
- Learn how different services in a web stack interact
- Implement Infrastructure as Code (IaC) using **Vagrant**

---

## 🧠 Architecture Overview

### **Services and Components**
| Service | Role | Tool/Technology |
|----------|------|-----------------|
| Load Balancer | Routes traffic to backend | **Nginx** |
| Application Server | Runs the web app | **Tomcat** |
| Message Broker | Handles inter-service communication | **RabbitMQ** |
| Caching Service | Improves performance by caching data | **Memcached** |
| Database | Stores persistent data | **MySQL** |

### **Automation Stack**
| Component | Purpose |
|------------|----------|
| **Vagrant** | Automates VM creation and provisioning |
| **VirtualBox** | Hypervisor for running virtual machines |
| **Git Bash** | Command-line tool for executing scripts |
| **Bash Scripts** | Used to install and configure services |

---

## ⚙️ Execution Flow

1. **Install prerequisites**
   - [Oracle VM VirtualBox](https://www.virtualbox.org/)
   - [Vagrant](https://developer.hashicorp.com/vagrant)
   - [Git Bash](https://git-scm.com/)
   - Text editor (VS Code, Sublime Text, Notepad++)

2. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/multi-tier-devops-lab.git
   cd multi-tier-devops-lab
