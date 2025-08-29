<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/YIe4odQI5Wk?si=tG8oVeSK68Dl9j4F)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- IIS
- PHP Manager
- VC_redistx86
- MySQL 5.5.62
- Rewrite Module
- Heidi SQL

<h2>Installation Steps</h2>
<h2>Setting up osTicket in Azure VM</h2>

1. <strong>Create Virtual Machine in Azure:</strong>
- <strong>Log into Azure Portal</strong>
- <strong>Create a new VM with Windows Server.</strong>

<img width="2048" height="635" alt="azure_portal_osticket_vm_row_highlighted_v2" src="https://github.com/user-attachments/assets/318c88c3-0ade-407f-af3a-d08402ff3c63"/>



<p>



</p>
<p>

</p>
<br />

<p>
<img width="401" height="241" alt="rdp" src="https://github.com/user-attachments/assets/9400c4d2-bc86-40ec-96b7-40d0844e0f20" />

</p>
<p>
 - Use the VM’s public IP address to connect via Remote Desktop Connection (RDP).
</p>
<br />

<p>
<img <img width="449" height="558" alt="login for rdp" src="https://github.com/user-attachments/assets/287916b9-f9c2-4c77-99a6-99e7d912ca61" />
/>
</p>
<p>
- Log in using the credentials you created during VM setup (Reggie-admin in this example).
</p>
<br />




<strong>2. Download the osTciket-installation-Files.zip</strong>
<p>
  <img <img width="794" height="419" alt="unzip" src="https://github.com/user-attachments/assets/e9ee5a8d-0190-4fad-a7bc-8a8c7429f50b" />
 />
</p>
<p>
- Inside your VM download the https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD and unzip it onto your desktop. We will use the files to download osTicket.
</p>
<br />


<strong> 3. Enable ISS with CGI </strong>
<p>
  <img <img width="826" height="438" alt="Screenshot 2025-08-29 102918" src="https://github.com/user-attachments/assets/595ea493-840c-4862-93c9-34da303a275c" />
/>
</p>
<p>
- Go to the Control Panel > Then go to Programs > Programs and Features > Then on the left side of the screen, click "Turn Windows features on or off.
</p>
<br />



- <strong> Enable (internet information services) World Wide Web Services > Application Development Features > enable CGI </strong>
<p>
  <img <img width="417" height="723" alt="Screenshot 2025-08-29 102947" src="https://github.com/user-attachments/assets/fc1d6183-6fe3-4139-840a-a67a1f438e60" />
 />
</p>
<p>
</p>
<br />


<strong> 4. Download and Install PHP manager from the osTicket-installation-Files </strong>
<p>
  <img <img width="507" height="415" alt="Screenshot 2025-08-29 103007" src="https://github.com/user-attachments/assets/a497235c-5fa6-46b8-b5b3-8f66cb37456a" />
 />
</p>
<p>
- (PHPManagerForIIS_V1.5.0.msi)
</p>
<br />




<strong> 5. Download and Install the Rewrite Module</strong>
<p>
  <img <img width="501" height="392" alt="Screenshot 2025-08-29 103020" src="https://github.com/user-attachments/assets/580f7d9f-1b49-4689-b53f-9b7d07a8546f" />
 />
 />
</p>
<p>
- (rewrite_amd64_en-US.msi) from the osTicket-Installation-Files
</p>
<br />





<strong> 6. Create a directory in the C drive. Name the folder PHP. </strong>
<p>
  <img <img width="828" height="445" alt="Screenshot 2025-08-29 103032" src="https://github.com/user-attachments/assets/ae7026c9-63fe-42e0-b6a5-c181c1334c59" />
 />
 />
 />
</p>
<p>
- Go to file explorer and create the directory C:\PHP
</p>
<br />

