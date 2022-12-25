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

- Setup Resource group/virtual Machine in Azure
- Install OsTicket requirements
- Install osTicket itself
- Perform after-installation configuration of osTicket
- Explore osTicket as a Help Desk Professional

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/ZTvGJks.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first thing that you would need in order to set up Azure, is to have an Azure tenant created as well as have an active subscription with Azure, but in order to create what you see in this image, you would first of all have to open up your browser and key in portal.azure.com, then once in, use the search box to type in "resource group" then you will click "+create" and while you are editing you will need to key in the necessary prerequisites, such as (windows 10, username/password, and check the box) which all follow the creation for your resource group. Immediately after, you will use your same resource group to create a virtual machine inside of it, using the virtual machine tab on the mainpage or simply type "virtual machine" in the search box. You will then click "+create" and it is very important tto click "Azure virtual machine" that follows, and fill in the necessary required information, (resource group, same region, windows 10, size, username/password, check/confirm box).
</p>
<p>
<img src="https://i.imgur.com/SoFcMtu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First you would need to copy the Public IP address of your newly made virtual machine, and then open up remote desktop, using your search bar on the desktop, you would then paste your Public IP address there and be sure to remember your username/password that was previously created. Afterwards you will have to install all of the following programs to make osTicket work.
</p>
<br />

<p>
<img src="https://i.imgur.com/UCqlXHd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have sucessfully completed the following installations to make osTicket work (Install/Enable IIS in windows,Web Platform Installer, etc), this "osTicket Basic Installation" page should come up.
</p>
<br />

<p>
<img src="https://i.imgur.com/V5D16an.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congratulations! It should have been installed sucessfully with no issues. You will finally browse to your help desk login page.
</p>
<br />
