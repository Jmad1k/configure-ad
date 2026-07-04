<p align="left">
  <img src="images/1_9DxO5nO1O4Z6w3ra5Go60w-4172338739.png" width="500" alt="Active Directory Logo">
</p>

# Active Directory Domain Services (AD DS) Deployment

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

<br>

![Azure Resource Group Architecture](images/RGOverview.png)
*Figure 1: Creation of Azure Resource Group architecture containing the Domain Controller (dc-1) and Client VM (Client-1), providing an organized foundation for the domain environment.*


![Azure Resource Group Architecture](images/RGCloseUp.png)
*Figure 1(a): Close up of Overview of Resource group .*

<br>

<a href="images/DNSCl.png">
  <img src="images/DNSCl.png" alt="DNS Verification">
</a>
*Figure 2: (Click to Enlarge) Verifying DNS connectivity from the Client VM. The 'ipconfig /all' output confirms the primary DNS server correctly points to the Domain Controller’s private IP address, enabling domain name resolution.*

