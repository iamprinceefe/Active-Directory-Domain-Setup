<h1>Active Directory Domain Setup on Windows Server 2019</h1>


<h2>Description</h2>
This project demonstrates setting up an Active Directory domain using Windows Server 2019. The repository includes a step-by-step guide to installing and configuring Active Directory Domain Services (AD DS) and creating and managing user accounts.
<h2>Utilities Used</h2>

- <b>Active Directory Domain Services (AD DS)</b>


<h2>Environments Used </h2>

- <b>VirtualBox</b>
- <b>Windows 10</b>
- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Set up VirtualBox and Windows Server Configuration: <br/>
<img src="https://i.imgur.com/wACHj5S.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/bS5h4dV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/kW8WPpA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ysfJ0OW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Windows Server:  <br/>
<img src="https://i.imgur.com/sfP0lJI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After Installation is complete, create a User:  <br/>
<img src="https://i.imgur.com/v6f6Vue.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login:  <br/>
<img src="https://i.imgur.com/ZivFvVy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/V8XkyZQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/V2LAb4J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
(After the complete setup, shut the VM and Restart) <br/>
Then click on “Add roles and features”:  <br/>
<img src="https://i.imgur.com/0CtotpA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click on Next:  <br/>
<img src="https://i.imgur.com/ITUcDza.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Select Role-based or feature-based installation:  <br/>
<img src="https://i.imgur.com/WYfafQG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Select the Server to use and choose AD Directory Domain Service:  <br/>
<img src="https://i.imgur.com/qilsq9L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click Next:  <br/>
<img src="https://i.imgur.com/1MIHeK4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Wait for the Installation:  <br/>
<img src="https://i.imgur.com/J6nBPRB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
(After Installation, Restart the Server. When you restart and Log back in, you'll notice a yellow notification on your top right) <br/>
Click on the Notification and "Promote the server to a domain controller"<br/>
<img src="https://i.imgur.com/ROeI2Kw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Add a Domain Name:  <br/>
<img src="https://i.imgur.com/JMv97QZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Setup a new forest and domain name:  <br/>
<img src="https://i.imgur.com/s4QrsM0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click Next all through and Install:  <br/>
<img src="https://i.imgur.com/jAy0J3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
The server will automatically reboot:  <br/>
<img src="https://i.imgur.com/e5RnsCY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Notice the name change, Now login again:  <br/>
<img src="https://i.imgur.com/jLh2tSP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create your domain account:  <br/>
<img src="https://i.imgur.com/Mvut6M4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create your Organization unit:  <br/>
<img src="https://i.imgur.com/snAtTZt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/ocdcSvO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create a New User and make the User an Admin:  <br/>
<img src="https://i.imgur.com/YLcaB0z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/Y5S8oQm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/mIapBkq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/6qPOtBE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/H4zg0RP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/jjx3Voj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/eZBVVsR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Then sign out and switch to the newly created user:  <br/>
<img src="https://i.imgur.com/m3577Wx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/iItiENB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />



<h2>Conclusion:</h2>
In this project, I successfully set up an Active Directory domain using Windows Server 2019. The process included the installation and configuration of Active Directory Domain Services (AD DS), DNS setup, and the creation of a domain. Additionally, I created a user account and assigned administrative privileges to it, demonstrating user management within the domain. This project showcases the fundamental steps required to establish and manage an Active Directory environment, providing a solid foundation for further exploration and implementation of enterprise-level directory services.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
