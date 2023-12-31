
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 Craeted Virtual Machines in Azure for Domain Controller named DC-1 and for Users named Client-1 (CC-1) 
- Step 2 Set the Domain Controller's NIC Private IP address to be Static
- Step 3 Installed Active Diectory Domain Services
- Step 4 Created an Admin and Users Account on Active Directory
- Step 5 Logged into Client-1 to link with Domain Controller.

<h2>Deployment and Configuration Steps</h2>


 ![1 Dc-1 VMa](https://github.com/waleoyecc/configure-ad/assets/140360882/d77bea9b-ca43-45f2-aaac-8f9e3cca0e4a)


   ![2 Dc-1 VMb](https://github.com/waleoyecc/configure-ad/assets/140360882/8df9e69c-0e03-4650-8240-8150782a516f)

</p>
<br />

</p>
<p>
LVirtual Machine Domain Controller named DC-1 created on Azure with Operating System - Windows Server 2022. Also displayed are the Resource Group name, IP Address, Virtual CPU size and Subnet 
<br />

 ![4 Cl-1 VMa](https://github.com/waleoyecc/configure-ad/assets/140360882/c9f25acc-9f05-484f-a0f1-f1486870c922)


   ![6 Cl-1 VMc](https://github.com/waleoyecc/configure-ad/assets/140360882/88f2b939-1f3a-4855-b4c6-d76ae017a807)
   
   Virtual Machine Created with Operating System Windows 10 (21H2) Computer named CC-1 created on Azure to connect to the Domain Controller named Dc-1. Also displayed are the Resource Group name, IP Address, Virtual CPU size and Subnet 

![Nvm1 Static](https://github.com/waleoyecc/configure-ad/assets/140360882/5fba394f-654b-4dff-8072-4fd30ad80e55)<p align="center">
   
 The Domain Controller's NIC Private IP address set to be Static
   
  ![Nvm Dc server mgr AD instld](https://github.com/waleoyecc/configure-ad/assets/140360882/150963a0-9a22-42bc-baba-b9c92b139ef5)

 The complete checks of Prerequisites for the installation of Active Directory on Donmain Controller (DC-1) Server

   ![Nvm Dom name creating users](https://github.com/waleoyecc/configure-ad/assets/140360882/1395f485-86f7-4a68-b56b-19e88e07b71f)

 PowerShell ISE used to create users who can connect to the Domain Server from CC-1 
 
 ![Wale Ad new users adm staf](https://github.com/waleoyecc/configure-ad/assets/140360882/83acc177-1568-418b-8414-4e5731a5d556)
 
The Organizationlal Unit Set up Active Directory for new users; ADMIN and STAFF were set up
 
 ![Wale-Ad](https://github.com/waleoyecc/configure-ad/assets/140360882/43a86d38-f856-485d-bc6e-eee3c1729787)
 
  Logged in to Remote Desktop after Active Directory Configuration. 

  ![Wale Ad new adm log in](https://github.com/waleoyecc/configure-ad/assets/140360882/18451b08-1469-4405-aa5f-b958107af8cf)

  Logged in as Admin and checked name for new Admin set up 

