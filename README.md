<h1>Active Directory Administration Lab: Running Active Directory inside Oracle VirtualBox and adding Users with Powershell</h1>


<h2>Description</h2>
A powerShell automated provision, maintaining and deprovisioning user accounts. And a Remote Access Serve (RAS) set up to support NAT/PAT. With an implimentation and maintanance of Windows DNS and DHCP services. Then configuring Windows File Servers with implementation of quotas and NTFS permissions.
<br />


<h2>Languages Used</h2>

- <b>PowerShell:</b> Adding 900+ Users

<h2>Environments Used </h2>

- <b>Oracle VirtualBox:</b> Virtual Machine

- <b>Windows 10 pr ISO:o</b> (21H2) Client Virtual Machine

- <b> Server 2019 ISO:</b> Domain Controller housing Active Directory

<h2>Lab walk-through:</h2>

<p align="center">
Lab Overview <br/>
<img src="https://imgur.com/DkaG4pN.png" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Install Server 2019 OS: Install VirtualBox Guest Additions <br/>
<img src="https://imgur.com/DkaG4pN.png" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Setup Server Network Adapters and Rename Server: Assign IP Adress to Internal Adapter  <br/>
<img src="https://imgur.com/KWZN4Xd.png" height="80%" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Install Active Directory Domain Services: Promote Domain Controller (projectdomain.com) <br/>
<img src="https://imgur.com/2IDgZxq.png" height="80%" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Create Domain Admin Account: Re-login with Domain Admin Account  <br/>
<img src="https://imgur.com/6HA10WR.png" height="80%" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Install and configure RAS/NAT and DCHP: Enable browsing on the Domain Controller  <br/>
<img src="https://imgur.com/nFNNGVH.png" height="80%" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Run Powershell ISE script as Admin: Change Directory to Script Directory to create users <br/>
<img src="https://imgur.com/3nu9aY8.png" height="80%" width="80%" alt="AD Setup Steps"/>
<br />
<br />
Install Windows 10 OS as Client VM: Join to domain and rename, then login with Domain Credentials <br/>
<img src="https://imgur.com/9i067XT.png" height="80%" width="80%" alt="AD Setup Steps"/>
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

