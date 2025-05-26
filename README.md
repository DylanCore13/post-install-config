# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket installer
- osTicket Admin Control Panel

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure "Roles"
- Configure "Departments"
- Configure "Teams"
- Enable anyone to create tickets 
- Configure "Agents" (i.e. help desk employees)
- Configure "Users" (i.e. customers)
- Configure "Help Topics"
- Configure "SLA" (service level agreements)

<h2>Configuration Steps</h2>

Log in to your osTicket panel that you installed in last lesson (pre-requisites and installation)

![image](https://github.com/user-attachments/assets/c50351f7-58c0-4db7-b4ae-27a6e744a814)


Once you are logged in, acknowledge/view/familarize yourself with the AGENT and ADMIN panel.
Notice how in Admin panel its shows a few configurations such as "Dashboards", "settings", "Manage", "Emails", and "Agents".
All of this is to configure settings on the backend for osTicket. If you click agent panel, this is if you're a help desk helper/worker.

![image](https://github.com/user-attachments/assets/03b1e98f-9a50-41ad-9d6e-18849ecd938d)

![image](https://github.com/user-attachments/assets/02a4ff62-eaad-4a58-9593-462b7ce9799f)


Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other




