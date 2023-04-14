<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post Installation Configuration</h2>

- Create SLA
- Assign Roles
- Create Departments
- Create Teams

<h2>Post Installation</h2>

<p>
<img src="https://i.imgur.com/nOWCqjM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/4uKxi72.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We're going to create a brand new tech company from scratch! Let's start with our SLA. SLA is a expectation set that the ticket will be handled in a certain time frame. Create SLA while logged into osTicket select admin, managage panel, then SLA. Now, select add new SLA and let's begin creating some SLAs. Above we've created the following SLA agreements. SLA-A which is an agreement that the ticket will be responded/handled within 8 years. SLA-B will be handled on a 24/7 bases. SLA-C will be handled in a 24/5 fashion.
</p>
<br />

<p>
<img src="https://i.imgur.com/Jh5cOM6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that our SLA is created let's create some roles within the company. You can create a role by going to the agent tab, selecting roles then create role. This role in particular that we've created we're going to label the "supreme role". We've giving this role the ability to do everything related to the ticketing system. They can assign tickets, delete them etc as they feel as needed. You can set your role to do as you feel is needed inside the role portal.
</p>
<br />
<p>
<img src="https://i.imgur.com/trlUzuS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
SLA, and roles are created now let's create new departments in the company. Today we're going to create the "supreme department". Departments are created by going to the agent tab again, selecting department and then hitting add new department. The department we created today will be over all other departments that will be created later on. We've gave the supreme department the pleasure of being on SLA-B which means they're supposed to respond to any ticket 24/7. 
<p>
<img src="https://i.imgur.com/ORuEnyq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Teams are created by going to the admin tab-> teams-> create new team. Teams will be when you break the staff into different groups. Can have your help desk team, and so on. We decided to create the "supreme team". Feel free to add and create any team as you wish.
<p>
<img src="https://i.imgur.com/zA9McNR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Everything is created and we've hired our first employee "John Doe". John Doe needs the ability to join the teams, departments, and be assigned a role. Today we're going to create John a profile to use within the company. Admin tab -> agents -> create new admin. Now that John profile is created we're going to assign a e-mail, password that he has to reset upon signing in. John will be giving the "supreme role" and placed in the "supreme department" and the "supreme team". He's all set with his fresh profile and has all the tools he needs inside osTicket to perform.



 <h2>You've created your tech company from start to finish using osTicket. Congrats!</h2>
