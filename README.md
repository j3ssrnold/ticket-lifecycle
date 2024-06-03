<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<!--
<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket] / !-->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Required Links</h2>

- <b>Helpdesk Login:</b> http://localhost/osTicket/scp/login.php
- <b>End User Login:</b>  http://localhost/osTicket/

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Step 1: You are going to create a few tickets from the end user's perspective and work through them as an agent to resolution. This is what the home screen for the End User should look like:

<p>
<img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
</p>
<br />

Step 2: Go ahead and enter in Karen's information. Email and name. Select the help topic Business Critical Outage that you established during the post-install tutorial; the bottom half of the screen will drop down to allow "Karen" to enter in details specific to her ticket request.

<p>
<img src="https://i.imgur.com/WkZGxrr.png" title="source: imgur.com" /></a>
</p>
<br />

- Say that Karen is a manager for an  online financial instiution. She reports that the entire online banking system is down; and that customers are receiving a 404 error when attempting to navigate. Click create ticket.

<p>
<img src="https://i.imgur.com/mZwKnjt.png" title="source: imgur.com" /></a>
</p>
<br />

- IF Karen's ticket submits successfully, this is how her screen should look:

<p>
<img src="https://i.imgur.com/o7Z5fwk.png" title="source: imgur.com" /></a>
</p>
<br />

Step 3: Create another ticket. So back to honmescreen here: 

<p>
<img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
</p>
<br />

- You can use Chad this time. Chad works into accounting or something similar. So Chad logs in and decides the help topic should be Personal Computer Issues. 

<p>
<img src="https://i.imgur.com/JcgPWHA.png" title="source: imgur.com" /></a>
</p>
<br />

- Chad is department lead and is reporting that the Accounting Department is unable to use Adobe Reader since last update. Click Create Ticket.

<p>
<img src="https://i.imgur.com/yjO2BeX.png" title="source: imgur.com" /></a>
</p>
<br />

- Chad submits his ticket successfully as well. Head back to user home acreen.

<p>
<img src="https://i.imgur.com/sqxK3bM.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
</p>
<br />

Step 4: Create one final ticket as Karen. She just wants some general information. Fill in her details, then select General Inquiry.

<p>
<img src="https://i.imgur.com/WkZGxrr.png" title="source: imgur.com" /></a>
</p>
<br />

- Karen wants to know when the next hardware refresh will be due to the fact that her entire staff are having issues ***(unspoecified)*** with their tablets. Click create ticket.

<p>
<img src="https://i.imgur.com/1hSwZ8D.png" title="source: imgur.com" /></a>
</p>
<br />

- Karen's ticket submits successfully.
  
<p>
<img src="https://i.imgur.com/xvLDsiS.png" title="source: imgur.com" /></a>
</p>
<br />

Step 5: Now that you have seen the end user process, it is time to learn how to work a ticket as an IT Professional. CLick on the HelpDesk link above and log in as Jane. Remember she is your Supreme Admin you created in the previous tutorial.

<p>
<img src="https://i.imgur.com/jsqE9Fc.png" title="source: imgur.com" /></a>
</p>
<br />

- This is what Jane's home screen looks like. Notice how all of the tickets that were generated are visible. Also all priority levels remain at normal. You should pick the BUsiness Critical outage as an accurate way to prioritize the tickets.

<p>
<img src="https://i.imgur.com/xMuJUMQ.png" title="source: imgur.com" /></a>
</p>
<br />

Step 6: This is how the ticket screen appears in the system. Notice you have the ticket creator's information, the date and time created. Notice also how the ticket is unassigned, normal priority, and unassigned to an agent. You are gping to begin to queue the tickets so that they may begin to be worked on. 

<p>
<img src="https://i.imgur.com/Cdysj5f.png" title="source: imgur.com" /></a>
</p>
<br />

- First, you need to establish priority, This ticket falls under Business Critical Outage. You should assign emergency due to the potential for impact to the business. You will also be prompted to enter a reason for the change. This is how the wimdow appears. After entering the reason click
update.

<p>
<img src="https://i.imgur.com/PGcw5J9.png" title="source: imgur.com" /></a>
</p>
<br />

- Next assign the SLA level. Due to this being an emergency and business impacting event, assign SLA Sev-A from your drop down menu. Do not forget to put you rationale in the box. Click Update.

<p>
<img src="https://i.imgur.com/SjktjWx.png" title="source: imgur.com" /></a>
</p>
<br />

- Then, assign the Ticket to your agent. Due to the Emergency Priority Level and other SLA paramenters for this client, assign this ticket to Jane from the drop down menu, who is a System Administrator. Click Assign.

<p>
<img src="https://i.imgur.com/2yUT3rC.png" title="source: imgur.com" /></a>
</p>
<br />

- Finally, transfer the Ticket due to the proper department. Since online banking infrastructure is the responsibility of System Admins, transfer that ticket to the proper department. Once selected click Transfer.

<P>
<img src="https://i.imgur.com/woAuMrb.png" title="source: imgur.com" /></a>
</p>
<br />

- The ticket thread falls directly below the general details of Karen's ticket. It shows what levels of support were changed and who the ticket was assigned to. It looks something like this:

<p>
<img src="https://i.imgur.com/omxjPzs.png" title="source: imgur.com" /></a>
</p>
<br />


Step 7: SInce Jane assigned the ticket to herself, she can go ahead and begin working the ticket. Underneath the ticket thread Jane posts a reply stating that she is coordinating with a team to get a resolution. Leave the ticket open and post reply.

<p>
<img src="https://i.imgur.com/9uvPupC.png" title="source: imgur.com" /></a> 
</p>
<br />

- Back at Jane's home screen you can see where the ticket's priorty status has changed and is assigned to an agent:

<p>
<img src="https://i.imgur.com/r2rWmsQ.png" title="source: imgur.com" /></a>
</p>
<br />

- Jane has been collaborating with her team to reach a resolution. A colleague in System Engineering finds and solves the problemt. Since the issure has been repaired she posts a reply in the system; Jane resolves the ticket by selectinbg Resolved from ticket status and clicks post reply.

<p>
<img src="https://i.imgur.com/STIwVo0.png" title="source: imgur.com" /></a>
</p>
<br />

- Back in Jane's home screen you can see the ticket is no longer in the queue. You can also Click Ticket --> Closed --> Today to double check that the ticket is closed.

<p>
<img src="https://i.imgur.com/FoxKJSA.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/uUU8Ead.png" title="source: imgur.com" /></a>
</p>
<br />

Step 8: Now it's tinme to work the next ticket. The second ticket opn our list that should be resolved due to priority is the ticket submitted by Chad regarding Adobe Reader problems. Keep in mind you are still logged in as Jane.

<p>
<img src="https://i.imgur.com/FoxKJSA.png" title="source: imgur.com" /></a>
</p>
<br />

- Here is the screen for the Adobe Reader ***(Personal Computer Issues)***. Again no priority levels or agents are assigned. Logged in as Jane, you will determine the proper settings for the Ticket submitted by Chad.

<p>
<img src="https://i.imgur.com/zAQGrfW.png" title="source: imgur.com" /></a>
</p>
<br />

- First Jane will need to establish priority. It would be best to assign this priority level as High, since the whole Accounting Department is unable to use the software. Choose High from the drop down menu --> Enter your rational for changing --> Click Update.

<p>
<img src="https://i.imgur.com/8bWtj71.png" title="source: imgur.com" /></a>
</p>
<br />

- Next,


<p>
<img src="https://i.imgur.com/AdyYomr.png" title="source: imgur.com" /></a>  
</p>
<br />

<p>
<img src="https://i.imgur.com/VTK9HfV.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/qNIUPeg.png" title="source: imgur.com" /></a>  
</p>
<br />

<p>
<img src="https://i.imgur.com/fCFKexw.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/qNIUPeg.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/4XpSrmB.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/sntSGfy.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/wYI9GYi.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/GNyMd8A.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/4I4obIg.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/ZJxtxoI.png" title="source: imgur.com" /></a>
</p>
<br />


















  
  
