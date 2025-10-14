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
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
