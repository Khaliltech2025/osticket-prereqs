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

- Windows 11</b>

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- Remote Desktop
- osTicket Installation Files
- PHP Directory 
- Heidi SQL
<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/aGkIySQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Hello, and welcome to my first IT tutorial! First off, we will begin by creating a virtual machine (vm) on the Microsoft Azure platform. A virtual machine is essentially a remote computer; the significance of the VM is that it will allow us to keep out PC protected from malware, bugs, and potential malfunctions while conducting the lab. The first step for this process is to create a resource group and title it "osTicket". Next you will set up your virtual machine with 2-4 VCPUs.
</p>
<br />

<p>
<img src="https://i.imgur.com/EbaLAAx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next you will log into your VM with the Remote Desktop Connection. In order for you to log in, you must go to the VM settings, copy the public IP address and paste it into the computer field. Once you paste the IP address, you must use the username and password that you used to create your VM. Once you input your username and password you will receive a pop up message, make sure you click "Yes" and you will boot up into the VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/EFRK3gC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you manage to login to your VM, You will need to enable Internet Information Services (IIS). Once you gain access to the control panel, select "uninstall a program" then you should see "turn windows features on or off" once the list is visible, make sure that you enable IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/eifCVjZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you manage to enable IIS, You will need to create a directory for C:\PHP, Once you make the necessary program installations you will need to configure your username and password credentials. You will need to go to the osTicket Installation Files folder, unzip the files into the PHP folder. next you will install VC_redist.x86.exe, and MySQL 5.5.62
</p>
<br />

<p>
<img src="https://i.imgur.com/fymjIv9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will open IIS as an admin. You will need to register PHP from within IIS (PHP Manager -> C:\PHP\php-cgi.exe), reload IIS (Open IIS, Stop and Start the server), install osTicket, Reload IIS (Open IIS, Stop and Start the server).


</p>
<br />

<p>
<img src="https://i.imgur.com/t8tx77S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will do the final steps in order for osTicket to work properly in our browser. FIrst, rename: ost-config.php, assign Permissions: ost-config.php, continue setting up osTicket in the browser (click Continue), from the “osTicket-Installation-Files” folder, install HeidiSQL., continue setting up osTicket in the browser, lastly... Congratulations, hopefully it is installed with no errors!


</p>
<br />
