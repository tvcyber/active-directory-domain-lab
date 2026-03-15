# Active Directory Home Lab

## Overview
This project demonstrates the deployment and configuration of a Windows Server 2022 Active Directory environment in a virtualized lab.

The lab simulates common IT help desk tasks such as user management, password resets, and organizational unit administration.

## Lab Environment

Virtualization Platform:
- Oracle VirtualBox

Server Operating System:
- Windows Server 2022

Directory Services:
- Active Directory Domain Services (AD DS)

Domain Name:
```
tylerlab.local
```

---

## Configuration Steps

### 1. Virtual Environment Setup
- Installed Oracle VirtualBox
- Created Windows Server 2022 virtual machine
- Allocated CPU, RAM, and storage for server environment

### 2. Active Directory Installation
- Installed Active Directory Domain Services
- Promoted server to Domain Controller
- Created domain environment

### 3. Organizational Structure
Created Organizational Units for departments:

```
Company
 ├ IT
 ├ HR
 ├ Sales
 └ Accounting
```

### 4. User Administration
Created and managed domain users including:

- jsmith
- mdavis
- slee
- ckent

### 5. Help Desk Task Simulation
Performed common IT support tasks:

- Password resets
- Account unlocks
- Account disabling
- Department organization

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Domain Services
- Organizational Unit Management
- User Account Administration
- Help Desk Troubleshooting
- Virtualization

