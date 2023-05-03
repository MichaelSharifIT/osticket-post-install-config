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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/KLZhLZE.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Roles</h3>
Admin Panel -> Agents -> Roles

- Supreme Admin

</p>
<br />

<p>
<img src="https://i.imgur.com/P3U9XxP.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Departments</h3>
Admin Panel -> Agents -> Departments

- System Administrators

</p>
<br />

<p>
<img src="https://i.imgur.com/FYYQR1G.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Teams</h3>
Admin Panel -> Agents -> Teams

- Level I Support
- Level II Support

</p>
<br />

<p>
<img src="https://i.imgur.com/ddSl6eY.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Allow anyone to create tickets</h3>
Admin Panel -> Settings -> User Settings

- Registration Required: Require registration and login to create tickets 


</p>
<br />


<p>
<img src="https://i.imgur.com/eN4r0B9.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Agents (workers)</h3>
Admin Panel -> Agents -> Add New

- Jane
- John


</p>
<br />

<p>
<img src="https://i.imgur.com/cMqsczQ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Users (customers)</h3>
Agent Panel -> Users -> Add New

- Karen
- Ken


</p>
<br />

<p>
<img src="https://i.imgur.com/sJRTN2I.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure SLA</h3>
Admin Panel -> Manage -> SLA

- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours)


</p>
<br />

<p>
<img src="https://i.imgur.com/vbf6T5u.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Help Topics</h3>
Admin Panel -> Manage -> Help Topics

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset



</p>
<br />
