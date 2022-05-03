<h1>Active Directory Administration Lab: Running Active Directory inside Oracle VirtualBox and adding Users with Powershell</h1>


<h2>Description</h2>
A powerShell automated provision, maintaining and deprovisioning user accounts. And a Remote Access Serve (RAS) set up to support NAT/PAT. With an implimentation and maintanance of Windows DNS and DHCP services. Then configuring Windows File Servers with implementation of quotas and NTFS permissions.
<br />


<h2>Languages Used</h2>

- <b>PowerShell</b> Adding 900+ Users

<h2>Environments Used </h2>

- <b>Oracle VirtualBox</b> Virtual Machine

- <b>Windows 10 pr ISOo</b> (21H2) Client Virtual Machine

- <b> Server 2019 ISO</b> Domain Controller housing Active Directory

<h2>Lab walk-through:</h2>

<p align="center">
Create Virtual Machine: Open Firewall to public internep traffic <br/>
<img src="https://imgur.com/DkaG4pN.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Log Analytics Workspace: Connect Log Analytics to VM  <br/>
<img src="https://imgur.com/KWZN4Xd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up Microsoft Azure Sentinel: Log into VM remotely <br/>
<img src="https://imgur.com/2IDgZxq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe Event Viewer Logs in VM: Turn off Windows Firewall on VM  <br/>
<img src="https://imgur.com/6HA10WR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Get Geolocation.io API Key: Run Powershell script to get Geo Data from attackers  <br/>
<img src="https://imgur.com/nFNNGVH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create custom log in LAW: Extract filds from raw custom log data  <br/>
<img src="https://imgur.com/3nu9aY8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup map in Sentinel by Country: Observe attackers on world map <br/>
<img src="https://imgur.com/9i067XT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

