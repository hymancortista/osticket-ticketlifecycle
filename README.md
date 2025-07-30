<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Configure Roles (for grouping permissions)<br />
Admin Panel -> Agents -> Roles<br />
- Supreme Admin

![image](https://github.com/user-attachments/assets/70bfd30f-40e3-4a33-b1b2-f668249f7b66)


Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)<br />
Admin Panel -> Agents -> Departments<br />
- SysAdmins

![image](https://github.com/user-attachments/assets/d92f20bc-2342-415d-b072-73579e9d2086)


Configure Teams<br />
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)<br />
- Online Banking

![image](https://github.com/user-attachments/assets/f0ae051f-8cde-4561-bf0d-185ffe22bb12)


Allow anyone to create tickets<br />
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)<br />
- Registration Required: Require registration and login to create tickets 

![image](https://github.com/user-attachments/assets/9e0108e9-d18b-4cd7-bec8-8ab979ce9b7b)


Configure Agents (workers)<br />
Admin Panel -> Agents -> Add New<br />
- Jane (Dept: SysAdmins)
- John (Dept: Support)

![image](https://github.com/user-attachments/assets/6da590c5-3a46-47d8-b14f-e6ae5175d9d2)


Configure Users (customers)<br />
Agent Panel -> Users -> Add New<br />
- Karen
- Ken

![image](https://github.com/user-attachments/assets/de38f8d9-efaf-41b4-960a-57474e9405f6)


Configure SLA<br />
Admin Panel -> Manage -> SLA<br />
- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)

![image](https://github.com/user-attachments/assets/563f43e4-5619-4894-8045-9d0f855d4996)


Configure Help Topics (For when users create a ticket)<br />
Admin Panel -> Manage -> Help Topics<br />
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other

![image](https://github.com/user-attachments/assets/aa985b4f-c5d2-4127-ae0d-e33150ca1611)

Now on to working on Tickets and their Ticket Lifecycle
