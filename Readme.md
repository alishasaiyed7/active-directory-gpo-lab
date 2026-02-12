# Active Directory Group Policy (GPO) – Hands-On Lab Project

## 📌 Project Overview
This project demonstrates hands-on implementation of Group Policy Objects (GPO) in a Windows Server Active Directory environment. The goal is to understand what GPO is, why it is important, how it is used in real enterprise environments, and how to troubleshoot common GPO-related issues.

---

## ❓ What is GPO?
Group Policy Object (GPO) is a feature in Windows Active Directory that allows administrators to centrally manage and enforce configuration settings for users and computers in a domain.

Using GPO, admins can:
- Enforce password policies
- Restrict access to Control Panel
- Map network drives
- Deploy software
- Configure security settings
- Control desktop environment

---

## 🎯 Why is GPO Important?
Without GPO:
- Admins would need to manually configure settings on each system
- Security policies would be inconsistent
- Compliance would be difficult to enforce
- IT operations would not scale

With GPO:
- Centralized management
- Improved security posture
- Reduced operational effort
- Standardized user experience

---

## 🔧 Tools & Environment
- Windows Server 2019 / 2022 (Domain Controller)
- Windows 10/11 client joined to domain
- Active Directory Domain Services
- Group Policy Management Console (GPMC)

---

## 🧪 Lab Scenarios Covered
- Creating and linking GPOs
- Enforcing password policy
- Restricting Control Panel access
- Mapping network drives using GPO
- Applying GPO to specific users using Security Filtering
- Using WMI Filters
- Backing up and restoring GPOs
- Troubleshooting GPO application issues

---

## 📚 Real-Life Use Cases
- Enforcing corporate security baselines
- Locking down kiosk machines
- Managing thousands of users in enterprise environments
- Applying department-specific policies (HR, Finance, IT)

---

## 🛠 Commands Used
gpupdate /force  
gpresult /r  

---

## 🧠 Learning Outcomes
- Strong understanding of Group Policy architecture
- Practical experience managing enterprise-level policies
- Improved troubleshooting and root cause analysis skills

---

## Author - Alisha Saiyed
