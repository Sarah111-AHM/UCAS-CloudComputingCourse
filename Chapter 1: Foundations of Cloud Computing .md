# Chapter 1: Introduction to Cloud Computing

---

## 1. Definition of Cloud Computing

**Cloud Computing** is a **specialized distributed computing model** that enables:

- Delivery of **IT resources as services** over a network (typically the **Internet**).
- Resources are **scalable**, **pooled**, and **virtualized**, allowing flexible usage and efficiency.

**Keywords:**  
distributed computing · virtualized resources · scalable · pooled · service delivery

**Example:**  
Renting virtual servers on **AWS** instead of buying physical servers.

---

## 2. Key Characteristics of Cloud Computing

| Characteristic | Description | Example |
|---------------|------------|---------|
| **Virtualized Resources** | Physical resources are abstracted into virtual forms | Virtual machines on AWS EC2 |
| **Resource Pooling** | Multiple users share the same physical resources efficiently | Shared storage or compute clusters |
| **Scalability & Elasticity** | Resources can grow or shrink on demand | Auto-scaling server instances |
| **On-demand Service** | Users can request and use resources whenever needed | Launching a new VM instantly |
| **Network-based Access** | Services are accessed over a network | Web applications or cloud databases |

---

## 3. Evolution of Cloud Computing

1. **Traditional On-premise Computing**  
   Organizations managed their own hardware and software.

2. **Virtualization & Distributed Systems**  
   Abstracting resources and distributing workloads.

3. **Service-Oriented Architecture (SOA)**  
   Applications exposed as services over networks.

4. **Cloud Computing Model**  
   Combines virtualization, pooling, and service-based delivery over the Internet.

**Example:**  
Moving from in-house email servers to **Gmail** in the cloud.

---

## 4. Cloud Service Models

Cloud services are categorized into **three primary models**:

### 4.1 Infrastructure as a Service (IaaS)

- Provides virtualized computing resources:
  - Servers
  - Storage
  - Networking
- Users control the **Operating System** and **applications**.
- Provider manages physical hardware.

**Examples:**  
AWS EC2  
Azure Virtual Machines  

---

### 4.2 Platform as a Service (PaaS)

- Provides a **development and deployment platform**.
- Infrastructure management is **abstracted**.
- Focus on application development.

**Examples:**  
Google App Engine  
Azure App Service  

---

### 4.3 Software as a Service (SaaS)

- Delivers **complete software applications** over the web.
- No installation or maintenance required.
- Accessed via a **web browser**.

**Examples:**  
Gmail  
Microsoft 365  

---

### Service Model Memory Rule

IaaS → Infrastructure → You manage OS & applications  
PaaS → Platform → You develop applications  
SaaS → Software → Just use it  

---

## 5. Relationship Between Cloud Service Models

### Hierarchy of Dependence

- **SaaS is built on PaaS**
- **PaaS is built on IaaS**

### Complementary Models

- Models **do not compete**.
- They **work together**, each providing a higher level of abstraction.

**Example:**  
Gmail (SaaS) → Google App Engine (PaaS) → Google Cloud Compute (IaaS)

**Keywords:**  
hierarchy · complementary · dependency · abstraction

---

## 6. Importance of Cloud Computing

| Advantage | Explanation | Example |
|---------|------------|---------|
| **Cost Efficiency** | Pay-as-you-go model | Renting VMs instead of buying servers |
| **High Availability** | Systems remain accessible during failures | Multi-zone deployments |
| **Scalability** | Dynamic increase/decrease of resources | Auto-scaling during traffic spikes |
| **Rapid Deployment** | Fast application launch | Deploying apps in minutes |
| **Support for Modern Applications** | Supports AI, IoT, microservices | Netflix, Spotify |

---

## 7. Cloud Deployment Models

### Public Cloud
- Services over the Internet to multiple tenants  
- Example: AWS, Microsoft Azure

### Private Cloud
- Dedicated to a single organization  
- Example: Internal enterprise cloud

### Hybrid Cloud
- Combination of public and private clouds  
- Example: Sensitive workloads on private cloud

### Community Cloud
- Shared by organizations with similar needs  
- Example: Research institutions

---

## 8. Cloud-Enabling Technologies

- **Virtualization**: Multiple virtual resources from one physical machine  
- **Automation & Orchestration**: Automatic provisioning and management  
- **Networking & Internet Technologies**: Enable remote access  
- **Service-Oriented Architecture (SOA)**: Modular service-based design

---

## Ultra-Short Memory Map

IaaS → Infrastructure  
PaaS → Platform  
SaaS → Software  
H → Hybrid  
C → Community / Public / Private
