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

<b>Step 1: In this tutorial, you are going to get a bit of practice, creating tickets from the end user's perspective and work through them as an agent to resolution. This is what the home screen for the End User should look like:</b>

<p>
<img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
</p>
<br />

<b>Step 2: For the first ticket, you will enter Karen's information (one of the users you created in the post-installation tutorial). Just enter Karen's email and name for the purposes of this tutorial. Select ***Business Critical Outage*** from Help Topic drop down menu.</b> 

**_!!NOTE!! - The bottom half of the form will drop down to allow you to fill in more details of the ticket request._**

<p>
<img src="https://i.imgur.com/WkZGxrr.png" title="source: imgur.com" /></a>
</p>
<br />

- Imagine Karen is the manager of the online banking platform. She is reporting that the entire online banking system is down; and customers don't have access. To do this: Create Issue Summary --> Expand on issue in box below -->Click Create Ticket. 

<p>
<img src="https://i.imgur.com/mZwKnjt.png" title="source: imgur.com" /></a>
</p>
<br />

- Your screen will look like this if your ticket is created successfully:

<p>
<img src="https://i.imgur.com/o7Z5fwk.png" title="source: imgur.com" /></a>
</p>
<br />

<b>Step 3: Create another ticket. Return to the Ticket System home page:</b> 

<p>
<img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
</p>
<br />

- Chad ***(the other user you created)*** is the head of an Accounting Department and is having software issues. So Chad logs in and creates a ticket in Personal Computer Issues. Fill in email and name --> Select Help Topic. 

<p>
<img src="https://i.imgur.com/JcgPWHA.png" title="source: imgur.com" /></a>
</p>
<br />

- He reports that the Accounting Department is unable to use Adobe Reader. Create Issue Summary --> Expand on issue in box below --> Click Create Ticekt.

<p>
<img src="https://i.imgur.com/yjO2BeX.png" title="source: imgur.com" /></a>
</p>
<br />

- Chad's ticket submits successfully. Head back to user home acreen.

<p>
<img src="https://i.imgur.com/sqxK3bM.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
</p>
<br />

<b>Step 4: Karen created one more ticket. She needs some general information. Fill in her details, then select General Inquiry.

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

- This is Jane's homescreen. Notice how all of the tickets that were generated are visible. Also all priority levels remain at normal. You are required to assign Priority, SLA Plans, and tickets to agents at this time. This is important to begin to queue the tickets so that they may begin to be worked on accourding to SLA requirements.

<p>
<img src="https://i.imgur.com/xMuJUMQ.png" title="source: imgur.com" /></a>
</p>
<br />

- This is how the ticket screen appears in the system. Notice you have the ticket creator's information, the date and time created. Notice also how the ticket is unassigned, normal priority, and unassigned to an agent. 

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


Step 6: SInce Jane assigned the ticket to herself, she can go ahead and begin working the ticket. Underneath the ticket thread Jane posts a reply stating that she is coordinating with a team to get a resolution. Leave the ticket open and post reply.

<p>
<img src="https://i.imgur.com/9uvPupC.png" title="source: imgur.com" /></a> 
</p>
<br />

- Back at Jane's home screen you can see where the ticket's priorty status has changed and is assigned to an agent:

<p>
<img src="https://i.imgur.com/r2rWmsQ.png" title="source: imgur.com" /></a>
</p>
<br />

Step 7: 
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

Step 8: You should look at the next ticket. That would be he second ticket on our list that is submitted by Chad regarding Adobe Reader problems. 

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

- Next, Jane needs to configure the SLA level for this ticket. It's not quite an emergency, but it is a high priority due to it potentially interrupting the productivity of the Accounting Department. Choose Sev-B from menu --> Click update. 

<p>
<img src="https://i.imgur.com/AdyYomr.png" title="source: imgur.com" /></a>  
</p>
<br />

- Finally, assign the ticket to a HelpDesk agent. Click Marshall Arnold --> Click Assign.

<p>
<img src="https://i.imgur.com/VTK9HfV.png" title="source: imgur.com" /></a>
</p>
<br />

- You can now see below the changes and assignments that have been applied to the Personal Computer Issues ticket.

<p>
<img src="https://i.imgur.com/qNIUPeg.png" title="source: imgur.com" /></a>  
</p>
<br />

- Jane proceeds to post a reply documenting her changes and assignment of the ticket. Create response ***per your institution's guidelines*** --> Choose Ticket status as open --> Click Post Reply.  You should also document that you reached out to the assigned agent with a warm hand ***(meaning that you spoke with the agent directly about the ticket and assignment)***. The ticket thread documents that a warm handoff with Marshall occurs, as well. 

<p>
<img src="https://i.imgur.com/fCFKexw.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/qNIUPeg.png" title="source: imgur.com" /></a>
</p>
<br />

- The ticket queue now shows that the Priority Level is High and has been assigned to an agent.

<p>
<img src="https://i.imgur.com/4XpSrmB.png" title="source: imgur.com" /></a>
</p>
<br />

  ***Note - To clean up your queue, feel free to delete the osTicket installed Ticket at any time you feel comfortable. Click on the Ticket --> Click the Trash Can Icon --> Delete.***

Step 9: Now for the final ticket, the General Inquiry. It was assigned to Jane, so you need to log back in as Jane on the Helpdesk Agent login.

<p>
<img src="https://i.imgur.com/jsqE9Fc.png" title="source: imgur.com" /></a>
</p>
<br />

- Once at the ticket screen, you can see that options are listed as default. Like the two previous tickets in the tutorial, you will first need to evaluate priority status and assignment. 

<p>
<img src="https://i.imgur.com/4uxexWN.png" title="source: imgur.com" /></a>
</p>
<br />

- Next you can change the SLA to Sev-C, and assign the ticket to an agent. The priority level is fine for the issue reported. Change the SLA --> Sev-C --> Update. Since Jane already knows this information, you can assign this to her by Clicking Assigned to --> Choose Jane Doe --> Click Assign.

<p>
<<img src="https://i.imgur.com/UYsz8TY.png" title="source: imgur.com" /></a>
</p>
<br />

- Then, Jane provides a resolution, and contact information for further communication and closes out the Ticket. Creaet Response --> Choose Closed from Status Menu --> Click Post Reply.

<p>
<img src="https://i.imgur.com/0CD5Q3O.png" title="source: imgur.com" /></a>
</p>
<br />

- Jane's reply posts successfully and has no tickets remaining at the time. 
<p>
<img src="https://i.imgur.com/fJfRUM2.png" title="source: imgur.com" /></a>
</p>
<br />

<p>
<img src="https://i.imgur.com/hmwblLC.png" title="source: imgur.com" /></a>
</p>
<br />

Step 10: In order to finish working the ticket, You need to login as Marshall at the Helpdesk Agent login.

<p>
<img src="https://i.imgur.com/sntSGfy.png" title="source: imgur.com" /></a>
</p>
<br />

- Marshall's home screen now shows he has a ticket he needs to resolve.

<p>
<img src="https://i.imgur.com/wYI9GYi.png" title="source: imgur.com" /></a>
</p>
<br />

- Marshall posts a reply of actions taken to temporarily get Accounting working again and plans to research for a solution. In order to do this; you create a response --> choose open TIcket Status --> Click post reply.

<p>
<img src="https://i.imgur.com/GNyMd8A.png" title="source: imgur.com" /></a>
</p>
<br />

- Marshall's reply has posted in the Ticket Thread. You can pretend some time has passed while research is occuring. A solution has been found. Marshall submits a reply and closes the ticket. To do this, Create a response --> Select Closed in Ticket Status menu --> Click Post Reply

<p>
<img src="https://i.imgur.com/4I4obIg.png" title="source: imgur.com" /></a>
</p>
<br />

- Back at his honme screen, you can see that Marshall has closed his ticket assignment.
<p>
<img src="https://i.imgur.com/ZJxtxoI.png" title="source: imgur.com" /></a>
</p>
<br />

Step 11: And finally, just to be sure, log back into Jane's account to be SURE that you have no tickets remaining. Her homescreen should look like this:

<p>
<img src="https://i.imgur.com/hmwblLC.png" title="source: imgur.com" /></a>
</p>
<br />


Congrats! Now you have completed this tutorial and have seen how the ticketing system works for both End users and 


<br />

  
  
