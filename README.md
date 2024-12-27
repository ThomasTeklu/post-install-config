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

The first step in this configuration process will be to establish roles. Roles serve a huge function in the ticketing system since they have the ability to give varying levels of permission within the system to different agents without having to specialize each agent's permissions individually.

We'll start by navigating to the admin/analyst login page that was presented on the congratulatory webpage we saw at the end of the installation phase (http://localhost/osTicket/scp/login.php). Then using our admin credentials, we will log in. Here, a crucial aspect needs to be observed. In the top right corner, there should be a small section containing the words "Admin Panel". This essentially points out the fact that, currently, though you are logged in with your admin credentials, you are viewing osTicket as an agent (there are two views/panels: Admin Panel and Agent Panel; if you are within one, the option seen in the corner will be the other). To make the changes that we want to make, we need to switch to admin mode by clicking "Admin Panel". 


![image](https://github.com/user-attachments/assets/f5f3be66-a07b-4ed7-b0ba-9d163aad09b1)

![image](https://github.com/user-attachments/assets/2e4806d4-9ef1-4d98-a940-821d3ab66bf7)



## Departments

![image](https://github.com/user-attachments/assets/7572b222-548e-49ef-b2e4-6983716eda5a)



## Teams

![image](https://github.com/user-attachments/assets/a5e49b7c-bc3d-4206-b385-1520221b9715)

![image](https://github.com/user-attachments/assets/8ee64878-8c3d-4ef9-9d58-584c3f74e967)




## Agents

![image](https://github.com/user-attachments/assets/c5a5707b-931f-4b93-b616-5a5aeb907210)

![image](https://github.com/user-attachments/assets/0bc29213-4310-4c85-969e-e8ca9d4bf9b0)




## Users 

![image](https://github.com/user-attachments/assets/07f0cf04-ac85-4785-b26d-b96fea77e08c)

![image](https://github.com/user-attachments/assets/295170d9-2f40-4355-bc9f-f3c0730b4457)




## Service Level Agreements

![image](https://github.com/user-attachments/assets/4c0e8804-f952-4d9f-9d0f-3be939470930)



## Help Topics

![image](https://github.com/user-attachments/assets/5584a89e-f710-4c90-b5e7-5aeb2b1f60bf)

![image](https://github.com/user-attachments/assets/83f31b4c-c33b-42f6-a29c-24a5020e931e)




