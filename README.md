# 👥 Active Directory Home Lab

Windows Active Directory home lab built using VirtualBox and PowerShell automation.  
This project simulates a real-world enterprise environment with a Domain Controller, DNS, DHCP, and domain-joined client machines.

---

## 🖥️ Lab Overview

This environment was built to practice Windows Server administration and Active Directory concepts in a safe, isolated lab using VirtualBox.

### Infrastructure

- **DC01 (Windows Server)**
  - Active Directory Domain Services (AD DS)
  - DNS Server
  - DHCP Server

- **Client Machine (Windows 10)**
  - Domain Joined

- **Network Setup**
  - Internal VirtualBox Network
  - NAT for internet access

---

## 🛠️ Technologies Used

- Windows Server 2019 / 2022
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- PowerShell
- Oracle VirtualBox
- Windows 10

---

## ⚙️ Features Implemented

- Active Directory Domain setup
- Organizational Units (OUs)
- Bulk user creation via PowerShell
- DHCP scope configuration
- DNS resolution inside the domain
- Domain joining process
- Internal network segmentation

---

## 🔥 PowerShell Automation

User creation and Active Directory provisioning were automated using a PowerShell script.

👉 View scripts here:  
https://github.com/Burkhardt0Patrick/Active-Directory-Lab/tree/main/scripts

---

## 📸 Screenshots

### Domain Controller (DC01)

![DC01](images/dc01-server.png)

---

### Active Directory Users and Computers

![AD Users](images/dc01-ad-users.png)

---

### PowerShell User Creation Process

![PowerShell](images/powershell.png)

---

### DHCP Configuration

![DHCP](images/dhcp.png)

---

### Client Machine Joined to Domain

![Domain Join](images/domain-joined.png)

---

## 🎯 What I Learned

- Windows Server administration
- Active Directory structure and user management
- DNS and DHCP configuration
- PowerShell scripting and automation
- Domain networking concepts
- Virtual machine networking (VirtualBox)

---

## 🚀 Future Improvements

- Group Policy Objects (GPOs)
- File server with permissions
- Centralized logging and monitoring
- Security hardening policies
- SIEM integration (Splunk / ELK)

---

## 📁 Project Structure
