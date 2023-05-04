<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP 7.3.8
- PHP Manager for IIS
- The Rewrite Module
- MySQL 5.5.62
- HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/pIR4HY1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we create a Windows 10 Vitual Machine in Azure. We remotely log into it with Microsoft Remote Desktop, then Internet Information Services/IIS with CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/c6ReaOG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we install all the prerequisite files for osTicket which include PHP 7.3.8, PHP manager for IIS, and MySQL 5.5.62.
</p>
<br />

<p>
<img src="https://i.imgur.com/FNlq5ve.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ceszROw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the prerequisites are all installed, we register PHP from witin IIS. Then we enable three IIS extentions within PHP Manager: php_imap.dll, php_intl.dll, and php_opcache.dll.
</p>
<br />

<p>
<img src="https://i.imgur.com/SCziK3G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/EGZa1DC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, we install HeidiSQL and create a new database within it called osTicket. Then we finish setting up osTicket within our broswer.
</p>
<br />
