<p align="center">
<img src="https://i.imgur.com/9dYCotk.png" alt="osTicket logo"/>
</p>

<h1>osTicket -Instalation</h1>
This lab will initiate the process of creating a real-world IT helpdesk environment by installing osTicket on an Azure VM. The installation will set up the environment to manage users and helpdesk professionals, enabling the creation of support workflows, SLAs, and ticket management operations. This setup will serve as the foundation for preparing for the CompTIA A+ certification and building the practical skills needed for a future IT role.<br />


<h2>Install osTicket on an Azure VM</h2>

- ### Steps to Install osTicket on an Azure VM
- ####  Step 1: Deploy an Azure Virtual Machine
    Open Azure and navigate to Virtual Machines. 

    Create Windows Server VM.

    Select a Standard_B2s instance or better.

    Enable public IP access for remote connection.

    Choose RDP (Windows) for authentication.

    Deploy the VM and wait for provisioning to complete.

- #### Step 2: Connect to the VM
 
  Use Remote Desktop (RDP) to log in.

<p align="center">
<img src="https://i.imgur.com/sPQWrFD.png" alt="osTicket logo"/>
</p>

- #### Step 3: Install Required Software Stack

[osTicket Installation Zipfile](https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD)

 Install IIS, MySQL, and PHP.

<p align="center">
<img src="https://i.imgur.com/P6KaEcz.png" alt="osTicket logo"/>
</p>

    Verify that the web server and database are functioning correctly.

- #### Step 4: Download and Configure osTicket
     Download the latest osTicket release.

     Move the files to the web server’s root directory.

     Set correct file permissions to allow execution.

<p align="center">
<img src="https://i.imgur.com/mMY8PWg.png" alt="osTicket logo"/>
</p>

- #### Step 5: Set Up the MySQL Database
    Create a MySQL database for osTicket.

    Create a database user with the necessary privileges.

- #### Step 6: Run the osTicket Installer

    Enter database credentials and set up an admin account.

<p align="center">
<img src="https://i.imgur.com/cSQfPCU.png" alt="osTicket logo"/>
</p>

    Complete the installation and remove the setup directory for security.

- #### Step 7: Customize osTicket for IT Helpdesk Training
    Configure ticket categories (e.g., Hardware, Software, Network).

    Set up Service-Level Agreements (SLAs) to define response times.

    Assign user roles (Admin, Technician, End User) for realistic workflows.

    Start logging and resolving test tickets to simulate real IT scenarios.

- #### Step 8: Secure the System
    Configure firewall rules to restrict access.

    Install an SSL certificate for secure access.

- #### Step 9: Simulate an IT Support Environment
    Submit tickets via http://your-vm-ip/osticket/.

    Use the Admin Panel to manage and resolve tickets.

    Analyze ticket history to identify recurring issues and resolution trends.

<h2>Systems and Technologies Deployed</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
