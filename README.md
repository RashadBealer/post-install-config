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

- Azure Virtual Machine with osTicket Installed: Ensure you have an Azure VM with osTicket installed following the initial installation tutorial.
- Remote Desktop Connection: Use Microsoft Remote Desktop to connect to the Azure VM.
- Internet Information Services (IIS): IIS should be installed on the Azure VM, serving as the web server for osTicket.
    
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Navigate to Admin Panel:

Open a web browser on the Azure VM or your local machine.
Navigate to the osTicket admin panel using the URL of your osTicket installation (e.g., http://localhost/osticket/scp).
</p>

<p>
  Log In:

Log in with the administrator credentials created during the osTicket installation.
</p>

<pUpdate General Settings:
In the osTicket admin panel, go to "Admin Panel" > "Settings" > "General".
Review and update general settings such as the site name, default department, and default help topic.</p>

<p>
  Configure Email Settings:
Navigate to "Admin Panel" > "Settings" > "Email".
Ensure that email settings are correctly configured for sending and receiving ticket-related emails.</p>

<p>
  Adjust Ticket Settings:
Under "Admin Panel" > "Settings" > "Tickets," configure default ticket status, priorities, and other relevant options.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Customize Ticket Forms:
Tailor ticket forms to gather specific information from users. Visit "Admin Panel" > "Manage" > "Forms" to add, edit, or remove custom ticket forms.
</p>

<p>
  Add Staff Members and Teams:
Go to "Admin Panel" > "Staff" to add support staff members and organize them into teams for efficient ticket assignment.
</p>

<p>
  Adjust Department Settings:
Under "Admin Panel" > "Manage" > "Departments," customize department names, email addresses, and permissions.
</p>

<p>
  Create Knowledge Base Articles:
Go to "Admin Panel" > "Manage" > "Knowledge Base" to create and organize articles for users to find solutions independently.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Ticket Filters and Rules:
Enhance automation by configuring ticket filters and rules. Go to "Admin Panel" > "Manage" > "Ticket Filters" and "Ticket Rules" to set conditions for automatic actions.</p>
  
<p>
  Generate Reports:
Leverage osTicket's reporting capabilities to analyze ticket data. Explore "Admin Panel" > "Reports" to generate reports on ticket activity, response times, and more.
</p>

<p>
  Customize Email Templates:
Personalize email communication by customizing templates. Navigate to "Admin Panel" > "Settings" > "Email" > "Templates" to edit email templates for various ticket-related notifications.</p>

<p>
  Customize User Portal:
Enhance the user experience by customizing the user portal. Navigate to "Admin Panel" > "Settings" > "User Interface" to make visual adjustments.
</p>

<p>
  Implement Security Measures:
Secure your osTicket installation by following security best practices. This includes regular backups, using HTTPS, and restricting access to sensitive areas.
</p>
<br />
