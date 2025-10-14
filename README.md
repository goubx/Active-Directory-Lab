<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This project demonstrates the setup and configuration of a Windows Server 2019 Active Directory environment. The lab covers the entire process of configuring the server, creating and organizing users, setting up Group Policy, configuring RAID 5, and mapping network drives manually and through scripts. The goal was to simulate an enterprise-style domain to practice identity management, user permissions, and system administration.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell – used for scripting, automation, and user management (DSADD, CSVDE).</b> 
- <b>Active Directory Domain Services (AD DS) – for domain and user management.</b>
- <b>Disk Management / RAID 5 – for drive redundancy configuration.</b>
- <b>File Explorer / Batch Scripts – for manual and automated network drive mapping.</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019 – domain controller and file server.</b> (21H2)
- <b>Windows 11 – domain-joined client machine.</b> (21H2)
- <b>Oracle VirtualBox – used to virtualize and network both systems in an isolated lab environment.</b> (21H2)


<h2>Program walk-through:</h2>

<p align="center">
Active Directory setup begins by installing the Active Directory Domain Services (AD DS) role on Windows Server 2019.
After installation, the server is promoted to a domain controller and the domain mohamedyagoub.com is created.: <br/>
<img src="https://imgur.com/ZZsOGdH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/qdvOWqI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/8AmNJek.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured IP address, DNS, and time zone for proper domain connectivity.
Server renamed to SERVER01 and connected to an internal VirtualBox network.:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created OUs for: IT, Sales, HR, Accounting, Research, CCP, Temple, and Drexel. Each OU was organized to simulate real enterprise departments: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Users (Manual and Scripted):
Added users manually to HR, IT, and Sales OUs & used PowerShell and CSVDE to automate user creation for Temple and CCP OUs:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured RAID 5 storage in Server Manager to simulate data redundancy and improve read performance:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Map Network Drives:
Used File Explorer to manually map S:, H:, and P: drives for department shares. Automated mappings using PowerShell and Batch scripts for drives F:, Z:, and Y:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logged into a domain-joined Windows 11 client to confirm users could access mapped drives and apply GPO restrictions:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Collected screenshots and notes verifying that all domain services, permissions, and mappings functioned as expected.  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
