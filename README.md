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

- Roles
- Departments
- Teams
- Agents
- Users(Customers)
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/znir9TC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you have installed osTicket, its time for the Post Installation Setup. We are first going to start with configuring Roles. On the admin panel, go to Agents-> Roles -> add new role. Name the role "Supreme Admins" and then click on Permissions and check all the boxes so that the System Admins have complete control.
</p>
<br />

<p>
<img src="https://imgur.com/fmLUiNY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, lets configure Departments, first go to Admin Panel -> Agents -> Departments -> Add New Department. You can name it "System Administrators".
</p>
<br />

<p>
<img src="https://imgur.com/xfGLo9O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure Teams go to Admin Panel -> Agents -> Teams. 
</p>
<br />

<p>
<img src="https://imgur.com/ck0W1EP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To allow anyone to create tickets go to Admin Panel -> Settings -> User Settings -> Registration Required.
</p>
<br />

<p>
<img src="https://imgur.com/cV0XW3B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, lets add some Agents(workers). To do this, navigate to Admin Panel -> Users -> Add New.
</p>
<br />

<p>
<img src="https://imgur.com/4N8Zw69.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add Users(workers) go to Agent Panel -> Users -> Add New.
</p>
<br />

<p>
<img src="https://imgur.com/DmDeiGn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, lets configures SLA. SLA plans, or Service Level Agreement, provide a length of time in which help desk admins expect tickets to be closed. To configure go to Admin Panel -> Manage -> SLA -> Add New SLA. Create 3 new SLA plans.
</p>
<br />


<p>
<img src="https://imgur.com/VneM3Hu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, lets configure help topics, to do this go to Admin Panel -> Manage -> Help Topics. Add the following topics: Business Critical Outage, Personal Computer Issure, Equipments Request, Password
</p>
<br />

