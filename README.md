<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Deploying Software with Group Policy</h1>
This tutorial outlines the implementation of deploying software with group policy in Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy Software with Group Policy](https://youtu.be/cG7M3Z-Cek4)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

  

<h2>Operating Systems Used </h2>

- Windows Server 2022

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a folder called 'Software'
- Download 7zip file
- Share and permit users to file folder
- Run active directory
- Create a new GPO called 'Software_Deployment_7zip_v1701'
- Download software installation 
- Command prompt for verification and/or login to user to verify software is on computer.


<h2>Deployment and Configuration Steps</h2>

<p>



</p>
<p>
Diagram
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/a75afe7c-115e-4608-8dde-adb6fae7929a" height="80%" width="80%""/>
</p>
<p>
Created a new folder called 'Software' and added 7zip file into the folder.
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/3dea41d9-3c9a-43c0-b684-2c55a981f562" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/1222d68c-d671-41d5-bb7b-44806dbeca72" height="80%" width="80%""/>
</p>
<p>Creating a new GPO into the mycybercat.com domain and calling it 'Software_Deployment_7zip_v1701'
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/6cab53b7-fb24-45ed-bede-558b60ee0017" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/a867f0d2-2078-4873-bd9a-e97876193c32" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/df931ffa-dbb3-4453-a9e4-64dda608e8c3" height="80%" width="80%""/>
</p>
<p>
The Software Package was installed and assigned. Also you can see on your desktop. So the next time a user logs into their computer, the Software is donwloaded.
</p>
<br />
