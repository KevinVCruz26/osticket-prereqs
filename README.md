<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows
- Install / PHP Manager for IIS
- Install / Rewrite Module 
- download PHP 7.3.8
- Install VC_redist.x86.exe
- Install MySQL 5.5.62
- Install HeidiSQL

<h2>List Prerequisites Downloads</h2>

[Installation Files](https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Install / Enable IIS in Windows WITH
CGI and Common HTTP Features</h2>
  World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features

<h2>AND IIS Management Console</h2>
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console

</p>
<br />

<h2>From the Installation Files, download and install PHP Manager for IIS </h2>

[PHPManagerForIIS_V1.5.0.msi](https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=drive_link)

<h2>From the Installation Files, download and install the Rewrite Module</h2>

[rewrite_amd64_en-US.msi](https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=drive_link)

<h2>Create the directory C:\PHP</h2>

<h2>From the Installation Files, download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP</h2>

[php-7.3.8-nts-Win32-VC15-x86.zip](https://drive.google.com/drive/folders/1yOk5ejp5Oe21USJfCgelyvdlJMwHRhxC?usp=drive_link)

<h2>From the Installation Files, download and install VC_redist.x86.exe</h2>

[VC_redist.x86.exe](https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=share_link)

<h2>Open IIS as an Admin</h2>

<h2>Register PHP from within IIS</h2>

<h2>Reload IIS (Open IIS, Stop and Start the server)</h2>

<h2>Install osTicket v1.15.8</h2>
Download osTicket from the Installation Files Folder
Extract and copy “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”
<h2>Reload IIS (Open IIS, Stop and Start the server)</h2>

<h2>Go to sites -> Default -> osTicket</h2>
On the right, click “Browse *:80”



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
