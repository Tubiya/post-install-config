<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=4kEQtECcO-U)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1 Configure Roles
- Item 2 Configure Departments
- Item 3 Configure Teams
- Item 4 Configure Agents 
- Item 5 Configure Users
- Item 6 Configure SLA
- Item 7 Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="403" alt="image" src="https://github.com/user-attachments/assets/1e0020e9-7b01-4cca-9c2d-1d1ea0d7dc4d" />
</p>

<p>
Alright first login as Admin so we can acknowleged agent panel vs admin panel
  Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles then click on add new role name it Supreme Admin then go to Premissions check everything then click add role. Now you must configure a few more go to Departments click add new Department make it SysAdmins. (FOR
  testing) Next go to click add new team and make this Online Banking (For testing).Now add some Agents click Agents then add new. Name Agent whatever you want now put this Agent in Dept: SysAdmins. Make another Agent, name them whatever you
  want and put them in Dept: Support
</p>
<br />

<p>
<img width="446" alt="image" src="https://github.com/user-attachments/assets/0b6841bd-d7c2-45a9-a18f-422dac411a9b" />
</p>

<p>
 Add some users, go to the top right and click Agents Panel and og top the Users tab the click add users name him/her whatever then make one more user   
</p>
<br />

<p>
<img width="443" alt="image" src="https://github.com/user-attachments/assets/1903f023-1362-46d8-8b52-8aaead846ebb" />
</p>

<p>
Now lets configure SLA (Service Level Agreement). Make sure that you are on the Admin Panel then the Mansge tab and SLA click add new SLA plan. Make the name Sev-A Grace Period 1 hour Schedule 24/7.
  Next make two more new plans Sev-B Sev-C. Sev-B should be an Grace Period: 4 hours, Schedule: 24/7. Sev-C an Grace Period: 8 hours, Business Hours.
</p>
<br />

<p>
<img width="403" alt="image" src="https://github.com/user-attachments/assets/9eb841b4-cf9b-4c51-a1c5-4eb9dbc0f967" />
</p>
<p>
Configure Help Topics (For when users create a ticket)
Go to Admin Panel -> Manage -> Help Topics
Creat these new Help Topics,
- Business Critical Outage 
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other
</p>
<br />
