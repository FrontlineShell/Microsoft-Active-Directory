# Microsoft-Active-Directory
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

- Create virtual machine
- Ensure connectivity between Client and domain controller
- Install active directory
- Create and admin and normal user account 

<h2>Deployment and Configuration Steps</h2>

-Be sure to create virtual machine under domain controller and window server using 2 vcpus so it can run faster.
set domain controllers NIC private IP address to static
Make sure client VM is created in window 10

-Ping client to domain controller
from domain controller enable ICMPv4 on local window firwall

-Install active directory domian services in domain controller
set up new forest as domain.com 
restart then log back into domain controller

-In active directory user and computers creater organizational unit
create new imployee name and admin
create new domain controller

-



