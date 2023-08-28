<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

![Screen Shot 2023-08-28 at 3 21 19 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/22f2d128-ab0b-4d43-9a13-5b061a2c87b9)
![Screen Shot 2023-08-28 at 3 25 06 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/c9add2a5-48c8-4929-afff-9fc79fdf34c8)

Here, you want to set up the roles. For example "Supreme Admin" would be created with full access compared to a role that's created with limited access or View Only.
</p>
<br />

![Screen Shot 2023-08-28 at 3 29 50 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/363f5c10-54a1-4524-9a85-d7d61e0e8487)
<p>
Next, you need to create departments that you can add your agents to later on. Ex: regular support, Admins, etc.
</p>
<br />

![Screen Shot 2023-08-28 at 3 32 14 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/bfcf85b3-90e5-49c9-b423-bff6539af44e)
<p>
 Here, you'll want to create your teams like an all-star team of your favorite top-performing agents.
</p>
<br />

![Screen Shot 2023-08-28 at 3 33 54 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/5bc5bdb4-d988-46ac-bade-a0f3db434711)

Next up, you need to start creating agents. Save their login information and assign access and permissions.

![Screen Shot 2023-08-28 at 3 40 24 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/cf84f94d-5d90-4ec4-9e16-a4a4c1e7e2a3)

Now create your users. You can think of them as employees of a company. They are the ones putting in the tickets. Its up to you as a systme admin and the queue manager to go over every ticket and code them correctly then assign them to the agents for them to be worked on according to the comapines SLA.

![Screen Shot 2023-08-28 at 3 43 37 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/715d6238-299e-45c4-9634-12facf36e337)

This is where you will create your Service Level Agreements. How severe is the ticket? Severity A or Severity C? Within 1 hour of a ticket being entered in the systemt or is it within 8 working business hours?

![Screen Shot 2023-08-28 at 3 45 24 PM](https://github.com/malikharris4587/post-install-config/assets/143438495/8b46840c-d9dd-4d0d-8c33-818e11c28214)

Finally create some help topics. When an employee puts in a ticket they will have these options populate that will be assigned to certain departments and give an overall understanding of the appropriate SLA. 
