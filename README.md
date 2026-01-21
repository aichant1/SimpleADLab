<h1>Active Directory Lab</h1>


<h2>Description</h2>
This lab demonstrates foundational identity and access management skills using Microsoft Active Directory in a simulated enterprise environment. A Windows Server domain controller was deployed in VMware Fusion on macOS and configured to manage users, groups, authentication, and access workflows commonly handled by IT Helpdesk and IAM teams.
<br />


<h2>Environments Used </h2>

- <b>macOS host (VMware Fusion)
- Windows Server 2019 (Domain Controller VM)
- Active Directory Domain Services
- Active Directory Users and Computers
- Windows 10/11 domain-joined client VM</b>

<h2>Key Tasks Performed</h2>

Created a custom Windows Server VM in VMware Fusion and installed Windows Server

Installed and configured Active Directory Domain Services and promoted the server to a domain controller

Created Organizational Units (OUs) to structure users and security groups

Created domain user accounts and security groups for role-based access control

Performed password resets and account unlocks using Active Directory Users and Computers

Modified group memberships to simulate permission changes for different roles

<h2>Skills Demonstrated </h2>

- <b>Identity and Access Management (IAM) fundamentals
- User and group lifecycle management in Active Directory
- Password reset and account unlock workflows
- Role-based access control (RBAC) via security groups
- Working with virtualized enterprise environments using VMware Fusion</b>

<h2>Program walk-through:</h2>

<p align="center">
Windows Server domain controller running inside VMware Fusion on macOS.  <br/>
<img width="1136" height="750" alt="00-vmware-fusion-dc01" src="https://github.com/user-attachments/assets/d3ecb631-0a6b-4a93-8528-013cddfacc78" />
<br />
<br />  
Windows Server configured as a Domain Controller with Active Directory Domain Services. <br/>
<img width="1136" height="750" alt="image" src="https://github.com/user-attachments/assets/37d16edd-a523-4ce4-a698-d802b1e1ddeb" />
<br />
<br />
Active Directory domain structure using Organizational Units to separate users and groups. <br/>
<img width="1136" height="750" alt="image" src="https://github.com/user-attachments/assets/f6576220-dcfa-4732-b748-f68de145bcda" />

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
