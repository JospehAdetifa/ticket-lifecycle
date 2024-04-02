# ticket-lifecycle
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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

STAGE 1: Create A Tickets Using The Customer Accounts We created Previously 

Click this link: http://localhost/osTicket/
You see a page that looks like this. Enter in Karen's email address and her full name. 


<img width="838" alt="Screenshot 2024-04-02 at 17 58 22" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/0cb3fe04-e5cf-470c-b196-b531918ce6cd">


Next we are going to click on the mobile banking ticket.


Then find scroll down to business critical outage in the help topic section. 

<img width="838" alt="Screenshot 2024-04-02 at 17 58 45" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/760dceb7-17a9-431a-ba7a-6f5f03d78d10">


Next fill out the issue summary e.g. Entire Mobile Online Banking Is down

<img width="840" alt="Screenshot 2024-04-02 at 18 03 40" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/f9bb841b-c312-4d5a-ad63-b754a78ca844">


Then fill out the issue summary e.g. Customers are reporting they are getting a 404 error when browsing to online banking.

<img width="840" alt="Screenshot 2024-04-02 at 18 03 40" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/52312749-876f-4743-9f07-09e90eb0eafe">


Once this is done click create ticket.


<img width="838" alt="Screenshot 2024-04-02 at 18 04 17" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/d992097a-ee09-461a-a5c6-ff2c0f8910c5">


STEP 2: Respond To Tickets As An Agent 

Login as Jane Doe

If you login as Jan Doe and you don't see any tickets. Log back in as your intial admin account and ensure that Jane is given access to the support department.

You should see a page like this with the 3 tickets that you generated earlier. 

<img width="959" alt="Screenshot 2024-04-02 at 18 44 29" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/2e0a3a89-0533-420e-b795-2b9091d79736">


STEP 3: Assign the ticks & Check the SLA level

Click on the mobile banking ticket and analyse the situation. 


<img width="956" alt="Screenshot 2024-04-02 at 18 48 03" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/810e264e-a523-4e55-ad5c-da96c8e2b709">


I notice that the priority level is set to normal and I want to correct this. This seems like a big business impacting issue so I will set the priority to emergency and make a comment that this is a business impacting event. 


<img width="647" alt="Screenshot 2024-04-02 at 18 50 09" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/2465025c-5482-4509-95c8-97a7774f6556">



<img width="647" alt="Screenshot 2024-04-02 at 18 51 19" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/0b821e26-91d3-4c76-a23b-7efe70672fa1">



Next we act like we are the escalation engineer by assigning this issue to a specific person. Click unassigned in the assigned to section 


<img width="438" alt="Screenshot 2024-04-02 at 18 54 24" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/7cd8e7a8-20b4-42d1-ad5e-55bab9d532ba">


Since Jane was is a high level employee let's assign this task to her by finding her name in the scroll down menu. Then Click update to complete this prcocess.


<img width="646" alt="Screenshot 2024-04-02 at 18 56 22" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/cc6ec50d-b9ef-4dd1-978c-accad836b642">


Next we can adjust the SLA.

Since this is a business impacting event I want to make it a "Sev-A" case. 


<img width="646" alt="Screenshot 2024-04-02 at 20 32 35" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/b6e9ae52-bf63-4a78-83e2-263938d0d433">


Next we can set the department to system administrators. 


<img width="646" alt="Screenshot 2024-04-02 at 20 36 33" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/3824e813-4f74-47da-9eea-439240e49c6b">


We can then leave a comment then click transfer.



<img width="647" alt="Screenshot 2024-04-02 at 20 37 34" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/02eda3b7-09d2-488d-aa42-5b1fce86c591">



After that we can leave an updated comment in the response section. To complete this section click post reply. 



<img width="931" alt="Screenshot 2024-04-02 at 20 41 42" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/09554e5c-5b47-4cc1-9bc1-3558cbe2e619">



Click the tickets tab to observe the changes. 


STEP 5: Resolve the ticket. 

CLick back on the mobile banking ticket and scroll down to the bottom. At this point we want to pretend like we fixed the problem so we will write a comment in the response section. 


<img width="922" alt="Screenshot 2024-04-02 at 20 48 31" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/9d76ebd6-eb4a-42c1-9374-4713e011c482">


Now go to the ticket status drop down menu and click resolved. 


<img width="922" alt="Screenshot 2024-04-02 at 20 49 33" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/d6af6934-076d-424b-bb28-40d917a07db4">


Once that is done click post reply. Once you go back to the ticket tab you should see that the mobile banking has dissapeared. 


<img width="955" alt="Screenshot 2024-04-02 at 20 51 59" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/a7707622-b392-42a1-8b63-658521a7ed10">


That's because the ticket has been resolved. You can find it by clicking on the closed tab. 


<img width="957" alt="Screenshot 2024-04-02 at 20 52 36" src="https://github.com/JospehAdetifa/ticket-lifecycle/assets/165278529/20046d3f-d00d-4646-908e-bef3cc894e08">


Repeat this process for the 2 other tickets!

