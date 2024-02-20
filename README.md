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

- Configure osTicket for agent and customer use

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/494a5ec1-5428-4f47-943b-c7224856b6ec" height="60%" width="60%" alt="Roles"/>
</p>
<p>
In osTicket log in as admin and add a new role named Supreme Admin by going to Admin Panel -> Agents -> Roles 
</p>
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/93d141d6-cff6-4a33-b4f0-e38ba924a3a8" height="60%" width="60%" alt="Departments"/>
</p>
<p>
Add a new department named System Administrators by going to Admin Panel -> Agents -> Departments
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/bda51587-fab8-439d-b8df-1a5b9632769c" height="60%" width="60%" alt="Teams"/>
</p>
<p>
Create Level I and II Support teams by going to Admin Panel -> Agents -> Teams
</p>
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/8ced9994-0200-4fe5-a7a7-653467ace3ec" height="60%" width="60%" alt="Ticket creation settings"/>
</p>
<p>
Under Authentication Settings check "Require registration and login" to create tickets to allow anyone to create a ticket by going to Admin Panel -> Settings -> User Settings
</p>
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/73614467-68f0-419d-89d7-d72ef2808b83" height="60%" width="60%" alt="admins"/>
</p>
<p>
Create 2 workers assigning them Administrator and Supreme Admin access by going to Admin Panel -> Agents -> Add New
</p>
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/bd922621-9292-47b9-88a7-7a94d68fac2b" height="60%" width="60%" alt="users"/>
</p>
<p>
Create 2 customers by going to Agent Panel -> Users -> Add New
</p>
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/9465b66a-5b90-4ae6-b226-89b7f8113a68" height="60%" width="60%" alt="sla"/>
</p>
<p>
Create 3 SLA's by going to Admin Panel -> Manage -> SLA
</p>
<br />

<p>
<img src="https://github.com/krystalcherry/post-install-config/assets/158524799/aee0131c-6d52-4d95-920e-796b43b9703f" height="60%" width="60%" alt="help topics"/>
</p>
<p>
Add Help Topics in Knowledge Base by going to Admin Panel -> Manage -> Help Topics
</p>
<br />
