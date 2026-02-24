# OS Power User: User & File Management Exercise 💻

This project was completed as part of **Course 3: Operating Systems and You – Becoming a Power User**. It demonstrates proficiency in system administration tasks using the command line interface (CLI), specifically focusing on Windows PowerShell.

## 🎯 Project Objectives
* **User & Group Management:** Creating local accounts and assigning roles.
* **Security & Permissions:** Managing Access Control Lists (ACLs) for files.
* **Package Management:** Automating software installation via `winget`.

---

## 🛠️ Tasks Performed

### 1. User and Group Management
I utilized PowerShell to manage system identities without a GUI. This is a critical skill for managing servers and remote environments.
* **Commands used:** `New-LocalUser`, `New-LocalGroup`, `Add-LocalGroupMember`
* **Outcome:** Created a restricted user and assigned them to a specific security group.

### 2. File Systems and Permissions
I demonstrated the principle of **Least Privilege** by manually configuring file access.
* **Commands used:** `New-Item`, `Get-Acl`, `Set-Acl`
* **Outcome:** Created a secure file and granted "Read" access to a specific user using an Access Control Rule.

### 3. Package Management
Rather than manually downloading installers, I used a CLI package manager to ensure a secure and repeatable installation process.
* **Commands used:** `winget search`, `winget install`
* **Outcome:** Successfully installed **Notepad++** via the Windows Package Manager.

---

## 📸 Practical Evidence
*Check the `/screenshots` folder for visual confirmation of these steps.*

1. **User Creation:** `screenshot-user-mgmt.png`
2. **Permissions Setup:** `screenshot-acl-config.png`
3. **Software Installation:** `screenshot-winget-install.png`

---

## 🧠 Skills Demonstrated
| Skill | Tool/Tech |
| :--- | :--- |
| System Administration | Windows PowerShell |
| Identity Management | Local Accounts & Groups |
| Cyber Security | ACLs / Permissions |
| Automation | winget (CLI) |

---

**Author:** [Your Name]  
**Date:** February 2026  
**Course:** Google IT Support Professional Certificate# ReadMe
