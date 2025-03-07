<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- End Users osTicket URL: http://localhost/osTicket 


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Gain a basic understanding of Ticketing systems and their functionality.
- Learn to manage and configure osTicket in a professional environment.
- Practice visualizing the soft skills neccessary for success. (i.e. time management, written communication)

<h2>Configuration Steps</h2>

<p><en>Note the many differences between the Agent Panel and Admin Panel</en></p>
<p><strong>Admin Panel:</strong> Full control over settings, roles, departments, and system-wide configurations.</p>
<p><strong>Agent Panel:</strong> Used by support agents to mangage and respond to tickets.</p>

<h3>Set up Agents and Roles</h3>
<img src='https://github.com/user-attachments/assets/a1122ab0-efe5-45c6-af39-ca25c1e7b3a7' />
<ul>
<li>Path: Admin Panel → Agents → Roles</li>
<li>Create Roles to define permissions (e.g., Supreme Admin).</li>
<li>Assign Agents to Departments for ticket visibility (e.g., Jane → SysAdmins, John → Support).</li>
<li>Group Teams across departments for collaboration (e.g., Online Banking).</li>
</ul>
<br />


<h3>Configure User Access & Ticket Creation</h3>
<img src='https://github.com/user-attachments/assets/a6bc3fed-47f9-4551-8021-906636a7f5e7' />
<ul>
  <li>Path: Admin Panel → Settings → User Settings</li>
  <li>Allow public ticket creation (Uncheck "Require registration") or enforce login.</li>
  <li>Add Users (Customers) in Agent Panel → Users (e.g. Karen, Ken).</li>
</ul>
<br />

<h3>Define Ticket Categories & SLAs</h3>
<img src='https://github.com/user-attachments/assets/29f5bc0e-024d-4459-8a53-0dfd8c6a4a0e' />
<ul>
  <li>Add Users (Customers) in Agent Panel → Users (e.g., Karen, Ken).</li>
  <li>SLA Plans: Admin Panel → Manage → SLA</li>
</ul>
<p>  - Sev-A (1-hour response, 24/7)</p>
<p>  - Sev-B (4-hour response, 24/7)</p>
<p>  - Sev-C (8-hour response, business hours)</p>
<br />
