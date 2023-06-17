<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />
This will require the completion of the first two guidelines here: <br/>
https://github.com/johnnylang12/osticket-prereqs, https://github.com/johnnylang12/post-install-config


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
We need to go to -> localhost/osTicket/ and click "Open a New Ticket". <br/>
Karen is the end user opening a ticket. She is reporting that mobile banking is completely down, and so from the menu she selects that this is a Business Critical Outage. In the last tutorial we created help topics like "Business Critical Outage" to help categorize tickets that are coming in. We will create two more under different topics.
<p>
<br />
<img src="https://i.ibb.co/P6pvWwn/os-Ticket34.jpg" height="80%" width="60%" alt="Karen opens a ticket"/>
<img src="https://i.ibb.co/VSmfj80/os-Ticket35.jpg" height="80%" width="60%" alt="Karen opens a ticket"/>
</p>
<p>
Now we will log in as an agent. <br/>
Agents will be able to see live tickets in the agent panel. Queue managers will assign priority tickets to the appropriate agents as well as assigning proper SLAs, or changing departments if it is needed. Agents Like Jane Doe can post replies to tickets they are working on to explain what they are doing to resolve the issue.
</p>
<br />
<img src="https://i.ibb.co/H4cpfW2/os-Ticket37.jpg" height="80%" width="60%" alt="open tickets"/>

</p>
<p>
In this example we are setting the priority level of the ticket to Emergency since this issue is critical to the functioning of the business. We have changed the SLA plan and assigned the ticket to a top level technician. In some ticketing systems customers can set their own SLA plans. Jane Doe, the assigned Agent, posted a reply on the ticket stating that she along with the system administration team are working to resolve the issue.
</p>
<br />
<img src="https://i.ibb.co/FVr49SS/os-Ticket38.jpg" height="80%" width="60%" alt="que manager"/>

To resolve the issue, we need to fill out the response and if it is resolved, on the drop down we will select "Resolved" and post reply. <br/>
The tickets will be removed from the que and placed in a different tab labeled for closed tickets. There you can see the date and time tickets were resolved and the agent that closed the ticket.
<img src="https://i.ibb.co/0ycG3zF/os-Ticket39.jpg" height="80%" width="60%" alt="que manager"/>
</p>

<img src="https://i.ibb.co/JF9nxn7/os-Ticket40.jpg" height="80%" width="80%" alt="closed tickets"/>

That concludes the full tutorial on osTicket!
