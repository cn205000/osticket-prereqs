<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Installation</h1>
A how-to install tutorial for the open-source help desk ticketing system osTicket.<br />

<h2>List of Prerequisites</h2>

- Stable Internet Connection
- Internet Browser
- OS: Windows 10 or older
- <a href="https://drive.google.com/drive/u/2/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">Installation Files</a></h3>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
  
<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)
  
<h1>Installation Steps</h1>

<h2>Step 1: Install/Enable IIS</h2>

Hit the windows key and search for Control Panel. Click on Programs then click on Turn Windows Features on or off.
It will open a new window, enable these features below.

- [X] Internet Information Services
  - [X] Web Management Tools
     - [X] IIS Management Console
  - [X]  World Wide Web Services
    - [X]  Application Development Features ->
       - [X] CGI
       - [X] Common HTTP Features

After all of these are enabled, hit okay.

<h2>Step 2: Create PHP Directory</h2>
Hit the windows key and search for file explorer. Open it and look on the left side of the window for This PC. Click on it then open the drive that says (C:). Right click on the empty space, hover over new then click on Folder. Right click the new folder that you just made and click on rename. Rename the file to PHP.


<h2>Step 3: Download & Install Files</h2>
Scroll up to the Installation Files and open the link. Download all the files. First we are going to launch PHPManagerForIIS_V1.5.0.msi. Go through the installation by just hitting next and accepting the terms & conditions. Next we are going to launch rewrite_amd64_en-US.msi. Do the same thing you did with the first installation.


<h2>Step 4: Configure IIS</h2>



<h2>Step 5: Setup OSTicket</h2>

