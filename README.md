# UCAS-CloudComputingCourse
Study notes, summaries, and project work for Cloud Computing course at UCAS Instructor: Dr. Esraa Ahmed Ferwana Topics: Cloud service models, deployment, infrastructure, security, storage, management, architectures, and real-world case studies.
---
#  Cloud Computing - UCAS

**Instructor:** Dr. Esraa Ahmed Ferwana  
**Email:** [ifarwanah@ucas.edu.ps](mailto:ifarwanah@ucas.edu.ps)  

---

##  Course Description
Structured introduction to **cloud computing principles, technologies, and architectures**.  

**Topics covered:**
- **Service Models:** IaaS, PaaS, SaaS  
- **Deployment Models:** Public, Private, Hybrid, Community  
- **Infrastructure:** Compute, Storage, Networking, Containers, Serverless  
- **Cloud Security & IAM**  
- **Management Mechanisms:** Automation, Orchestration, Monitoring  
- **Architectures:** Edge, Multi-cloud, Meta-cloud  
- **Cloud Storage & Big Data**  
- **Case Studies** on major cloud platforms  

**Visual Overview:**
![Cloud Computing Diagram](./images/cloud-overview.png)  
*Add your own diagrams here.*

---

##  Study Plan

| Week | Topic | Notes File |
|------|-------|------------|
| 1 | Introduction to Cloud Computing | `1_introduction/intro_notes.md` |
| 2 | Deployment Models & Enabling Technology | `2_deployment_models/deployment_notes.md` |
| 3 | Infrastructure Mechanisms I (Compute, Storage, Networking) | `3_infrastructure_mechanisms/infrastructure_I.md` |
| 4 | Infrastructure Mechanisms II (Containers, Serverless, Microservices) | `3_infrastructure_mechanisms/infrastructure_II.md` |
| 5 | Cloud Security & Cybersecurity I (Access Mechanisms: IAM, Auth) | `4_security/access_mechanisms.md` |
| 6 | Cloud Security & Cybersecurity II (Data: Encryption, Integrity) | `4_security/data_mechanisms.md` |
| 7 | Cloud Management Mechanisms | `5_cloud_management/management_mechanisms.md` |
| 8 | Cloud Architectures I (Public, Private, Hybrid, Federated) | `6_architecture/fundamental.md` |
| 9 | Cloud Architectures II (Edge, Multi-cloud, Meta-cloud) | `6_architecture/advanced.md` |
| 10 | Working with Clouds I (Cost & Delivery Models) | `7_working_with_clouds/delivery_models.md` |
| 11 | Working with Clouds II (Service Quality & SLAs) | `7_working_with_clouds/service_quality.md` |
| 12 | Cloud Storage & Big Data I (Distributed Storage, Tiering) | `8_storage_bigdata/distributed_storage.md` |
| 13 | Cloud Storage & Big Data II (Analytics in Cloud) | `8_storage_bigdata/bigdata_analytics.md` |

---

## Cloud Security Summary

### CIA Security Triad

| Goal | Definition | Cloud Techniques |
|------|------------|----------------|
| **Confidentiality** | Prevent unauthorized access | Encryption, IAM, Access Control |
| **Integrity** | Prevent unauthorized modification | Logging, Monitoring |
| **Availability** | Ensure access to services | Redundancy, Backups, Load Balancing |

**Visual Tip:**  
![CIA Triad Diagram](./images/cia-triad.png)  

---

### Shared Responsibility Model

| Responsibility | Provider | Consumer |
|----------------|---------|----------|
| Physical Data Centers | ✅ | ❌ |
| Hardware & Virtualization | ✅ | ❌ |
| Data | ❌ | ✅ |
| IAM & Permissions | ❌ | ✅ |
| Applications | ❌ | ✅ |

---

### Principle of Least Privilege

- Grant **minimum permissions** required  
- Reduces **security risks**  

**IAM Example – University System**

| Role | Permissions |
|------|------------|
| Students | View grades |
| Instructors | Enter grades |
| Admins | Full system access |

---

##  Key Takeaways

- Cloud security protects **systems and data**  
- **CIA triad** is foundational  
- Security responsibility is **shared**  
- **IAM controls access** and supports **least privilege**  

---

##  Projects

- Folder: `projects/`  
- Contains **assignments, midterm, and final project files**  
- Include **Python scripts, Jupyter notebooks, diagrams**  
