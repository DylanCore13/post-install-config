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

- Configure Roles
- Configure Departments
- Configure Teams
- Enable anyone to create tickets 
- Configure Agents (help desk employees)
- Configure Users (customers)
- Configure Help Topics
- Configure SLA (service level agreements)

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

![image](https://github.com/user-attachments/assets/71d1f311-4d71-4d86-bb10-052bdaf8790f)

You will go to add role and name it Supreme Admin, than you'll see a section somewhere called permissions, check off evey single box in "Ticket", "Tasks", and "Knowledgebase",
than just click add role/create. This will give Supreme Admin full access and control over these permissions.

![image](https://github.com/user-attachments/assets/a310c354-25ed-49c3-8e3c-5bbd746f1044)



Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

Next we will configure departments to view ticket visability, so if a ticket gets assigned to like a specific department 
such as networking, you could configure it so they only can see their own tickets. Maybe a different deparment like SysAdmins can see all tickets.

![image](https://github.com/user-attachments/assets/63f812b3-0dad-4bb7-82b1-759505a2e568)


![image](https://github.com/user-attachments/assets/83eb04c1-da75-49ed-ae5d-7450e5eb4c60)



Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

For teams, the whole point is if you want create like a group of people who are all from different DEPARTMENTS. Example could be if you work at a clothing shop, you'll create a design team that consists of the marketing team members who are responsible for making sure everything looks good to market. Or a Banking team that consists of sysadmins who are responsible for theh online banking system, and some help desk people who help out customers.

![image](https://github.com/user-attachments/assets/8d13a6f4-386e-4d9d-bf24-295655dfdd10)


Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

This setting allows people to create tickets even though their not registered in theh system yet. Like the end users can create their own tickets without having an account.

![image](https://github.com/user-attachments/assets/2c9ff3d0-a6f5-45d5-b9a8-86a67c9d78ca)



Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

You will create a agent named Jane and John. Jane will be in SysAdmins department and with the online banking team. You'll do the same with John but will be with Support department and with won't be with a team.


![image](https://github.com/user-attachments/assets/c7ff4efd-fda0-4d1a-9873-2d5f5256944b)


![image](https://github.com/user-attachments/assets/dfe14490-3865-4f9f-90e3-850012a0c56f)


![image](https://github.com/user-attachments/assets/7becdc94-45d8-45df-8e90-554fa49f49b1)




Configure Users (customers)
Agent Panel -> Users -> Add New
Karen

Know we'll add a user named Karen, remember to switch over to agent panel, and from there click on users and create her.

![image](https://github.com/user-attachments/assets/99e2d51a-1d51-40ba-ba22-6565bad49cb7)


Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

SLAs stand for service level agreement, and its how much time you have to complete a ticket or task. You'll have to go back to Admin panel to configure it. We are going to create 3 SLAs. Sev-A, Sev-B, Sev-C. A being a big problem, B being a bit less than A, and C being a small problem. Go to manage and than click onn SLAs. Than click on add new SLA plan.

![image](https://github.com/user-attachments/assets/1e9fee92-e135-43fd-9385-d81c14c85ff8)

![image](https://github.com/user-attachments/assets/456533c8-8082-4f79-b9a1-b5e15478bd4b)


![image](https://github.com/user-attachments/assets/3c0133de-288f-43d7-9ad5-6be401d88cee)



Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other


Lastly, topics are for when end users are creating a ticket they choose the catagory of the problem/issue.

![image](https://github.com/user-attachments/assets/a91f68b7-9047-4b01-b6c0-bdc1f1d25e97)


![image](https://github.com/user-attachments/assets/70636830-2d2b-4bc4-b7f4-6521b8f89244)

![image](https://github.com/user-attachments/assets/29bb45f6-a6f5-4b99-9622-1d56892d8ffb)



![image](https://github.com/user-attachments/assets/92a5dbc5-53fd-47e3-a86d-41f2401b9673)

![image](https://github.com/user-attachments/assets/f95d708c-ecd4-4187-bbba-0910b4ccb550)








