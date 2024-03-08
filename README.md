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

- Roles,permissions and etc.
- Configuring agents
- configuring help topics


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/UtXpd8G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to OSTICKET go to ->admim panel->agents->roles->add new role->"supreme admin". Now that I have created the supreme admin role I will give them all permissions in the catergories tickets, task, and knowledgebase. Next is to configure department so admin panel->agents->department and add new department select all default name "System Administrator". Confuguring teams admin panel->settings->authentication settings->name level II support" and make yourself the team leader. Allow everyone to make tickets admin panel->settings->users->require registration and start to make tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/EzlWc1s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure agents by ->admin panel->agents->agents and we will add 2 agents "Jane" "Doe" and "John" "Doe". We are going to make "Jane" "doe" level II support, system adminstrator, and supreme admin. "John" "doe" will be support and both of them will have password1 so we're able to login to them. To make some customers for the next example we are going to configure users agent panel->users-> add new which will be "Karren" "Karren" and "Ken" "Ken". These will be the customers that make tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/8xptgCw.png"80%" width="80%" alt="Disk Sanitization Steps"/>
</p> Last things I will do is confuguring SLA and configuring help topics. I will start with SLA by going to admin panel->manage->SLA and then make 3 SLA plan like Sev-A(1 hour, 24/7), Sev-B(4 hours, 24/7) and Sev-C(8 hours, business hours). To configure help topics open admin panel->manage->help topics-> and create business critical out rage, personal computer issue, equipment request, and password reset.
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
