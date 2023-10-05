<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Part 1 (Create Virtual Machine in Azure)
Create a Resource Group
Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs
When creating the VM, allow it to create a new Virtual Network (Vnet)
- Part 2 (Installation of prerequisite softwares)
Create an Azure Virtual Machine Windows 10, 4 vCPUs
Name: VM-osTicket
Username: labuser (**Note:This is just an example, normally don't write down credentials for security reasons)
Password: osTicketPassword1! (**Note:This is just an example, normally don't write down credentials for security reasons)
Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
[X] IIS Management Console
<img src="https://i.imgur.com/lviaMr5.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
- Part 3
- From the Installation Files, download and install HeidiSQL.
Open Heidi SQL
Create a new session, root/Password1
Connect to the session
Create a database called “osTicket”
- Continue Setting up osticket in the browser
MySQL Database: osTicket
MySQL Username: root
MySQL Password: Password1
Click “Install Now!”


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/qvU2t1m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Internet Information Services (IIS) Manager
</p>
<br />

<p>
<img src="https://i.imgur.com/AbcBEeT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Heidi SQL Instllation
</p>
<br />

<p>
<img src="https://i.imgur.com/8aIj3On.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket Isntllation
</p>
<br />

