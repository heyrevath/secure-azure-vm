# 🔐 Secure Azure Ubuntu Virtual Machine Deployment

<img width="700" height="768" alt="nhrdM7MAcaa46gbK-v18c-modified" src="https://github.com/user-attachments/assets/e0257c75-3f3f-4109-98d3-14594983fc3c" />


## 📌 Project Overview
This project demonstrates the secure deployment and configuration of an **Ubuntu Linux Virtual Machine in Microsoft Azure**.  
It focuses on **secure network access, SSH-based remote connectivity, and basic cloud security best practices**, which are essential skills for **Cloud Support Engineer** and **Cloud Security Engineer** roles.

---

## 🎯 Project Objectives
- Deploy an Ubuntu Linux Virtual Machine in Microsoft Azure  
- Secure the VM using Network Security Groups (NSGs)  
- Enable secure remote access using SSH (Port 22)  
- Apply basic cloud security best practices  
- Document the deployment using GitHub  

---

## ☁️ Technologies Used
- Microsoft Azure  
- Ubuntu Linux Virtual Machine  
- Azure Virtual Network  
- Network Security Group (NSG)  
- SSH (Port 22)  
- Azure Portal 

---

## 🏗️ Architecture Overview
The architecture consists of:
- An Ubuntu VM deployed inside an Azure Virtual Network  
- A Network Security Group controlling inbound traffic  
- SSH access enabled while all unnecessary ports remain blocked  


---

## 🚀 Deployment Steps
### Create a Resource Group
A resource group is created to organize all Azure resources used in this project.

<img width="900" height="700" alt="RG01" src="https://github.com/user-attachments/assets/c80907cb-96b8-4308-8301-6935b8d3d023" />


---

### Create Ubuntu Virtual Machine
- OS Image: Ubuntu Server (LTS)  
- VM size selected based on requirement  
- Authentication configured using SSH key 

<img width="900" height="700" alt="VM01" src="https://github.com/user-attachments/assets/e48ecb22-306d-447c-9fdd-5547c2c1a11a" />


---

### Configure Network Security Group (NSG)
Inbound security rules configured to:
- Allow SSH (Port 22)  
- Restrict access to required sources  
- Block all other inbound traffic  

<img width="900" height="700" alt="NSG 01" src="https://github.com/user-attachments/assets/681d63b9-3863-41f8-8c6a-326a9fa60402" />

---

### Connect to VM Using SSH
Secure remote access to the Ubuntu VM is established using SSH.

<img width="900" height="700" alt="VM03" src="https://github.com/user-attachments/assets/c882b2f9-bf94-4d8d-b397-8aa22b79d513" />

---
## Conclusion
This project presents a secure deployment of an **Ubuntu Linux Virtual Machine on Microsoft Azure**, emphasizing controlled network access and secure remote connectivity. The implementation of **Network Security Groups and SSH-based access** demonstrates foundational cloud security practices relevant to modern cloud environments.

---

## In Future
- Enable Azure Monitor and Log Analytics for performance and security monitoring  
- Configure Azure Backup for data protection and disaster recovery  
- Implement Just-In-Time (JIT) VM access to reduce attack surface  

---


