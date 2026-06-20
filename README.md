# Configuring On-premises Active Directory within Azure VMs

## Project Overview
This project demonstrates the deployment of a functional Active Directory Domain Services (AD DS) environment within a Microsoft Azure virtual network. The goal was to simulate an enterprise-level identity management infrastructure in a hybrid cloud environment.

## Key Skills Demonstrated
- **Active Directory Domain Services (AD DS):** Managed users, groups, and domain policies.
- **Azure Networking:** Configured Virtual Networks (VNet) and subnets.
- **Windows Server Administration:** Installed and promoted a server to a Domain Controller.
- **Infrastructure Troubleshooting:** Validated domain connectivity and DNS resolution.

## Implementation Steps
1. Created an Azure Virtual Network.
2. Deployed a Windows Server Virtual Machine.
3. Installed and configured Active Directory Domain Services.
4. Promoted the server to a Domain Controller.
5. User Management: Created Organizational Units (OU) and added test user accounts to verify proper authentication.


![Active Directory Setup](ad-setup.png)
*Figure 1: Server Manager dashboard confirming AD DS installation.*

![Test Users and OUs](ad-users.png)
*Figure 2: Active Directory Users and Computers view showing organizational structure.*
