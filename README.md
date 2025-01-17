<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>


<h2>Configuration Steps</h2>

1) Configuring Roles
2) Configuring Departments
3) Configuring Teams
4) Ticket Permission
5) Configuring Agents
6) Adding New Users
7) Configuring SLA's (Service Level Agreements)
8) Creating Help Topics

<h3> 1) Configuring Roles</h3>

<p>In this step, I will be showing you how to configure roles to your employees/admins. First login to your Admin account with this link : "http://localhost/osTicket/scp/login.php". Once you are logged into your admin account, on the top right of the page you will see either "Agent Panel" or "Admin Panel". Make sure you are in the "Admin Panel", then go to "Agents" -> "Roles". This will show you the roles you have by default, but it also shows you how to edit certain roles and how to create certain roles. </p>

<p>
<img src="https://i.imgur.com/4YWjpPw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3> 2) Configuring Departments</h3>

<p>If you are wanting to create certain departments and permissions within these departments, after you have created your roles you can select the "Departments" option just to the right of the "Roles" option. This will bring you to the "Add New Department" window within the Admin Panel, Select "Add New Department and punch in the information you see as fit for the department you are creating. Once you are done creating your department, you can then press the "Create Dept" button on the bottom of the page.</p>

<img src="https://i.imgur.com/DUSkjV2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4opS7aY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3> 3) Configuring Teams</h3>

<p>The purpose of creating "Teams" is to help you categorise people that are in different departments (For Example: Online Banking). To find "Teams", go to where you found the "Departments" Column and on the left you will see a "Teams" column. Select "Add New Team". This is where you can create "Teams" within OsTicket. </p>

<img src="https://i.imgur.com/beJJui0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sC7KfIB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3> 4) Ticket Permission</h3>

<p>This next step will allow anyone to create a ticket even if they are not in the system. To do this you will need to be in the "Admin Panel" and select "Settings" -> "User Settings" -> and make sure to <b>UNCHECK</b> "Require registration and login to create tickets". Make sure to save changes when you are done.</p>

<img src="https://i.imgur.com/Aiy83sH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3> 5) Configuring Agents</h3>

<p>In this step you will learn how to add "Agents" in OsTicket. First you will need to be in your "Admin Panel", go to "Agents" -> "Add New Agent"</p>

<img src="https://i.imgur.com/eTNky7o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>In this step, I will be creating 2 new agents but, you can make as many as you need. You can also assign "Access", "Permissions" and "Teams" to this new agent while you are creating them. </p>

<img src="https://i.imgur.com/djXrSwE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3> 6) Adding New Users</h3>

<p>In this step, we will go over how to create user accounts for clients. Make sure you are in "Agent Panel" (which can also be classified as "Staff Control Panel"), Go to "Users" and "Add User".</p>

<img src="https://i.imgur.com/aYjjVS4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3> 7) Configuring SLA's (Service Level Agreements)</h3>

<p>This step will include creating your SLA's specific to your company. this will help delegate the severity of your tickets, how long it will take to finish your tickets and what schedule your tickets will be listed on. First switch back to your "Admin Panel", then go to "Manage" -> "SLA" and "Add New SLA Plan".  </p>

<img src="https://i.imgur.com/B2CFz7s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>We will be creating 3 different SLA's in this tutorial :</p> 
<p>Sev-A (Grace Period: 1 hour, Schedule: 24/7)</p>
<p>Sev-B (Grace Period: 4 hours, Schedule: 24/7)</p>
<p>Sev-C (Grace Period: 8 hours, Business Hours)</p>

<img src="https://i.imgur.com/h7c9392.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3> 8) Creating Help Topics</h3>

<p>Help Topics are what your users and employees will use to help categorise your tickets. For Example: One of your admins is having computer issues, we can list a ticket under "Personal Computer Issues" so that when someone opens that ticket, they have a general understanding on what that ticket is about.</p>

<p>In order for you to get to creating your "Help Topics", you will need to be in the "Admin Panel" -> "Manage" then go to "Help Topics" and click on "Add New Help Topic".</p>

<img src="https://i.imgur.com/xBiVw0n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>By default, you will already have some "Help Topics" available. If you choose to, you can either leave them or delete them by clicking the checkmark box on the left of the topic, going over to "More" on the right, clicking the down arrow and selecting "Delete".</p>

<img src="https://i.imgur.com/wsDdFdc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>This concludes our OsTicket Post Installation Proccess! Congratulation and I hope this helped!</p>

</p>
<br />
