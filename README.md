# Group Policy in Active Directory
Group Policy in Active Directory is a centralized management tool to control the working environment of user accounts and computers. Administrators use it to set policies, like security settings and software installations, across an entire organization. Group Policy Objects (GPOs) are linked to Active Directory containers, such as sites, domains, or organizational units. These GPOs automatically apply their settings to all users or computers within those containers. It simplifies and streamlines network management by ensuring consistent configurations.

<h2>Technologies used</h2>
-Microsoft Azure <br>
-Remote Desktop <br>
-Active Directory Domain <br>

<h2>Operating System used</h2>
- Windows 10 <br>
- Windows Server <br>

<h2>Configuration of Group Policy</h2>
<p>
<p align="center">
    <img src="https://github.com/user-attachments/assets/955a7c83-3646-4124-97ff-723aff9136cb" height="50%" width="50%" alt="getting to group policy"/>
</p>
<p>
In domain controllers go to start gpmc.msc to pull up the group policy management console. Then right click on the group policy object and select edit.
To find account lockout policy go to group management editor and do the following: computer configuration -> policies -> windows setting -> security settings -> account policies -> account lockout policy.
</p>
 <p>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/3955b7a1-7f59-4cef-921a-79ab41a84de4"
 height="50%" width="50%" alt="getting to group policy"/>
  </p>
  <p>
Tip: to update group policy on the employee computer go to command prompt and type gpupdate /force and enter
  </p>
<p>
<p align="center">
    <img src="https://github.com/user-attachments/assets/6b251966-69ac-48d8-b29e-f2d056384dcd"
 height="30%" width="30%" alt="disabling account"/>
</p>
<p>
 Right click on the employee account and select disabled or if needed enabled.
</p>
<p>
<p align="center">
    <img src="https://github.com/user-attachments/assets/8ac22f9e-6c9f-4ca4-9052-9e3b9e3025e0" height="30%" width="30%" alt="pasword reset"/>
</p>
<p>
Right click on the employee account and select reset password.
</p>
