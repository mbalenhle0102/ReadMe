OS Power User: User & File Management Exercise 
Introduction
This project demonstrates proficiency in Windows system administration using PowerShell. The goal is to move beyond the GUI to manage users, file permissions, and software installation via the command line, which is essential for automation and efficiency in an IT environment.

This project was completed as part of **Course 3: Operating Systems and You – Becoming a Power User**. It demonstrates proficiency in system administration tasks using the command line interface (CLI), specifically focusing on Windows PowerShell.

 Project Objectives
* **User & Group Management:** Creating local accounts and assigning roles.
* **Security & Permissions:** Managing Access Control Lists (ACLs) for files.
* **Package Management:** Automating software installation via `winget`.

---
Tasks Performed

1. User and Group Management
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
 Practical Evidence

1. User Creation:
<img width="791" height="378" alt="powershell1" src="https://github.com/user-attachments/assets/9139ffe7-feae-45e0-a2b8-8ee7e3f02110" />


2. Permissions Setup:
<img width="798" height="384" alt="powershell2" src="https://github.com/user-attachments/assets/e8a6ab79-1a90-4a9e-b9a1-b63a50bbca71" />


`
3. Software Installation
<img width="1045" height="390" alt="powershell3" src="https://github.com/user-attachments/assets/10386be0-4326-41f9-9ee5-eddc20a79ba3" />

 

 Skills Demonstrated
| Skill | Tool/Tech |
| :--- | :--- |
| System Administration | Windows PowerShell |
| Identity Management | Local Accounts & Groups |
| Cyber Security | ACLs / Permissions |
| Automation | winget (CLI) |

---
Conclusion
I successfully performed core OS tasks using the CLI. By automating user creation and permission scaling, I demonstrated how to manage a system securely and efficiently. These skills are fundamental for any modern IT Power User.
Author:Innocentia Jiwa  
Date: February 2026  
