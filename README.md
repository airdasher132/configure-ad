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

- Ensure connectivity between client and domain w/ ICMPv4
- Install active directory
- Create admin and user accounts
- Allow client to join domain

<h2>Deployment and Configuration Steps</h2>

<p>

![image](https://github.com/airdasher132/configure-ad/assets/158870278/6b86cc50-28ea-4620-87bf-281820f80f39)



</p>
<p>
I set the IP address to static so any additional computers may contact the same address.
</p>
<br />

<p>

![image](https://github.com/airdasher132/configure-ad/assets/158870278/b8109e2a-76a2-4282-9d31-7ec80bc85828)


</p>
<p>

Allowing ICMPv4 traffic so other computers can connect to the domain controllers.
</p>
<br />

<p>

![image](https://github.com/airdasher132/configure-ad/assets/158870278/1a0e6dac-36c4-4114-b8c6-ac61a1a263b8)




</p>
<p>
Head to the domain controller and go to server manager. Start the installation for Active Directory on the designated machine.
</p>
<br />


<p>

![image](https://github.com/airdasher132/configure-ad/assets/158870278/9fa26581-1b91-4034-ac76-8007dcf96dae)

</p>

<p>
Create space for manually created employees and admins to access the domain and set their permissions.
</p>
<br />

<p>

![image](https://github.com/airdasher132/configure-ad/assets/158870278/6d97d77d-0e46-46dd-bb09-20c56106996c)



</p>

<p>
Allow any created user to connect via a remote desktop or any that is on a designated DNS to access the domain.
</p>
<br />
