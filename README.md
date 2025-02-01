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

- Configure Roles, Departments, Teams, Agents and Users
- Configure Service-Level Agreements (SLA)
- Configure Help Topics

<h2>Configuration Steps</h2>

1.) Login with your created username and password for osTicket. Upon reaching the homescreen, click the "Admin Panel" section to the top right near your name. This will take you to a page giving you the ability to do multiple things;
  * Create new agents
  * Create new roles
  * Create new departments aswell as users

2.) Now, from this page, create an agent, in practical use, this will be the name of an employee that will assist with support tickets but for this tutorial, we will use random names. 

3.) Upon the creation of the agent, navigate to the roles section, here you will check all boxes as checked in the image below to ensure this user can access all permissions when solving tickets. 

![image](https://github.com/user-attachments/assets/935b3025-9b47-4935-924c-8bb1849c45f6)

4.) Create separate roles to differentiate the levels of assistance each agent assigned to them can provide. The amount of roles is up to you, I recommend these four for simplicity
  * Supreme Admin
  * Expanded Access
  * Limited Access
  * View Only

![image](https://github.com/user-attachments/assets/49cf8c27-de31-4fb1-92e2-7a77cc1df54f)


5.) Next, create a department for your admin and top access users by navigating to the departments tab, here you will want to set the parent to "Top Level Department" and name the department.



![image](https://github.com/user-attachments/assets/020faa57-e4f4-4884-863c-2315d17124c5)

<p></p>
6.) Repeat step 5 for the creation of two alternate departments of lower level status, in this case, I titled them "Support" and "Maintenance", as shown in the image below

![image](https://github.com/user-attachments/assets/702ac006-04a7-4102-9b07-387e365f80e7)

7.) Now you will need new agents to assign to these departments. Navigate to the create agents section again and create an agent and assign them to one of your newly created departments. In my case, I created "Christian Hill" and "John Smith" and assigned them to the support department.

![image](https://github.com/user-attachments/assets/69640d1f-d128-4530-b840-aea11d426bf3)

8.) You now will need users that will submit tickets to your agents, navigate to the users tab and create a user. In this case, I created "Karen Jones".

![image](https://github.com/user-attachments/assets/5c648113-8ca7-4a60-9cd4-7a9abc7e2948)

9.) Next, create multiple Service Level Agreements, these are used to indicate the severity of a ticket and its importance. Click the "Manage" tab, click "SLA" and select "create new". You will be greeted with a menu that will allow you to name the SLA, here I created three
  * Sev-A (Severity A, highest priority)
  * Sev-B (Severity B, moderate priority)
  * Sev-C (Severity C, lowest priority)

10.) Once done, you will see all SLAs listed on the screen, as shown in the image below

![image](https://github.com/user-attachments/assets/a379752b-ebe9-44ed-a9d1-e8063c8bb4be)

11.) There will need to be topics to associate what type of help is needed for each ticket and which deparments will deal with them. Navigate to the "Help Topics" section and create the following topics 
  * General Inquiry / Equipment Request (This will be used if there is certain equipment that is needed such as a mouse, keyboard etc.)
  * General Inquiry / Other (this will be used to designate miscellaneous requests that don't fall under the umbrella of the other topics
  * Report a Problem / Access Issue (For access problems such as file permissions)
  * Report a Problem / Bussiness Critical Outage (For problems impacting the functionality of the business ex. entire departments with no internet connection)
  * Report a Problem / Password Reset (For login issues/ password resets)
  * Report a Problem / Personal Computer Problem (This is reserved for the computers of high level employees such as CEOs, District Managers etc.)
  * When done correctly, you will see all the above topics listed alongside the stock options that come stock with osTicket as shown below

 ![image](https://github.com/user-attachments/assets/abc0dfa2-9060-4c54-bed0-ef3d9463b4ef)

Now you are completely setup and ready to operate and maintain the osTicket ticketing System.
