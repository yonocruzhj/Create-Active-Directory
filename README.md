<h1>Setting Up Basic Home Lab Running Active Directory</h1>

<h2>Description</h2>
This project outlines the steps to set up a basic home lab running Active Directory (AD) using a virtualized environment. Active Directory is a directory service developed by Microsoft that provides centralized authentication, authorization, and management for users, devices, and resources in a Windows-based network. 

<h2>Goals</h2>
The purpose of this home lab setup is to simulate a real-world network, allowing cybersecurity enthusiasts to learn and practice skills like user management, group policies, DNS configurations, and domain management.
<br />

<h2>Languages and Utilities </h2>

- <b> Powershell </b> 

<h2>Environments Used </h2>

- <b>Windows 11 Pro</b>
- <b>Windows 2019 Server</b>
- <b> UTM Virtual Machines for macOS</b>

<h2>Configure Active Directory Domain Serivices On Windows Server:</h2>

Assign Static IP to Adapter that will act as NIC for internal network (bridged): <br/>
<img src="https://imgur.com/Hk7QatQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Install RAS/NAT: <br/>
<img src="https://imgur.com/WwoAdmj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Install AD DS:  <br/>
<img src="https://imgur.com/seCc34h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/WwoAdmj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Install DHCP and Create New Scope:
<img src="https://imgur.com/1MqNm8l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Promote Server to a Domain Controller <br/>
<img src="https://imgur.com/sqY98ze.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/7xK7gAg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2> Connect Windows 11 Client to Server </h2>
<br />
<br />
Join Domain and Change PC Name <br/>
<img src="https://imgur.com/ldYMWAy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2> Managing Active Directory</h2>
<br />
Create User Accounts and Organize into Organizational Units (OUs) using script<br/>
<img src="https://imgur.com/9QgBy4n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Manage Group Policies<br/>
<img src="https://imgur.com/2j54YQp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/SBmmzpi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

Summary

This project provided a step-by-step guide to setting up a basic home lab that runs **Active Directory (AD)** in a virtualized environment. **Active Directory** is a Microsoft directory service that centralizes **authentication**, **authorization**, and **management** for users, devices, and resources within a Windows network. In this lab, I configured an Active Directory with Windows 2019 server and connected it to a client (Windows 11 Pro), created many user accounts, and assigned tasks to specific users.
