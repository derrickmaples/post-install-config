![osTicketImage](https://github.com/user-attachments/assets/501cacc0-438e-466c-a227-29f2eff08797)


<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone the ability to create a ticket
- Configure Agents
- Configure Users
- Configure SLA
- Configure Topics

<h2>Configuration Steps</h2>


<p>
Configure my role in osTicket by creating a new role. Go to Admin Panel -> Agent -> Roles. Here you can add, delete and configure roles in osTicket.  
</p>
<br />


![2-1](https://github.com/user-attachments/assets/e1310f45-c7f8-4286-aa4c-e3aec09972d1)
![2-2](https://github.com/user-attachments/assets/304815c8-fc0b-4508-88b6-6b1d770ead04)
![2-3](https://github.com/user-attachments/assets/f2a41f10-db80-4417-8561-1f33a2c63f75)
![2-4](https://github.com/user-attachments/assets/1ddbdd8f-b34f-47f4-97f2-5b91186e0806)



<p>
Add a new role named "My Permissions" and give the role unlimited access. 
</p>
<br />


![2-5](https://github.com/user-attachments/assets/ec118a03-dd53-4588-83e0-1f3aabcc6fd5)
![2-5a](https://github.com/user-attachments/assets/18cb96b4-88cc-4e6c-b19a-28e4b4eff33f)
![2-5b](https://github.com/user-attachments/assets/cb9f60fa-96ad-4d89-8b20-97d8211bef39)



<p>
Add a new department named "Admins" in the Departments tab.
</p>
<br />


![2-6a](https://github.com/user-attachments/assets/59248fdf-28f5-4c38-95c3-3a344e652c4d)
![2-6b](https://github.com/user-attachments/assets/4ee93533-645a-45ed-8193-d188dd86b730)
![2-6c](https://github.com/user-attachments/assets/9b100c2b-43fa-4d88-9d18-3e424820eba4)


<p>
Add a new team named "Accounting" in the Teams tab.
</p>
<br />


![2-7](https://github.com/user-attachments/assets/8c3c00c8-07e7-4804-908f-f6549e3bee5f)
![2-7a](https://github.com/user-attachments/assets/0043b8b4-5e50-42fa-88d5-9483b990b657)
![2-7b](https://github.com/user-attachments/assets/5f08fddf-28f6-48c0-b687-b70ef96e188b)


<p>
Allow anyone the ability to create a ticket by going to Settings -> Users by making sure the "Require registration and login to create tickets" option is not checked.
</p>
<br />


![2-8](https://github.com/user-attachments/assets/53707fd8-65df-4a0c-8a94-9aa79f98ca86)


<p>
Add some agents and assign them to departments and teams. I got the names from a randomizer.
Add Mary Charles to the Admins department with My Permissions access and the Accounting team.
</p>
<br />


![2-9](https://github.com/user-attachments/assets/f6425e79-65fe-48bb-9841-f852312a5b11)
![2-9a](https://github.com/user-attachments/assets/bad4489c-10c1-478b-8a49-b8f922976890)
![2-9b](https://github.com/user-attachments/assets/5247dedc-8dc9-406f-a948-e8a305731b22)

<p>
Add Eric Gabriel to the Support department with View Only access and no team. Now there are two more people in the Agents category.
</p>
<br />


![2-9c](https://github.com/user-attachments/assets/f53f872b-11a9-48ed-bbf9-fca43e6e5c77)
![2-9d](https://github.com/user-attachments/assets/b180031e-f12f-4827-bf1e-e719321e1f1c)
![2-9e](https://github.com/user-attachments/assets/86d2841b-15f1-464f-b012-b7fe78e6f3cc)


<p>
Add the osTicket users who will be able to create tickets by going to the Users tab in the Agent Panel.
Add Fred Peterson and Ron Davis
They now appear in the User Directory
</p>
<br />


![2-10](https://github.com/user-attachments/assets/7ea03a89-a69a-48e5-9eb6-8a4ef3bd75ed)
![2-10a](https://github.com/user-attachments/assets/b53285ed-588b-487f-8d45-22affa5713ed)
![2-10b](https://github.com/user-attachments/assets/13bfb9f9-a1a1-4619-95f5-1c1f73e793dc)
![2-10c](https://github.com/user-attachments/assets/e5427401-847a-43a9-b360-a6b77036f3da)


<p>
Create the SLA perameters for the tickets. This determines the time at which the tickets are resolved depending on the problem.
Go to SLA in the Manage tab of the Admin Panel.
</p>
<br />


![2-11](https://github.com/user-attachments/assets/37e43f27-8d27-45d3-b5d2-1f2b573f3112)


<p>
For this project, 3 SLAs are created. Level 1,2 and 3 (1 being the highest level)
</p>
<br />


![2-11a](https://github.com/user-attachments/assets/add9bb5c-b845-4d0c-acea-1a79b4617ae2)
![2-11b](https://github.com/user-attachments/assets/c379d5f4-8c19-4661-af2f-27949a1f7626)
![2-11c](https://github.com/user-attachments/assets/a27e2172-ca03-4251-8555-fd732d8eee81)

<p>
Create the topics for each level to help the user determine which level to use in Help Topics.
Create "Equipment Request" and "Other" under General Inquiry and "Business Critical", "PC Issues" and "Reset Password" under Report a Problem.
</p>
<br />


![2-12](https://github.com/user-attachments/assets/58c49e8e-8e2a-4eed-84ce-e3098615b30d)
![2-12a](https://github.com/user-attachments/assets/6dede115-ab38-4dc7-8ff4-f0c5d2c917d4)


<h2>Success!</h2>
