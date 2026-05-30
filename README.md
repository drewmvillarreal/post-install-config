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

- Windows 11 Pro </b> (25H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (for when users create a ticket)

<h2>Configuration Steps</h2>

<p>
1. Connect to your virtual machine using remote desktop connection app. 
</p>
<p>
<img width="399" height="239" alt="image" src="https://github.com/user-attachments/assets/a8cac344-79c4-4e1c-824a-17880b2c22c1" />
</p>

 <p>
2. Log in to the Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 
 </p>
 <p>
<img width="247" height="177" alt="image" src="https://github.com/user-attachments/assets/e9f92cad-d59d-48cd-ae8c-20575a00974e" />
 </p>
 <p>
<img width="578" height="212" alt="image" src="https://github.com/user-attachments/assets/2a95ae31-1228-4c93-b5ba-b7bdfdbf1797" />

</p>

<p>
3. Configure roles for grouping permissions. 
  
Click on Admin Panel within osTicket

<img width="578" height="212" alt="image" src="https://github.com/user-attachments/assets/dd8d4f2d-5fbf-410d-b463-db0160d45ef3" />

</p>

<p>
  Click on Agents -> Roles -> Add New Role and name it Supreme Admin
</p>
<p><img width="587" height="253" alt="image" src="https://github.com/user-attachments/assets/ff956d75-1b1d-407c-9773-63427fb99b44" />
</p>

<p><img width="579" height="346" alt="image" src="https://github.com/user-attachments/assets/8b7cfc3c-8f4d-41ef-a0cd-aceaa78fdf28" />
</p>

<p> Click on Permissions and check all permissions under Tickets, Tasks, and Knowledgebase, then click Add Role at the bottom</p>
<p><img width="582" height="428" alt="image" src="https://github.com/user-attachments/assets/5aec4937-3366-4fb4-abaa-c8bd59bcc279" />
</p>
<p><img width="583" height="338" alt="image" src="https://github.com/user-attachments/assets/b0fe903d-afca-428c-9e5e-9f7a50617866" />
</p>
<p><img width="579" height="249" alt="image" src="https://github.com/user-attachments/assets/cd96d2b6-c6f4-439b-803e-ab62637922f2" />
</p>

<p> Supreme Admin role has now been created</p>
<p><img width="572" height="268" alt="image" src="https://github.com/user-attachments/assets/a029f85f-6685-4303-8937-c202a576b4ce" />
</p>

End Users osTicket URL:
http://localhost/osTicket 


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

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
