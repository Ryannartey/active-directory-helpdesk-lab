# Active Directory Help Desk Lab

## Overview

This project demonstrates the deployment and administration of a Windows Server 2022 Active Directory environment.

The lab includes:

- Domain Controller deployment
- Active Directory Domain Services (AD DS)
- Organizational Units (OUs)
- User and Group Management
- Role-Based Access Control (RBAC)
- Shared Folder Permissions
- Group Policy Objects (GPOs)
- Password Policies
- Account Lockout Policies
- Network Drive Mapping

---

## Technologies Used

- Windows Server 2022
- Active Directory Domain Services
- Group Policy Management
- NTFS Permissions
- SMB File Sharing
- VirtualBox

---

## Lab Walkthrough

### 1. Domain Controller Setup

![DC Rename](./01-DC01-Rename.png)
![Static IP](./02-Static-IP-Configured.png)
![ADDS Installed](./03-ADDS-Installed.png)
![Domain Validation](./04-Domain-Validation-Passed.png)
![Promoted DC](./05-Domain-Controller-Promoted.png)
![Active Directory Domain](./06-Active-Directory-Domain.png)

---

### 2. Organizational Units

![OUs](./07-Organizational-Units.png)

Created separate departments:

- IT
- HR
- Finance

---

### 3. User and Group Management

![IT Users](./08-IT-User-Accounts.png)
![IT OU Users and Groups](./10-IT-OU-Users-and-Groups.png)
![IT Department](./11-IT-Department.png)
![HR Department](./12-HR-Department.png)
![Finance Department](./13-Finance-Department.png)
![Group Membership](./14-Ryan-ITAdmins-GroupMembership.png)

---

### 4. Security Administration

![Disabled User](./15-Disabled-User-Account.png)
![CompanyFiles Share](./16-CompanyFiles-Share-Configuration.png)
![AD Group Permissions](./17-AD-Group-Permissions.png)
![RBAC](./18-Role-Based-Access-Control.png)

---

### 5. Group Policy Management

![Custom GPO](./19-Custom-GPO-Created.png)
![Password Policy GPO](./20-Password-Policy-GPO.png)
![Password Policy Configured](./21-Password-Policy-Configured.png)
![Account Lockout Policy](./22-Account-Lockout-Policy.png)

---

### 6. Drive Mapping

![GPO Drive Mapping](./23-GPO-Drive-Mapping.png)
![Drive Mapping Applied](./24-Drive-Mapping-GPO-Applied.png)

---

## Skills Demonstrated

- Active Directory Administration
- Group Policy Management
- Identity and Access Management (IAM)
- User Provisioning and Deprovisioning
- File Share Administration
- NTFS and Share Permissions
- Password Security Enforcement
- Network Drive Mapping
- Windows Server Administration


## Project Summary

Built a Windows Server 2022 Active Directory lab to simulate real Help Desk and Junior System Administrator tasks, including user provisioning, group management, password resets, account disablement, password policies, account lockout policies, shared folder permissions, and mapped network drives.
