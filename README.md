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

![DC Rename](screenshots/01-DC01-Rename.png)

![Static IP](screenshots/02-Static-IP-Configured.png)

![ADDS Installed](screenshots/03-ADDS-Installed.png)

![Domain Validation](screenshots/04-Domain-Validation-Passed.png)

![Promoted DC](screenshots/05-Domain-Controller-Promoted.png)

![Active Directory Domain](screenshots/06-Active-Directory-Domain.png)

---

### 2. Organizational Units

![OUs](screenshots/07-Organizational-Units.png)

Created separate departments:

- IT
- HR
- Finance

---

### 3. User and Group Management

![Users](screenshots/08-IT-User-Accounts.png)

![OU Users and Groups](screenshots/10-IT-OU-Users-and-Groups.png)

![IT Department](screenshots/11-IT-Department.png)

![HR Department](screenshots/12-HR-Department.png)

![Finance Department](screenshots/13-Finance-Department.png)

![IT Admin Membership](screenshots/14-Ryan-ITAdmins-GroupMembership.png)

---

### 4. Security Administration

![Disabled User](screenshots/15-Disabled-User-Account.png)

![File Share](screenshots/16-CompanyFiles-Share-Configuration.png)

![Permissions](screenshots/17-AD-Group-Permissions.png)

![RBAC](screenshots/18-Role-Based-Access-Control.png)

---

### 5. Group Policy Management

![Custom GPO](screenshots/19-Custom-GPO-Created.png)

![Password Policy GPO](screenshots/20-Password-Policy-GPO.png)

![Password Policy](screenshots/21-Password-Policy-Configured.png)

![Account Lockout](screenshots/22-Account-Lockout-Policy.png)

---

### 6. Drive Mapping

![Drive Mapping](screenshots/23-GPO-Drive-Mapping.png)

![Applied Drive Mapping](screenshots/24-Drive-Mapping-GPO-Applied.png)

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
