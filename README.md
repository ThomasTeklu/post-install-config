<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computing)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

In the previous repository, how to set up a Windows web server to function as an osTicket system was covered. In this repository, we'll move on to specifying certain perameters within the newly established ticketing system.

## Preperation 
Before anything else, we will need to remote connect to our virtual machine using its public IP address. After connecting, we should load two particular webpages: http://localhost/osTicket/scp/login.php and http://localhost/osTicket. If you remember, at the end of completing the prerequisites, we were left with a sort of congratulatory webpage from osTicket. At the bottom of this page, there were four linked webpages, the two of which are the ones just listed in the prior sentence. Both are extrememly relevant as the former is the login page for agents and admin of the ticketing system, while the latter is the page wherein users can generate their tickets and check their status. Having all that said, let's move on to actually configuring some aspects of the osTicket system that we now have.

## Roles

![image](https://github.com/user-attachments/assets/64f4410f-5e67-41f7-9f20-14b9571e8f71)


## Departments

![image](https://github.com/user-attachments/assets/8bb835c2-deb9-4dbd-a73a-25057ed6e665)


## Teams

![image](https://github.com/user-attachments/assets/ee7c9058-a16f-4d13-8ce2-ff125166243f)


## Agents

![image](https://github.com/user-attachments/assets/a5a0d130-ed4c-4b73-a404-c4abb9557bfe)


## Users 

![image](https://github.com/user-attachments/assets/cd53fc59-410d-4566-b389-b9c0532f34d4)


## Service Level Agreements

![image](https://github.com/user-attachments/assets/e40087cc-bc95-4faa-a9f3-4168d4a1506b)


## Help Topics

![image](https://github.com/user-attachments/assets/f68ed8a7-32d7-4a2b-801a-8ba34b07a8ac)


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
