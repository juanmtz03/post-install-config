

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>Post-Install Configuration Objectives</h2>

### Part 3: Post Installation Setup

#### Configure Roles
- **Admin Panel** -> **Agents** -> **Roles**
  - Supreme Admin
#### Configure Departments
- **Admin Panel** -> **Agents** -> **Departments**
  - System Administrators
#### Configure Teams
- **Admin Panel** -> **Agents** -> **Teams**
  - Level I Support
  - Level II Support
#### Allow Anyone to Create Tickets
- **Admin Panel** -> **Settings** -> **User Settings**
  - Registration Required: Require registration and login to create tickets
#### Configure Agents (Workers)
- **Admin Panel** -> **Agents** -> **Add New**
  - Jane
  - John
#### Configure Users (Customers)
- **Agent Panel** -> **Users** -> **Add New**
  - Karen
  - Ken
#### Configure SLA
- **Admin Panel** -> **Manage** -> **SLA**
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)
#### Configure Help Topics
- **Admin Panel** -> **Manage** -> **Help Topics**
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset

<h2>Configuration Steps</h2>

<p>

<p>
<img src="https://github.com/user-attachments/assets/2356b316-2571-48bb-8964-c62e214a80b7" height="80%" width="80%" alt="Part 3 osTicket"/>
</p>

</p>
<p>

The images show how to set up roles, departments, teams, and permissions in the Admin Panel, add agents and users, configure SLA policies, and create help topics like “Password Reset.” Each image illustrates these setup tasks. 
</p>
<br />
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
