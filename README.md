# Hi, I'm Mohamed Gamal 👋

### Systems & Cloud Engineer | System Administration | Cloud & DevOps

**Linux • Windows Server • AWS • Terraform • Ansible • Docker • Kubernetes • CI/CD**

I build and automate **reliable, scalable, and highly available infrastructure** across cloud and enterprise environments, with a focus on system administration, infrastructure automation, containerization, monitoring, and continuous improvement.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Gamal-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/mohamed-gamal546)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:m.nasser5466@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-mohamedgamal546-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/mohamedgamal546)

📍 Cairo, Egypt

---

## 👨‍💻 About Me

I'm a **Systems & Cloud Engineer** with a background in **Electronics & Communications Engineering** and intensive systems administration training through **ITI – MCIT**.

My engineering work covers the infrastructure lifecycle:

**Design → Provision → Configure → Deploy → Automate → Monitor → Troubleshoot**

My main areas of experience include:

* 🐧 **Linux & System Administration**
* 🪟 **Windows Server & Active Directory**
* ☁️ **Cloud Infrastructure** — AWS, GCP, Azure, Huawei Cloud
* 🏗️ **Infrastructure as Code** — Terraform
* ⚙️ **Automation & Configuration Management** — Ansible, Bash, Python
* 🐳 **Containers & Orchestration** — Docker, Docker Compose, Kubernetes, Helm, ArgoCD
* 🔄 **CI/CD** — Jenkins, GitHub Actions
* 🖥️ **Virtualization** — VMware vSphere
* 🌐 **Networking** — TCP/IP, DNS, DHCP, Routing & Switching
* 📊 **Monitoring & Observability** — Prometheus, Grafana
* 🗄️ **Databases** — MySQL, SQL, PL/SQL, Backup & Recovery

---

# 🚀 Featured Projects

## ☁️ Highly Available 3-Tier AWS Infrastructure

[**View Project →**](https://github.com/mohamedgamal546/Highly-Available-3-Tier-AWS-Infrastructure-)

`AWS` `Terraform` `Ansible` `Docker` `ECR` `EC2` `ALB` `RDS` `SSM` `IAM` `Secrets Manager` `GitHub Actions`

Production-style **highly available 3-tier AWS infrastructure** designed around automation, scalability, secure operations, and fault tolerance.

### Architecture

```text
                         Internet
                            │
                            ▼
                  Application Load Balancer
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
             EC2 / ASG              EC2 / ASG
              AZ-1                    AZ-2
                 │                     │
                 └──────────┬──────────┘
                            ▼
                    RDS MySQL Multi-AZ
```

### Engineering Highlights

* Engineered a **multi-AZ 3-tier AWS architecture** using Terraform
* Designed a custom **VPC with public and private subnets**
* Deployed a public **Application Load Balancer**
* Deployed private **EC2 application infrastructure**
* Implemented **RDS MySQL Multi-AZ** for database high availability
* Containerized workloads using **Docker**
* Managed container images with **Amazon ECR**
* Automated Linux configuration and deployment using **Ansible**
* Used **AWS Systems Manager Session Manager** for secure instance access
* Implemented **IAM and AWS Secrets Manager** for secure access and credential management
* Built **GitHub Actions CI/CD** with AWS OIDC
* Automated testing, image delivery, deployment, and health validation

**Key Concepts:**
`High Availability` • `AWS Networking` • `Infrastructure as Code` • `Automation` • `Containerization` • `Security` • `Fault Tolerance`

---

## 🚗 Edge Autonomous Driving System with DevOps Integration

[**View Project →**](https://github.com/mohamedgamal546/Edge-Autonomous-Driving-System-with-DevOps-Integration)

`Raspberry Pi 4` `Python` `OpenCV` `MQTT` `Docker` `Docker Compose` `Ansible` `GitHub Actions` `Prometheus` `Grafana`

A production-style **edge computing and autonomous driving system** combining computer vision, IoT communication, containerization, automation, CI/CD, and monitoring.

### Engineering Highlights

* Designed and deployed a **Dockerized microservices platform** on Raspberry Pi 4
* Used **Docker Compose** for service orchestration
* Implemented inter-service communication using **MQTT**
* Integrated computer vision using **OpenCV**
* Built multi-architecture CI/CD workflows with **GitHub Actions**
* Automated deployment to Raspberry Pi using **Ansible**
* Implemented monitoring using **Prometheus and Grafana**
* Added health checks, custom metrics, and automated dashboards

**Key Concepts:**
`Edge Computing` • `IoT` • `Computer Vision` • `Microservices` • `DevOps` • `Observability`

---

## 🖥️ VMware vSphere Enterprise Infrastructure

[**View Project →**](https://github.com/mohamedgamal546/VMware-vSphere-Enterprise-Infrastructure)

`VMware vSphere` `ESXi` `vCenter` `HA` `DRS` `vMotion` `Fault Tolerance` `NFS`

Enterprise virtualization infrastructure built using **nested virtualization**, focusing on availability, resource management, networking, storage, and centralized administration.

### Engineering Highlights

* Designed and implemented a VMware vSphere environment with **vCenter Server and two ESXi hosts**
* Configured **High Availability (HA)** and **Distributed Resource Scheduler (DRS)**
* Implemented **vMotion** for live virtual machine migration
* Designed dedicated management, VM, and vMotion networks
* Configured shared **NFS storage**
* Validated resilience through **ESXi host-failure simulation**
* Tested VM failover, live migration, and **Fault Tolerance (FT)**

**Key Concepts:**
`Virtualization` • `High Availability` • `Resource Management` • `Virtual Networking` • `Shared Storage`

---

## 🪟 Enterprise Windows Server Infrastructure

[**View Project →**](https://github.com/mohamedgamal546/Enterprise-Windows-Server-Infrastructure)

`Windows Server` `Active Directory` `AD DS` `DNS` `DHCP` `GPO` `RRAS` `File Services`

Enterprise Windows Server environment focused on **identity management, network services, centralized administration, security, and file services**.

### Engineering Highlights

* Designed a multi-domain Windows Server environment
* Implemented **Active Directory Domain Services (AD DS)**
* Configured domain controllers, OUs, centralized user management, and delegated access control
* Configured **DHCP, Group Policy, and File Services**
* Implemented NTFS and share permissions with department-based security controls
* Configured **RRAS VPN**
* Validated domain replication, authentication, DHCP, and file access

**Key Concepts:**
`Active Directory` • `DNS` • `DHCP` • `Group Policy` • `RRAS` • `File Services` • `Access Control`

---

## 🔄 Java CI/CD Pipeline Project

[**View Project →**](https://github.com/mohamedgamal546/Java-CI-CD-Pipeline-Project-)

`Java` `Maven` `Docker` `Jenkins` `Azure DevOps` `Git`

CI/CD project demonstrating automated application build, testing, containerization, and source-control integration.

### Engineering Highlights

* Containerized a Java application using **Maven and Docker**
* Configured CI/CD pipelines using **Jenkins and Azure DevOps**
* Automated application build and testing workflows
* Integrated Git-based source control
* Automated Docker image build processes

**Key Concepts:**
`CI/CD` • `Build Automation` • `Containerization` • `Git` • `Jenkins`

---

## 🌦️ Modern Containerized Weather Application

[**View Project →**](https://github.com/mohamedgamal546/modern-devops-weather-app)

`Docker` `Docker Compose` `MySQL` `Microservices`

Modern containerized application demonstrating multi-service deployment and Docker-based infrastructure management.

### Engineering Highlights

* Built and orchestrated UI, Authentication, Weather, and MySQL services using **Docker Compose**
* Configured container networking and service discovery
* Implemented environment-based configuration
* Configured persistent MySQL storage using **Docker Volumes**
* Secured application credentials through environment variables
* Excluded sensitive `.env` files from Git version control

**Key Concepts:**
`Docker Compose` • `Microservices` • `Container Networking` • `Persistent Storage` • `Configuration Management`

---

# 🧰 Technical Toolkit

| Area                              | Technologies                                                                     |
| --------------------------------- | -------------------------------------------------------------------------------- |
| 🐧 **System Administration**      | Linux Admin I & II • Windows Server • VMware vSphere • Apache • Nginx • Storage  |
| ☁️ **Cloud Platforms**            | AWS • GCP • Microsoft Azure • Huawei Cloud                                       |
| 🏗️ **Infrastructure as Code**    | Terraform                                                                        |
| ⚙️ **Automation**                 | Ansible • Bash • Python                                                          |
| 🐳 **Containers & Orchestration** | Docker • Docker Compose • Kubernetes • Helm • ArgoCD                             |
| 🔄 **CI/CD**                      | Jenkins • GitHub Actions • Git • GitHub • YAML                                   |
| 📊 **Monitoring**                 | Prometheus • Grafana                                                             |
| 🌐 **Networking**                 | TCP/IP • Subnetting • Routing & Switching • DNS • DHCP • Network Troubleshooting |
| 🗄️ **Databases**                 | MySQL • SQL • PL/SQL • Backup & Recovery                                         |
| 💻 **Programming & Scripting**    | Bash • Python • Go                                                               |

---

# 🏆 Certifications & Training

### Certifications

🎖️ **Red Hat Certified System Administrator — RHCSA**

☁️ **Huawei HCCDA — Cloud Native**

☁️ **Huawei HCCDA — Tech Essentials**

### Networking

🌐 **CCNA — Introduction to Networks**

🌐 **CCNA — Switching, Routing, and Wireless Essentials**

🌐 **CCNA — Enterprise Networking, Security, and Automation**

---

# 🎓 Education

### Information Technology Institute — ITI / MCIT

**Intensive Code Camps (ICC) — Systems Administration Track**
January 2026 – June 2026

Focus areas:

`Linux` • `Windows Server` • `Networking` • `Cloud` • `Virtualization` • `Containers` • `Automation`

---

### National Technology Institute — NTI

**Digital Egypt Youth (DEY) — Cloud Service Management and Operations**
November 2025 – January 2026

---

### Sinai University

**B.Sc. in Electronics and Communications Engineering**
October 2020 – June 2025

* **Grade:** Very Good
* **Department Rank:** 3rd
* **Graduation Project:** Edge Autonomous Driving System with DevOps Integration
* **Project Grade:** Excellent (A+)

---

# 🎯 Current Focus

I'm continuously expanding my expertise in:

**AWS • Linux Administration • Cloud Infrastructure • Terraform • Ansible • Docker • Kubernetes • CI/CD**

My focus is on building infrastructure that is:

`Automated` • `Scalable` • `Highly Available` • `Secure` • `Observable` • `Reliable`

---

# 🤝 Let's Connect

I'm open to opportunities in:

**System Administration • Cloud Engineering • DevOps • Infrastructure Engineering**

📧 **Email:** [m.nasser5466@gmail.com](mailto:m.nasser5466@gmail.com)

💼 **LinkedIn:** [linkedin.com/in/mohamed-gamal546](https://www.linkedin.com/in/mohamed-gamal546)

💻 **GitHub:** [github.com/mohamedgamal546](https://github.com/mohamedgamal546)

---

### Build. Automate. Operate. Improve.
