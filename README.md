<h2>On-Premise Active Directory using Windows 10 and Windows Server Virtual Machines on Microsoft Azure</h2>
In this project, I successfully deployed an on-premises Active Directory environment using Microsoft Azure Virtual Machines, applied network administration and managed DNS services to improve network functionality.
<br />
<br />
<p align="center">
<img src="/AD-Structure.jpg" height="80%" width="80%"/>
</p>

<h2>4-Part Project</h2>

Due to the depth of the project, it's been broken down into 4 parts:
<br />

  - 🛠️ Active Directory Deployment
  - ⚙️ DNS Configurations and Management
  - 📈 Expansion and Further Management
  - 📜 Creating GPO (Group Policies)

<br />
This will be found below.

<br />

<h2>Links to the Different Parts of Project</h2>

- 🛠️ Part 1: Deploying the Active Directory on a Virtual Machine through Microsoft Azure
  - [Project Link: Deployment of an Active Directory on VMs via Azure](https://github.com/Ervin-Thorpe/Active-Directory-Deployment)
- ⚙️ Part 2: Managing DNS through our Virtual Machines made through Microsoft Azure
  - [Project Link: Configuration and Management of an Active Directory](https://github.com/Ervin-Thorpe/Active-Directory-DNS-Management)
- 🏢 Part 3: Expanding and Further Management of the Active Directory on Windows Server 2022
  - [Project Link: Active Directory Structure Expansion](https://github.com/Ervin-Thorpe/AD-Structure-Expansion)
- 📜 Part 4: Understanding and Creating GPO (Group Policies) on Windows Server 2022
  - [Project Link: Active Directory GPO (Group Policies)](https://github.com/Ervin-Thorpe/Active-Directory-GPO)


<h2>Technologies Used</h2>

- <b>Microsoft Azure</b>
- <b>Windows 10 Pro</b>
- <b>Windows Server 2022</b>
- <b>Active Directory</b>
- <b>Server Manager</b>
- <b>Azure Virtual Networks</b> 
- <b>DNS Manager</b>
- <b>Command Prompt</b>
- <b>Group Policy Objects (GPOs)</b>
- <b>Group Policy Management Console</b>

<h3>Key Accomplishments:</h3>

1. **Active Directory Deployment:**
   - Set up Azure VMs for Windows Server 2022 and Windows 10.
   - Installed and configured Active Directory Domain Services.
   - Promoted the server to a domain controller and created organisational units.
   - Configured the client VM to join the Active Directory domain and enabled remote desktop access.
   - Implemented and managed a in-depth Active Directory for centralised management of network resources.
   - Set up various Group Policy Objects (GPOs) to enforce security and configuration settings across the network.

2. **DNS Management:**
   - Created and tested A-Records, including updating IP addresses and verifying changes.
   - Set up a CNAME Record to create a domain alias for 'google'.

3. **Troubleshooting and Testing:**
   - Managed DNS settings and cleared cached records to ensure accurate resolution.
   - Verified DNS configuration and connectivity using commands like `ping` and `nslookup`.
  
4. **Group Policy Management:**
   - Created and edited GPOs through the Group Policy Management Console.
   - **Password Policy:** Configured rules for password complexity, length, and expiration to enhance security.
   - **Drive Mapping Preferences:** Automated network drive mappings to ensure consistent access to shared resources.
   - **Desktop Wallpaper Policy:** Set a standardized desktop background to reinforce corporate branding.
   - **Control Panel Policy:** Restricted or customized access to Control Panel settings to prevent unauthorized changes.
   - **Disable USB Devices Policy:** Restricted USB port usage to mitigate security risks.
   - **Account Lockout Policy:** Established measures to lock accounts after failed login attempts to prevent unauthorized access.

This project provided valuable hands-on experience in deploying and managing Active Directory on a Virtual Windows Server 2022 Machine, as well as focusing on DNS management, and creating Group Policy Objects (GPOs).
<br />
<br />
