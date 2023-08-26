# osTicket-Post-Installation-Configuration<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles & Departments
- Configure Teams 
- Allow anyone to create tickets
- Configure Agents(workers) & Users(customers)
- Configure SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure Roles
- a. Admin Panel -> Agents -> Roles
- b. Supreme Admin
- Configure Departments
- a. Admin Panel -> Agents -> Departments
- b. System Administrators

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure Teams
- a. Admin Panel -> Agents -> Teams
- i. Level I Support
- ii. Level II Support

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Allow anyone to create tickets
- a. Admin Panel -> Settings -> User Settings
- b. Registration Required: Require registration and login to create tickets 

<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Configure Agents (workers)
- a. Admin Panel -> Agents -> Add New
- i. Jane
- ii. John
- Configure Users (customers)
- a. Agent Panel -> Users -> Add New
- i. Karen
- ii. Ken

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure SLA
- a. Admin Panel -> Manage -> SLA
- i. Sev-A (1 hour, 24/7)
- ii. Sev-B (4 hours, 24/7)
- iii. Sev-C (8 hours, business hours)
- Configure Help Topics
- a. Admin Panel -> Manage -> Help Topics
- i. Business Critical Outage
- ii. Personal Computer Issues
- iii. Equipment Request
-iv. Password Reset

<br />
