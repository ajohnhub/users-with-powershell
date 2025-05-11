<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating Users in Active Directory</h1>
This walkthrough demonstrates how to create users with PowerShell in Active Directory.  <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)


<h2>Deployment and Configuration Steps</h2>

<p>
</p>
<p>
To begin, Log into Client-1 as mydomain.com\jane_admin. Next, open system properties
and click “Remote Desktop”.Then, allow “domain users” access to remote desktop. You can now log into Client-1 as a normal, non-administrative user.
 

<br />
<p>
<img src="https://github.com/user-attachments/assets/5d9f99bc-9d69-49e3-bea0-9c07567783f7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to DC-1 as jane_admin
Open PowerShell_ise as an administrator

<img src="https://github.com/user-attachments/assets/8a9eacc2-fdef-4dc1-9d35-5a049e9f3128" height="60%" width="60%" alt="Disk Sanitization Steps"/>


</p>
<br />

<p>Create a new File and paste the contents of the script below into it:
https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1. Run the script and observe the accounts being created


<img src="https://github.com/user-attachments/assets/11d3579d-730c-4d90-956e-9ae9388bf92c" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
When finished, open ADUC and observe the accounts in the appropriate OU　(_EMPLOYEES)
</p>
<img src="https://github.com/user-attachments/assets/083500b6-9a4b-4b89-873b-25c5fe0ce914" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
</p>
Attempt to log into Client-1 with one of the accounts (take note of the password in the script).

</p>
<img src="https://github.com/user-attachments/assets/be8b7abb-7e0f-4c3f-893c-63beac2b2c8d"
height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/f2c0d69a-b72c-459f-9717-cfb16aecbd70"
height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>


