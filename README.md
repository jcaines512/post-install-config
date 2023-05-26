# osTicket
Setting up to use osTicket as Admin

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/ZrwgMx8PCec)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<p><h2>Post-Install Configuration Objectives and Steps</h2>

1. Configure Roles
2. Configure Departments
3. Configure Teams
4. Configure Agents
5. Configure Service Level Agreements
6. Configure Help Topics
7. Set to Allow Anyone to Create Tickets
8. Configure Users</p>

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/eYK4iOA.png" height="80%" width="80%" alt="Configure Roles"/>
</p>
<p>
Part 1. Configure Roles

- Upon login, toggle to ADMIN panel
- Select "Agents" from top menu bar
- Select "Roles" from lower menu bar 
- Select "Add New Role" to create as many Roles needed for the organization. 
The Roles are set up according to what access levels each group of members needs depending upon their departments and abilities to assign or close tickets etc. 

</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/vpHHmod.png" height="80%" width="80%" alt="Departments"/>
</p>
<p>
Part 2. Configure Departments

- Upon login, toggle to ADMIN panel
- Select "Agents" from top menu bar
- Select "Departments" from lower menu bar and click to "Add New Department"
From here, choose the appropriate settings that will apply to the access levels for this department. The "Departments" have many different settings which apply to tickets as they are routed through the departments, and determine the visibility as well as whether tickets can be routed to each department. 

</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/jL6xBOj.png" height="80%" width="80%" alt="Configure Teams"/>
</p>
<p>
Part 3. Configure Teams

- Upon login, toggle to ADMIN panel
- Select "Agents" from top menu bar
- Select "Teams" from lower menu bar and click to "Add New Team"
From here, choose the appropriate members for the team and set the access levels that will apply. Configuring Teams will allow Agents from different Departments to be organized to handle a specific issue or user via a Help Topic or Ticket Filter, regardless of the parameters of the Agents' Department rules. 



</p>
<br />

<hr>

<p>
<img src="https://i.imgur.com/truhOnL.png" height="80%" width="80%" alt="Configure Agents"/>
</p>
<p>
Part 4. Configure Agents/Workers

- Upon login, toggle to ADMIN panel
- Select "Agents" from top menu bar
- Select "Agents" from lower menu bar and select "Add New Agent" to add new workers and assign their Departments and Roles. 
Agents are given access to the help desk with the intent to respond and resolve the tickets. Agents working the help desk should be assigned to a Primary Department and given a Primary Role. 

</p><hr>

<p>
<img src="https://i.imgur.com/o35vIgU.png" height="80%" width="80%" alt="Configure SLAs"/>
</p>
<p>
Part 5. Configure SLA

- Upon login, toggle to ADMIN panel
- Select "Manage" from top menu bar
- Select "SLA" from lower menu bar and select "Add New SLA Plan" to choose the appropriate grace period hours and schedule allowed to respond
Service Level Agreements (SLA Plans) are set to provide a length of time for the help desk  workers to close a ticket. 

</p>
<br />
<hr>

<p>
<img src="https://i.imgur.com/PrS8xNs.png" height="80%" width="80%" alt="Add Help Topics"/>
</p>
<p>
Part 6. Configure Help Topics

- Upon login, toggle to ADMIN panel
- Select "Manage" from top menu bar
- Select "Help Topics" from lower menu bar and select "Add New Help Topic" 
Help Topics are created to ensure proper assignment and response of a ticket by assigning specific topics to the proper teams or departments. 

</p>
<br />
<hr>

<p>
<img src="https://i.imgur.com/6VPg6cI.png" height="80%" width="80%" alt="Allow Anyone to Create Tickets"/>
</p>
<p>
Part 7. Configure osTicket to Allow Anyone to Create Tickets

- Upon login, toggle to ADMIN panel
- Select "Settings" from top menu bar
- Select "Users" from lower menu bar
- Choose the appropriate options for "Require registration and log in to create tickets"


</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/dD9Y8O2.png" height="80%" width="80%" alt="Configure Users"/>
</p>
<p>
Part 8. Configure Users/Customers

- Upon login, toggle to AGENT panel
- Select "Users" from top menu bar
- Select "Add User" to create a new User and add their information.
- Choose the appropriate options for "Require registration and log in to create tickets"
Users in osTicket are the customer, or internal member who needs assistance, and is the owner of the ticket. The User is associated with their email address 

</p>
<br /><hr>
