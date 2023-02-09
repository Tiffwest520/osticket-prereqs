<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- create Virtual Machine in Azure
- Install / Enable IIS in Windows with CGI
- Install PHP manager for IIS and PHP 
- Install rewrite module
- Install VC_redist
- Install MySQL and HeidiSql
- Install osTicket




<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/ynGk0RP.png" height="80%" width="80%" alt="PHP Steps"/>
</p>
<p>
Once all the software is installed, PHP has to be registered within IIS. From there we can go to the osTicket setup page.</p>
<br />

<p>
<img src="https://imgur.com/IVYPz1P.png" height="80%" width="80%" alt="browserSteps"/>
</p>
<p>
On IIS, enable extensions for PHP from the PHP manager that was configured.
</p>
<br />

<p>
<img src="https://imgur.com/E4KQ1AQ.png" height="80%" width="80%" alt="SQL Steps"/>
</p>
<p>
In Heidi SQL we will connect to the database that was made in MYSQL.
</p>
<br />

<p>
<img src="https://imgur.com/HvBOxWY.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
<p>
When everything is installed and configured we can go to the help desk login page.
</p>
<br />
