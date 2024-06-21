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

<h3>Step 1: In the browser of your preference head over to the osTicket End User home page to begin.</h3>

-  [osTicket End User Home Screen](http://localhost/osTicket) --> This what the home screen for the End User should look like:

    <p>
    <img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 2: Enter your user's information</h3>

-  Use Karen: created in the [Post-installation tutorial](https://github.com/j3ssrnold/post-install-config).
    -  Enter Karen's email and name --> Select ***Business Critical Outage*** from Help Topic drop down menu. 

    <p>
    <img src="https://i.imgur.com/WkZGxrr.png" title="source: imgur.com" /></a>
    </p>

>[!TIP]
>The bottom half of the form will drop down to allow you to fill in more details of the ticket request after you select the help topic.

-  Karen is the manager of the online banking platform. She is reporting that the entire online banking system is down; and customers don't have access.
    -  Create Issue Summary --> Expand on issue in box below --> Click Create Ticket. 

    <p>
    <img src="https://i.imgur.com/mZwKnjt.png" title="source: imgur.com" /></a>
    </p>

-  Karen's ticket submits successfully; and the screen looks like this:

    <p>
    <img src="https://i.imgur.com/o7Z5fwk.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 3: Create another ticket.</h3> 

-  Return to the [Ticket home page](http://localhost/osTicket):

    <p>
    <img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 4: Enter the next user's information</h3> 

-  Use Chad created in the [previous tutorial](https://github.com/j3ssrnold/post-install-config)
    -  Fill in Chad's email and name --> Select ***Personal Computer Issues*** Help Topic. 

    <p>
    <img src="https://i.imgur.com/JcgPWHA.png" title="source: imgur.com" /></a>
    </p>

-  Chad is the head of the Accounting Department and reports that the entire Department is unable to use Adobe Reader.
    -  Create Issue Summary --> Expand on issue in box below --> Click Create Ticket.

    <p>
    <img src="https://i.imgur.com/yjO2BeX.png" title="source: imgur.com" /></a>
    </p>

-  Chad's ticket submits successfully. Head back to user home acreen.

    <p>
    <img src="https://i.imgur.com/sqxK3bM.png" title="source: imgur.com" /></a>
    <img src="https://i.imgur.com/IUG7z4H.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 4: Karen creates one more ticket regarding general information.</h3> 

-  Fill in Karen's details, then select General Inquiry.

    <p>
    <img src="https://i.imgur.com/WkZGxrr.png" title="source: imgur.com" /></a>
    </p>

-  Karen wants to know when the next hardware refresh will be due to the fact that her entire staff are having ***(unspecified)*** issues with their tablets.
    -  Create Issue Summary --> Expand on issue in box below --> Click Create Ticket.

    <p>
    <img src="https://i.imgur.com/1hSwZ8D.png" title="source: imgur.com" /></a>
    </p>

-  Karen's ticket submits successfully.
  
    <p>
    <img src="https://i.imgur.com/xvLDsiS.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 5: Now you can explore how to work a ticket as an IT Professional.</h3> 

-  Go to [HelpDesk](http://localhost/osTicket/scp/login.php) --> Log in as Jane, your Supreme Admin created from the [previous tutorial](https://github.com/j3ssrnold/post-install-config).

    <p>
    <img src="https://i.imgur.com/jsqE9Fc.png" title="source: imgur.com" /></a>
    </p>

-  This is Jane's homescreen. Notice how all of the tickets that were generated are visible and all priority levels remain at normal. 

    <p>
    <img src="https://i.imgur.com/xMuJUMQ.png" title="source: imgur.com" /></a>
    </p>

>[!NOTE]
>Jane is required to assign Priority, SLA Plans, and tickets to agents at this time. This is important to begin to queue the tickets so that they may begin to be worked on according to SLA requirements and maintain proper workflow.
<br />

<h3>Step 6: This is how the ticket screen appears in the system pre-queue. Notice how the ticket is unassigned, has normal priority, and is unassigned to an agent.</h3>
      
-  Be sure you can locate the ticket creator's information, the date and time created. 

    <p>
    <img src="https://i.imgur.com/Cdysj5f.png" title="source: imgur.com" /></a>
    </p>

-  First, you need to establish priority.
    -  For a Business Critical Outage --> Choose Emergency --> Business Impacting Event --> Update. This is how your window will appear: 

    <p>
    <img src="https://i.imgur.com/PGcw5J9.png" title="source: imgur.com" /></a>
    </p>

>[!IMPORTANT]
>You should always assign priority according to your institution's SLA requirements and the potential for impact to the business or client.
<br />

-  Second, assign the SLA level. Due to this being an emergency and business impacting event, assign SLA Sev-A from your drop down menu.
    -  Click SLA Plan --> Select SEV-A --> Rationale: Business Critical Event: Potential Financial Impact --> Click Update.

    <p>
    <img src="https://i.imgur.com/SjktjWx.png" title="source: imgur.com" /></a>
    </p>

-  Third, assign the Ticket to an agent. Due to the Emergency Priority Level and other SLA paramenters for this client, choose Jane, your System Admin.
    -  Click Assigned to --> Choose Jane Doe --> Click Assign.

    <p>
    <img src="https://i.imgur.com/2yUT3rC.png" title="source: imgur.com" /></a>
    </p>

-  Finally, transfer the Ticket to the proper department. Example: Online banking infrastructure is the responsibility of System Admins.
    -  Click Department --> Choose System Administrator--> Transfer.

    <p>
    <img src="https://i.imgur.com/woAuMrb.png" title="source: imgur.com" /></a>
    </p>

-  Additionally, the ticket thread (located below Karen’s ticket details) indicates support level changes and assignment updates.
    -  It looks something like this:

    <p>
    <img src="https://i.imgur.com/omxjPzs.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 7: You can begin working Jane's first ticket.</h3> 

-  Post reply under ticket thread --> Leave ticket open --> Click Post Reply. 

    <p>
    <img src="https://i.imgur.com/9uvPupC.png" title="source: imgur.com" /></a> 
    </p>

-  Back at Jane's home screen you can see where the ticket's priorty status has changed and is assigned to an agent:

    <p>
    <img src="https://i.imgur.com/r2rWmsQ.png" title="source: imgur.com" /></a>
    </p>

<h3>Step 8: Jane has been collaborating with her team to reach a resolution. A colleague in System Engineering finds and solves the problem.</h3>

-  Since the issue is repaired: Post a reply in the system --> Selecting Resolved from Ticket Status --> Click Post Reply.

    <p>
    <img src="https://i.imgur.com/STIwVo0.png" title="source: imgur.com" /></a>
    </p>

-  Back in Jane's home screen you can see the ticket is no longer in the queue.
   -  To confirm ticket is closed: Click Ticket --> Closed --> Today.

    <p>
    <img src="https://i.imgur.com/FoxKJSA.png" title="source: imgur.com" /></a>
    <img src="https://i.imgur.com/uUU8Ead.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 9: Take a look at the next ticket that Chad submitted regarding Adobe Reader issues.</h3>

-  Back at Jane's home screen click on the "Accounting Department" Ticket to pull up the details.

    <p>
    <img src="https://i.imgur.com/FoxKJSA.png" title="source: imgur.com" /></a>
    </p>

-  Below is the Ticket Details Screen for the ***Personal Computer Issues*** submission. Again no priority levels or agents are assigned.

    <p>
    <img src="https://i.imgur.com/zAQGrfW.png" title="source: imgur.com" /></a>
    </p>

-  Logged in as Jane, you will determine the proper settings for the Ticket submitted by Chad.

-  First, You will need to establish priority. Assign this priority level as High, since the whole Accounting Department is unable to use the software.
    -  Choose High from the drop down menu --> Enter your rationale for changing --> Click Update.

    <p>
    <img src="https://i.imgur.com/8bWtj71.png" title="source: imgur.com" /></a>
    </p>

-  Second, Configure the SLA level for this ticket. Choose high priority due to it potentially interrupting the productivity of the Accounting Department.
    -  Click SLA Plan --> Choose Sev-B from menu --> Click update. 

    <p>
    <img src="https://i.imgur.com/AdyYomr.png" title="source: imgur.com" /></a>  
    </p>

-  Finally, assign the ticket to a HelpDesk agent.
    -  Click Assigned To --> Choose Marshall Arnold --> Click Assign.

    <p>
    <img src="https://i.imgur.com/VTK9HfV.png" title="source: imgur.com" /></a>
    </p>

-  Now you can see the changes and assignments that have been applied to the ticket below.

    <p>
    <img src="https://i.imgur.com/qNIUPeg.png" title="source: imgur.com" /></a>  
    </p>

-  Jane proceeds to post a reply documenting her changes and assignment of the ticket.
    -  Create response ***per your institution's guidelines*** --> Choose Ticket status as open --> Click Post Reply.

    <p>
    <img src="https://i.imgur.com/fCFKexw.png" title="source: imgur.com" /></a>
    </p>

-  You should also document that you reached out to the assigned agent with a warm hand ***(meaning that you spoke with the agent directly about the ticket and assignment)***.
    -  The ticket thread reflects that a warm handoff with Marshall occurs. 

    <p>
    <img src="https://i.imgur.com/qNIUPeg.png" title="source: imgur.com" /></a>
    </p>

- The ticket queue displays that the Priority Level is High and has been assigned to an agent.

    <p>
    <img src="https://i.imgur.com/4XpSrmB.png" title="source: imgur.com" /></a>
    </p>

>[!TIP]
>To clean up your queue, feel free to delete the osTicket installed Ticket at any time you feel comfortable. Click on the Ticket --> Click the Trash Can Icon --> Delete.

<h3>Step 10: The General Inquiry, the final ticket, was assigned to Jane.</h3> 

-  You need to log back in as Jane on the Helpdesk Agent login.

    <p>
    <img src="https://i.imgur.com/jsqE9Fc.png" title="source: imgur.com" /></a>
    </p>

-  Once at the ticket screen, you can see that options are listed as default. Like the two previous tickets, you will first need to evaluate priority status and assignment. 

    <p>
    <img src="https://i.imgur.com/4uxexWN.png" title="source: imgur.com" /></a>
    </p>

-  Next, configure the SLA to Sev-C, and assign the ticket to an agent. The priority level is fine for the issue reported.
    -  Change the SLA --> Sev-C --> Update.
        -  Since Jane already knows this information, you can assign this to her.
            -  Click Assigned to --> Choose Jane Doe --> Click Assign.

    <p>
    <img src="https://i.imgur.com/UYsz8TY.png" title="source: imgur.com" /></a>
    </p>

-  Then, Jane provides a resolution and contact information for further communication. She also closes out the Ticket.
    -  Create Response --> Choose Closed from Status Menu --> Click Post Reply.

    <p>
    <img src="https://i.imgur.com/0CD5Q3O.png" title="source: imgur.com" /></a>
    </p>

- Jane's reply posts successfully and has no tickets remaining at the time. 

    <p>
    <img src="https://i.imgur.com/fJfRUM2.png" title="source: imgur.com" /></a>
    <img src="https://i.imgur.com/hmwblLC.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Step 11: Complete the Ticket</h3>

-  To finish working the ticket, You need to login as Marshall at the [Helpdesk login](http://localhost/osTicket/scp/login.php).

    <p>
    <img src="https://i.imgur.com/sntSGfy.png" title="source: imgur.com" /></a>
    </p>

-  Marshall's home screen now shows he has a ticket he needs to resolve.

    <p>
    <img src="https://i.imgur.com/wYI9GYi.png" title="source: imgur.com" /></a>
    </p>
-  Marshall posts a reply of actions taken to temporarily get Accounting working again and plans to research for a solution.
    -  Create a response --> Choose Open Ticket Status --> Click Post Reply.

    <p>
    <img src="https://i.imgur.com/GNyMd8A.png" title="source: imgur.com" /></a>
    </p>

-  Marshall's reply has posted in the Ticket Thread. You can pretend some time has passed while research is occuring. A solution has been found and Marshall submits a reply and closes the ticket.
    - To do this: Create a response --> Select Closed in Ticket Status menu --> Click Post Reply

    <p>
    <img src="https://i.imgur.com/4I4obIg.png" title="source: imgur.com" /></a>
    </p>

-  Back at the honme screen, you can see that Marshall has closed this ticket assignment.

    <p>
    <img src="https://i.imgur.com/ZJxtxoI.png" title="source: imgur.com" /></a>
    </p>

<h3>Step 12: Finally, just to be sure, log back into Jane's account to be SURE that you have no tickets remaining.</h3> 

-  The homescreen should look like this:

    <p>
    <img src="https://i.imgur.com/hmwblLC.png" title="source: imgur.com" /></a>
    </p>
<br />

<h3>Congrats! You should now have some understanding of the Ticket Lifecycle from creation to resolution.</h3> 


<br />

  
  
