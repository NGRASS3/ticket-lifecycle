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

For this tutorial we will walk through the stages of a ticket from Intake to Resolution. 

To begin we will see an end-user, Karen in this example, submits a ticket with the topic - Business Critical Outage. She summarizes the issue as the "Entire mobile online banking system is down". 

![image](https://user-images.githubusercontent.com/111653930/235738146-eeb57cfc-79a9-432c-83f7-ae9895463c75.png)


Next we login as an Agent and see a list of the current active tickets. Typically Queue managers will assign priority tickets to the appropriate agents as well as assigning proper SLAs.

![image](https://user-images.githubusercontent.com/111653930/235742803-093ecfbb-8cef-48b1-a6f8-30f6e02e366f.png)


Inside the ticket we can see that the priority has been set to Emergency since its a business impacting event. We also see that the ticket has been assigned to the appropriate Agent, and that the Agent has left a note detailing that he/she is working with System Administrators to get mobile banking back online.

![image](https://user-images.githubusercontent.com/111653930/235744604-0d16cebc-e434-4179-a86b-32e7c278265f.png)

<br/>
Once the problem has been fixed we can update the ticket with a message detailing the solution and set the status to "resolved".

![image](https://user-images.githubusercontent.com/111653930/235746283-ae527f7c-30ee-4267-b957-0a288f7c5921.png)

After resolving the ticket we can see it no longer appears in the "Open" tab but can still be found under the "Closed" tab.

![image](https://user-images.githubusercontent.com/111653930/235746600-4daad270-d44a-455a-89a3-d9d540949b1c.png)
![image](https://user-images.githubusercontent.com/111653930/235746634-659ee4c3-78a3-4125-9ed4-97c03e068640.png)







