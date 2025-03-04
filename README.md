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

- Remote Desktop
- osTicket Local Host Site
- osTicket Login Page

<h2>Configuration Steps</h2>

<p>
  
![step 1 create supreme admin role](https://github.com/user-attachments/assets/4622649c-ae91-41a1-9999-6388132022b2)

</p>
<p>
First had to configure Roles for grouping permissions. Created Role named "Supreme Admin."
</p>
<br />

<p>
  
![step 2 create department sysadmin](https://github.com/user-attachments/assets/c45364a8-cbf9-4c58-91da-3982f3a2f84c)

</p>
<p>
Next, I configured a Department for "SysAdmins."
</p>
<br />

<p>
  
![step 3 create team online banking](https://github.com/user-attachments/assets/1ef9fa59-905c-4877-8f33-a1c69b673e40)

</p>
<p>
Configured Teams (Pulling Agents from different Departments). The Team was named "Online Banking."
</p>
<br />

<p>
  
![step 4 create agents](https://github.com/user-attachments/assets/605b3602-ad89-47ee-86c6-f54d3f46b059)

![step 4 create agents cont](https://github.com/user-attachments/assets/bc00d616-70c3-43b6-b7eb-d08202fb41ee)

</p>
<p>
Configured Agents, which are workers. The Agents I created went by the names of Jane and John.
</p>
<br />

<p>
  
![step 5 create user](https://github.com/user-attachments/assets/6a4f21dd-0ab8-442c-9669-77bbd8277e8d)

</p>
<p>
Then, I created a User, which is a customer by the name of Karen.
</p>
<br />

<p>
  
![step 6 adding different level of SLAs](https://github.com/user-attachments/assets/8ab9d029-359e-4d3e-ad09-5228e2ea13e9)

</p>
<p>
Created 3 levels of SLAs.
- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />

<p>
  
![step 7 adding help topics](https://github.com/user-attachments/assets/9fdb4e4b-ce01-4bef-aded-54cf8056b627)

![step 7 help topics finished](https://github.com/user-attachments/assets/e57d5be3-f2af-4869-b0f7-4420c0df3c55)

</p>
<p>
Lastly, I configured Help Topics (for when users create a ticket). These are the Topics I created:
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other
</p>
<br />
