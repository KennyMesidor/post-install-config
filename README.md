# post-install-config

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system, osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/sx170cG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Great! With osTicket successfully configured, the next step is to begin system administration tasks—starting with creating and configuring new roles within the help desk. This will help you manage user access and permissions more effectively.
</p>
<br />

<p>
<img src="https://i.imgur.com/DAhGSan.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create new roles within the help desk, navigate to Admin Panel → Agents → Roles. Select “Add New Role” and enter the desired role name, such as Supreme Admin. From there, you can define the role’s permissions and responsibilities. Since this will function as a Supreme Admin role, enable all available permissions to grant full administrative access across the system.
</p>
<br />

<p>
<img src="https://i.imgur.com/KzFVjJQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Agents tab, select “Departments.” From here, you can create new departments and assign agents based on their responsibilities within the help desk. Create a department called System Administrators, which will serve as the designated department for Supreme Admins. You can further customize settings—such as SLAs, department managers, and email configurations—within the Departments section to match your help desk’s operational requirements.
</p>
<br />

<p>
<img src="https://i.imgur.com/ob4MEma.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To set up teams, go to Admin Panel → Agents → Teams. Teams allow agents from different departments to work together on shared responsibilities. Create a team called Level II Support and add agents from various departments as needed to support cross-functional collaboration.
</p>
<br />

<p>
<img src="https://i.imgur.com/TcRrhwN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To enable anyone to submit tickets, navigate to Admin Panel → Settings → User Settings. Uncheck the option labeled “Require registration and login to create tickets.” This will allow unregistered users to create tickets without needing an account.
</p>
<br />

<p>
<img src="https://i.imgur.com/dwAhP3I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To set up agents, navigate to Admin Panel → Agents → Add New. Enter the required information—such as the agent’s name, email address, assigned role, and department—to create their profile and define their permissions within the help desk.
</p>
<br />

<p>
<img src="https://i.imgur.com/aYLnu3z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add users (customers), navigate to Agent Panel → Users → Add New. Create users such as Ryu and Ken by entering their names, email addresses, and any other required details. This will allow them to submit tickets and track their support requests.
</p>
<br />

<p>
<img src="https://i.imgur.com/YXWfwh8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To set up help topics for user ticket submission, go to Admin Panel → Manage → Help Topics. These topics help users categorize their requests properly when creating new tickets.

</p>
<br />
