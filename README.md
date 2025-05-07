<p align="center">
<img src="https://i.imgur.com/9dYCotk.png" alt="osTicket logo"/>
</p>

<h1>osTicket -Instalation</h1>
This lab will initiate the process of creating a real-world IT helpdesk environment by installing osTicket on an Azure VM. The installation will set up the environment to manage users and helpdesk professionals, enabling the creation of support workflows, SLAs, and ticket management operations. This setup will serve as the foundation for preparing for the CompTIA A+ certification and building the practical skills needed for a future IT role.<br />


<h2>Install osTicket on an Azure VM</h2>

### Install osTicket on an Azure VM

####  Step 1: Deploy an Azure Virtual Machine
 I logged into Azure, went to Virtual Machines, and deployed a Windows Server VM using a Standard_B2s instance. I enabled public IP access and chose RDP for remote authentication. I waited for the VM to finish provisioning.

#### Step 2: Connect to the VM
Once the VM was ready, I connected to it using Remote Desktop Protocol (RDP) to access the server environment.

<p align="center">
<img src="https://i.imgur.com/sPQWrFD.png" alt="osTicket logo"/>
</p>

***

#### Step 3: Install Required Software Stack
I installed IIS, MySQL, and PHP on the server to prepare it for osTicket. I verified that both the web server and the database were running properly.
[osTicket Installation Zipfile](https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD)

<p align="center">
<img src="https://i.imgur.com/P6KaEcz.png" alt="osTicket logo"/>
</p>

***

#### Step 4: Download and Configure osTicket
     Download the latest osTicket release.

     Move the files to the web server’s root directory.

     Set correct file permissions to allow execution.

<p align="center">
<img src="https://i.imgur.com/mMY8PWg.png" alt="osTicket logo"/>
</p>

#### Step 5: Set Up the MySQL Database
I created a new MySQL database for osTicket and added a user with the correct permissions to manage it.
I launched the osTicket installer in the browser, entered the database info, and created the admin account to finish the setup.

<p align="center">
<img src="https://i.imgur.com/cSQfPCU.png" alt="osTicket logo"/>
</p>

***

#### Essential Terms for Installing osTicket on an Azure VM
    Azure VM – A virtual computer hosted on Microsoft Azure.

    Windows Server VM – A virtual machine running Windows Server.

    Public IP Access – Allows remote connections to the VM over the internet.

    RDP (Remote Desktop Protocol) – A method to remotely access and control the VM.

    IIS (Internet Information Services) – A web server needed to run osTicket.

    MySQL – A database system that stores osTicket data.

    PHP – A programming language required to run osTicket.

    Root Directory – The main folder where osTicket files are stored.

    Database Credentials – The username and password used to access the MySQL database.

    osTicket Installer – A setup tool that helps configure osTicket on the server.

#### Technology & Software

    Microsoft Azure (Virtual Machines/Compute)
  
    Remote Desktop
  
    Internet Information Services (IIS)
