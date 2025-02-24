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

- Configure Basic Settings
- Set Up Ticket Categories & SLA Plans 
- Create Departments & Roles



<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/M2AODxT.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step of the post installation, we are going to configure the basic osticket settings we would like to have changed. Some examples include: 

Configure your helpdesk name, default system email, time zone, and language preferences under Admin Panel → Settings → System.
</p>
<br />

<p>
<img src="https://i.imgur.com/EvNg5bn.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step we are going to configure Roles, along with the users in each Role. Once you have your users located within the correct Roles, you may begin adding permissions to these Roles. You can see from the screenshot what type of permissions you will be able to deny or allow within the department. 
</p>
<br />

<p>
<img src="https://i.imgur.com/vJNpIZf.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we can begin creating the SLA agreements for different categories of tickets. SLA meaning Service Level Agreement, are different tiers of ticket escalation based on severity. With these different tiers you can change how long after a ticket is created until it needs to be assigned or claimed. You can also manage the days / times of the week that these ticktes will be activated. IE: severe level tickets might be active 7 days a week even outside of standard business hours. 
</p>
<br />

<p>
<img src="https://i.imgur.com/iLDj3tk.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step we are going to configure Departments, this will allow you to put users in the correct Department for their Roles within osTicket. Once you have configured the Departments. You can then assign the Roles to the Departments.
To locate this area of osTicket follow these steps as described: 
  
<ins> **Access the Admin Panel**</ins>   

➤ Log in to your osTicket system using an admin account.
  
 <ins> **Navigate to Agent Management**</ins>   
 
 ➤ In the left-hand menu, click on Agents. 
 
 ➤ Select Roles from the dropdown menu.

   <ins> **View or Create a Role**</ins>   
   
   ➤ To view or edit an existing role, click on the role name. 
   
   ➤ To create a new role, click the Add New Role button at the top-right.

   <ins> **Configure Role Permissions**</ins>
➤ Enter a Role Name (e.g., Support Agent, Manager).

➤ Adjust permissions under the following sections:

➤ Tickets – Control access to ticket creation, assignment, and management.

➤ Tasks – Manage task-related permissions.

➤ Knowledgebase – Set permissions for article creation and editing.

➤ Configuration – Grant or restrict access to system settings.
</p>
<br />
