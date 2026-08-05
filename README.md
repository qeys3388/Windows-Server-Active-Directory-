# Windows-Server-Active-Directory-
This is a project to learn Active Directory.  

# Lab: Creating Active Directory Users

## Objective

The objective of this lab was to learn how to create, manage, and organize Active Directory users within Windows Server 2025.

## Environment

- Windows Server 2025
- Azure Virtual Machine
- Active Directory Domain Services
- Server Manager
- Active Directory Users and Computers

## Tasks Completed

- Installed Active Directory Domain Services
- Opened Active Directory Users and Computers
- Created multiple user accounts
- Assigned users to Organizational Units
- Reset user passwords
- Disabled and re-enabled accounts
- Deleted and restored a user account

## Skills Practiced

- User account management
- Active Directory administration
- Password management
- Organizational Unit management

## Commands Used

```powershell
Get-ADUser
New-ADUser
Remove-ADUser
Unlock-ADAccount
```

## Challenges

Initially, I created users in the default Users container rather than in the correct Organizational Unit. I moved the users into the appropriate OU and verified that the structure reflected the intended company organization.

## Key Takeaways

- Active Directory stores users in Organizational Units for easier management.
- Security groups simplify permission management.
- PowerShell can automate repetitive administrative tasks.
- Proper OU design makes Group Policy deployment easier.

## Screenshots

- Server Manager
- Active Directory Users and Computers
- Created Users
- Organizational Units
- Successful User Creation



GitHub Repository Structure
Windows-Server-2025-Active-Directory-Lab
│
├── 01-Server-Installation
├── 02-Active-Directory
├── 03-DNS
├── 04-Organizational-Units
├── 05-Users
├── 06-Groups
├── 07-Domain-Join
├── 08-Group-Policy
├── 09-File-Server
├── 10-DHCP
├── 11-Print-Services
├── 12-PowerShell
├── 13-Troubleshooting
└── Images
