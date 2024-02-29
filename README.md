<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install process of OsTicket. We are going to create some arbitrary roles and rules to simulate the help desk environment. This tutorial is relatively straightforward and intuitive compared to the initial installation process. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure roles, departments, and teams
- Create agents and users
- Create SLA
- Create potential help topics
  
![Screen Shot 2024-02-29 at 4 37 26 PM](https://github.com/Chillsoda/post-install-config/assets/161760771/d0c236be-18e5-418a-a10e-508150af0c41)

<h2>Configuration Steps</h2>

1.) Configure Roles:

Access the Admin Panel and navigate to Agents > Roles to configure roles. Create the role of Supreme Admin that has permission to do everything within your help desk environment.

2.) Configure Departments:

 Navigate to Agents > Departments to configure departments. Create the System Admin department.

3.) Configure Teams:

Navigate to Agents > Teams to configure teams. Create level 1 and two support teams.

4.) Allow Anyone to Create Tickets:

Go to Settings > User Settings and set "Registration Required" to require registration and login to create tickets.

5.) Configure Agents (workers) and Users (customers):

Admin panel> Add agents and users under the Agents and Users sections, respectively. Create add new and create agents John Doe and Jane Doe. Then go to the agent panel and create customers Karen Smith and Ken Smith. Make sure to give your agents permissions that will allow them to view and work the tickets; give one the rule of supreme admin.

6.) Configure SLA:

Access Manage in Admin panel > SLA to configure Service Level Agreements. Create SEV A, B, and C SLA tiers. 

7.) Configure Help Topics:

Admin panel> Manage > Help Topics to configure different help topics. Create Business Critical Outages, Personal Computer Issues, Equipment Reset, and Password Reset help topics. 

Finish! After this, we are ready to play around and create tickets in osTicket and "resolve" them. You are also welcome to create additional users, roles, help topics, etc. 

![Screen Shot 2024-02-29 at 5 40 31 PM](https://github.com/Chillsoda/post-install-config/assets/161760771/a846010a-e8b1-4bdd-b34e-0af93c5ac856)



