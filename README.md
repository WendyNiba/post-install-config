# post-install-config
<p align="center">
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

- Congratulations, hopefully it is installed with no errors!
Go to Remote Desktop
Browse to your help desk login page: http://localhost/osTicket/scp/login.php
<p>
<img src="https://i.imgur.com/sSK9J0q.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


- Observe the differences between the admin panel and the agent panel
Configure Roles 
https://docs.osticket.com/en/latest/Admin/Agents/Roles.html
Admin Panel -> Agents -> Roles - > Create new roles Supreme Admin
<p>
<img src="https://i.imgur.com/mB9s6f1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Give Supreme Admin permisions to everything

- Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
<p>
<img src="https://i.imgur.com/iyuTmgr.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
Add a new team and name it level 2 support
Create Teams
<p>
<img src="https://i.imgur.com/WJkMkQb.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 

Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John

<p>
<img src="https://i.imgur.com/upmY7nz.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
<p>
<img src="https://i.imgur.com/p19qsZL.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
<p>
<img src="https://i.imgur.com/gUnWLL0.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
<p>
<img src="https://i.imgur.com/ji8kqU9.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Mention IRL, it's possible for users to fill out forms and/or send emails and tickets will automatically be created for them.


