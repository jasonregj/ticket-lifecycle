<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/zLQLpCN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we'll simulate an external user/guest creating a ticket from the localhost site. We will assign tickets as an administrator to an agent based on the help topic and respond as the agent with resolution and close the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/gFHsP2m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We've logged in as "Jane" one of the administrators we configured. We can see all the open tickets by date/time (intake). All the tickets are prioritized as normal so the smart move here would be to open each time by intake time and prioritize (make sure SLA makes sense) each from there. 
</p>
<br />

<p>
<img src="https://i.imgur.com/UZXTpXl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As the administrator we made some changes to the ticket. A ticket claiming customers are having 404 error messages browsing online banking sounds like a significant business impact. So we changed the priority to emergency, the SLA to SEV-A (most responsive) and assigned the ticket to Jane since she has the most access and permissions of all the agents coordinated. We could have assigned to a different agent but for this example we chose Jane. The department was changed from 'Support to 'System Administrators' since this is more that department's wheel-house. As we make admin changes/updates, the thread below tracks and reports those changes to any and all persons assigned to the ticket for transparency. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DsZ8Eob.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once a ticket is resolved, as the assigned agent/admin you can post a response within the thread. If you have been granted the permission to do so, you may also change the status of the ticket from 'Open' to 'Closed' or 'Resolved.' For this example, the admin has the permission to resolve tickets. Select 'Resolved' at the drop-down and click the 'Post Reply' button to close out the ticket. The system will refresh and the ticket will no longer appear in the open tickets page. It will appear in the closed tickets drop-down instead. See image below. 
</p>
<br />

<p>
<img src="https://i.imgur.com/NDo0i2x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
