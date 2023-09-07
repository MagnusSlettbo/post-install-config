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

- Create "Super Admin" Role
- Create "System Admin" Department
- Ticket Submitting settings
- Add Agents
- Create and setup SLA
- Configure Prefix tabs for tickets

<h2>Configuration Steps</h2>

<p>
  <p>
To create the Super Admin role go to the "Admin Panel" in the top right, you will know if you are in the Admin Panel if it says "Agent Panel" in the top right corner, as shown in the picture below. Then go to "Agents" -> "Roles" -> Add new role. In the "Permissions" tab select all the options as this is the Super Admin role wich needs all the accesses available. Then press "Add role".
</p>
<p>
<img src="https://i.imgur.com/hGhqipO.png" height="80%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/VwoYk4R.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<h2>Adding Departments</h2>
<br />
<p>
Now to add Departments, go to the Departments tab like the picture below, click "Add New Department" and add "Level 1 Support" & "Level 2 Support" or what other departments you would want/need.
</p>
<p>
<img src="https://i.imgur.com/nImbIcq.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/aTJMz6k.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Ticket Submitting Setting</h2>
<p>
Now we need to make it so people don't have to login to the ticketing system to be able to submit a ticket. Go to Admin Panel -> Settings -> Users and make sure Registration Required is not selected, unless you want it to be required.
</p>
<p>
<img src="https://i.imgur.com/FUwZBCD.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Adding Agents</h2>
<p>
Now we need to create some agents that can work cases for us, To do this go to Admin Panel -> Agents -> Add New and just fill in the information needed for the agents. Then go to the Access tab and select the Department the Agent should belong to and his permissions.
</p>
<p>
<img src="https://i.imgur.com/genQpOW.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/yishdcb.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>Now we have created two agents "Jim" & "John" and assigned them to their departments</p>
<img src="https://i.imgur.com/uKsdAmQ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />

<h2>SLA Setup</h2>
<p>
In this Helpdesk we will use SLA in our ticket system. To set this up go to Admin Panel -> Manage -> SLA "Add New SLA Plan. Let's add 3 different SLAs with the settings set up by the organization or manager.
</p>
<p>
<img src="https://i.imgur.com/OdrK7QF.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/jeNrBet.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/jNyH10w.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Help Topics</h2>
<p>
The final thing to do now is add Prefix to the tickets to help aid the end users to filter easier what their problems are. To do this go to Admin Panel -> Manage -> Help Topics
  Let's add 3 Help Topics: Business Critical, Equipment Request, and Password Reset.
</p>
<p>
<img src="https://i.imgur.com/72vE9xR.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/oOfaxiC.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  <p> Here we can see the Help Topics in use in the Support Ticket submission form</p>
  <img src="https://i.imgur.com/Eqwznk6.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<br />
