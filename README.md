<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This demonstration outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Utilized</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Utilized</h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Role Configuration
- Department Configuration
- Team Configuration
- Item 4
- Item 5

<h1>Ticketing System Configuration Tutorial:</h1>

<h2>Step 1. Access Admin Panel</h2>

<p>
<img src="https://i.imgur.com/lTZJbA2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login into osTicket using this link http://localhost/osTicket/scp/login.php using the credentials you created in the installation tutorial. If you are already logged in, select the Admin Panel in the top right area of the page next to "Welcome, (your name)". You should end up on this page.  
</p>
<br />

<h2>Step 2. Configure Roles for Grouping Permissions</h2>

<p>
<img src="https://i.imgur.com/o5xmLvw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click the Agents tab then click Roles. You should see different levels of access. Clicking on them will allow you to rename said role in the Definition tab, and assign different permissions in the Permissions tab. To create new roles, click the Role tab and click Add New Role on the right side. This will prompt you to name your new role in the Definition tab, as well as assign permissions in the Permission tab. The name of the role for this demonstration is "Supreme Admin Role". Give this role all permissions. Once you are finished click the yellow Add Role button at the bottom of the page. 
</p>
<br />

<h2>Step 3. Configure Departments for Ticket Visibility</h2>

<p>
<img src="https://i.imgur.com/js5sUxt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Departments under the Manage tab and click the Add New Departments button on the right side. Fill in correalating information in the appropriate fields. A SysAdmin department will be created for this demonstration. Once complete, scroll down and press the yellow Create Dept button to create a new Department. 
</p>
<br />

<h2>Step 4. Configure Teams for Collaboration</h2>

<p>
<img src="https://i.imgur.com/45cbhc4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Teams, and then click the Add New Team button on the right side. Rename and configure the team in the Team tab, and add members to the team in the Members tab. In this demonstration the team will be called Online Banking. click the yellow Create Team button on the bottom once it's done. 
</p>
<br />

<h2>Step 5. Allow for Ticket Creation</h2>

<p>
<img src="https://i.imgur.com/QJqLUx9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Settings, then Users, and make sure the "Require registration and login to create tickets" box is unchecked. This allows for users without accounts to create tickets without registration.  
</p>
<br />

<h2>Step 6. Configure Agents</h2>

<p>
<img src="https://i.imgur.com/E9DYa7h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Agents and click on the Add New Agent button on the right side. In this demonstration two agents will be created. Fill in their information and credentials as you see fit. Make sure to set passwords for each. Have one agent become a part of the SysAdmin department as a Supreme Admin in the Online Banking team. Have the other be Support with the View Only permission. Once you're finished press the yellow Create button in the Teams tab next to the Permissions tab.    
</p>
<br />

<h2>Step 7. Configure Users</h2>

<p>
<img src="https://i.imgur.com/nkNi8CL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the Agent Panel on the top right side of the page. Once there click Users, and then click Add Users on the right side of the page. Fill in the appropriate information and click Add User on the bottom right corner of the User configuration box.     
</p>
<br />

<h2>Step 8. Configure SLAs</h2>

<p>
<img src="https://i.imgur.com/nkNi8CL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the Admin Panel on the top right side of the page. Once there click Manage, and then click SLA and press Add New SLA Plan on the right side of the page. Fill in the appropriate information and click Add User on the bottom right corner of the User configuration box. In this demonstration three SLA plans will be created. The first will be named Sev-A, grace period will be 1 hour, and schedule will be 24/7. The next will be Sev-b, 4 hour grace period, and 24/7 schedule. The last will be Sev-C, 8 hour grace period, and schedule will be business hours so Monday-Friday 8am to 5pm. Press the yellow Add Plan at the bottom of the page to create each one.     
</p>
<br />

<h2>Step 9. Configure Help Topics</h2>

<p>
<img src="https://i.imgur.com/0i7V00j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Manage tab you are already in, click Help Topics and add five new Help Topics. They will be named Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and other. For Business Critical Outage, Personal Computer Issues, and Password Reset, set the parent topic to Report a Problem. Set the others to General Inquiry. Click the yellow "Add Topic" button to create each Help Topic. This is the end of the tutorial for the post installation configuration for the osTicket ticketing software.     
</p>
<br />
