<p align="center">
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

  Virtual Machine Domain Controller named DC-1 created on Azure with Operating System - Windows Server 2022 . Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.


   ![2 Dc-1 VMb](https://github.com/waleoyecc/configure-ad/assets/140360882/8df9e69c-0e03-4650-8240-8150782a516f)

</p>
<br />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

 ![4 Cl-1 VMa](https://github.com/waleoyecc/configure-ad/assets/140360882/c9f25acc-9f05-484f-a0f1-f1486870c922)

Virtual Machine Created with Operating System Windows 10 (21H2) Computer named CC-1 created on Azure to connect to the Domain Controller named Dc-1. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /> 

   ![6 Cl-1 VMc](https://github.com/waleoyecc/configure-ad/assets/140360882/88f2b939-1f3a-4855-b4c6-d76ae017a807)
   Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  ![Nvm Dc server mgr AD instld](https://github.com/waleoyecc/configure-ad/assets/140360882/150963a0-9a22-42bc-baba-b9c92b139ef5)
  
 ![Nvm Dom name creating users](https://github.com/waleoyecc/configure-ad/assets/140360882/b8f0574e-981c-4342-9c12-fb1818df23df
 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
 ![Wale Ad new users adm staf](https://github.com/waleoyecc/configure-ad/assets/140360882/83acc177-1568-418b-8414-4e5731a5d556)
 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
 ![Wale-Ad](https://github.com/waleoyecc/configure-ad/assets/140360882/43a86d38-f856-485d-bc6e-eee3c1729787)
  Logged in to Remote Desktop after Active Directory Configuration. dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

