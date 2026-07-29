# Enterprise Windows Server Infrastructure

Enterprise infrastructure deployment using **Windows Server 2016** in a virtualized environment. This project demonstrates the implementation and administration of core Microsoft infrastructure services including Active Directory Domain Services (AD DS), DNS, DHCP, Group Policy, Active Directory Replication, and Network Load Balancing (NLB).

---

# Project Overview

This lab was built to simulate a small enterprise environment using VMware Workstation. The infrastructure was designed to provide centralized authentication, network services, user management, and high availability concepts commonly used in enterprise networks.

---

# Objectives

- Deploy Windows Server 2016
- Configure Active Directory Domain Services
- Configure DNS Server
- Configure DHCP Server
- Manage Users and Organizational Units
- Apply Group Policy Objects
- Configure Additional Domain Controller
- Configure Child Domain
- Monitor Active Directory Replication
- Configure Network Load Balancing

---

# Lab Environment

| Component | Technology |
|-----------|------------|
| Hypervisor | VMware Workstation |
| Operating System | Windows Server 2016 |
| Client | Windows 10 |
| Directory Service | Active Directory |
| DNS | Microsoft DNS |
| DHCP | Microsoft DHCP |
| High Availability | Network Load Balancing |

---

# Virtual Machines

| Machine | Role |
|---------|------|
| ADDS1 | Primary Domain Controller |
| ADC | Additional Domain Controller |
| ChildDC | Child Domain Controller |
| NLB1 | Load Balancing Node |
| NLB2 | Load Balancing Node |

---

# Technologies

- Windows Server 2016
- VMware Workstation
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- Active Directory Replication
- Network Load Balancing
- PowerShell
- Command Prompt

---

# Implemented Features

## Active Directory

- Domain Controller Deployment
- Additional Domain Controller
- Child Domain
- User Management
- Group Management
- Organizational Units

## DNS

- Forward Lookup Zone
- Reverse Lookup Zone
- Name Resolution

## DHCP

- DHCP Scope
- Address Leasing
- DHCP Configuration

## Group Policy

- User Policies
- Computer Policies
- Administrative Templates

## Replication

- Active Directory Replication
- Replication Monitoring
- Replication Troubleshooting

## High Availability

- Network Load Balancing (NLB)

---

# Troubleshooting

Throughout the project, several Microsoft administration tools were used:

- Repadmin
- DCDiag
- GPResult
- Event Viewer
- Server Manager
- Active Directory Administrative Center

---

# Skills Demonstrated

- Windows Server Administration
- Active Directory Administration
- DNS Administration
- DHCP Administration
- Group Policy Management
- Active Directory Replication
- Enterprise Network Administration
- Troubleshooting Windows Server
- High Availability Fundamentals

---

# Project Structure

```
Enterprise-Windows-Server-Infrastructure
│
├── README.md
├── screenshots
├── docs
```

---


# Author

**Rawan Hesham Mohamed**

Faculty of Computers and Artificial Intelligence, Cairo University
