<p align="center">
<img src="https://i.imgur.com/hnS8d9S.jpg"/>
</p>

<h1>Resource Group and Virtual Machine Creation (Azure)</h1>
This short tutorial explains how to create a Resource Group and Virtual Machine together, a link to creating a Resource Group separately, and the basics of
how to use a remote desktop and connect to your virtual machine.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: What a Resource Group is and how to create one within Azure](https://www.youtube.com/watch?v=lafIQLYC7Ss)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Microsoft Azure (Resource Group)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- (https://portal.azure.com/)
- [Creating Resource Group Seperately](https://portal.azure.com/#create/Microsoft.ResourceGroup)
- Virtual Machine - Create
- Virtual Machine - Create - Creation Type
- Virtual Machine - Configuration
- Virtual Machine - Config + Resource Group Creation
- Remote Desktop Basics + Accessing Virtual Machine/Network


<h2>Deployment and Configuration Steps</h2>

<p>
You will first start by selecting Virtual Machine or searching for it at the top of your screen and pressing Create.
<img src="https://i.imgur.com/6xcGjK7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After pressing create a small drop-down menu will open, please click the first option -"Azure Virtual Machine".
<img src="https://i.imgur.com/BRsJSKY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
Next, you will be sent to a screen to start your Virtual Machine Configuration. Your first task is to select an active
<p>
"Subscription". 
The next task is to select or create a Resource Group, Virtual Machine name, Region, and Operating System.
<p>
<img src="https://i.imgur.com/vci1VQN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 Create the name for your Resource Group here, remember that this name is character-sensitive.
<img src="https://i.imgur.com/gEbLxa6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
"Image" is where you will select the operating system that you wish to run your Virtual Machine on.
<img src="https://i.imgur.com/agEdyMd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
 After completing the last task you will scroll to the end of the page and select the size of the
 Memory, vcpu, and pricing, after selecting your size you now need to create a username and password.
</p>
 *Note* If you're using a free subscription the options that you are presented with may vary.
 The last thing needed for this page is to check the licensing box at the bottom, please beware that
 if you are using this for production on your own you will need to check if you have the license
 to use the operating system.
<img src="https://i.imgur.com/i50YStC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
As you can tell by the top of this screen there are a lot of different tabs to customize 
your Virtual Machine, if you have configurations that you want to use do so now. **WARNING!!!** Unless you
understand how to configure a virtual machine it's best to use the preset values presented. *Note 
most common changes that are made are to the networking tab.
<img src="https://i.imgur.com/oMBMRSC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ChGrJZ1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
The first task on this tab is to select a virtual network, your resource group you just created is the
default option the system will use unless there is another or you want to create one. The subnet
and the public IP will be created for you as well. If you have followed the steps you are able to press review
and create.
<img src="https://i.imgur.com/zRrNkGj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Once accepted you will see this next screen and then you are ready to
create your virtual machine if there are no changes needed select Create.
<img src="https://i.imgur.com/PVkxRXO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
Once you have selected Create you will see this screen and at this time Azure is creating your Virtual Machine, plug-ins,
add-ons, and any other network connections needed for it to function properly.
<img src="https://i.imgur.com/RP2auTO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Esg4qXM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<h2>Remote Desktop and How to connect to your VM</h2>

<p>
Remote Desktop Connection is a feature of Microsoft Windows that allows a user to remotely access another computer over a network connection.
If you are using a MAC you would need to download:
  
- ### [Microsoft Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)
</p>

- (https://portal.azure.com/) Once you have located and or downloaded the remote desktop go back to your portal
- Access your Virtual Machine page
- Copy your Public IP address
- Use your username and password when creating your VM
- Connect to your Virtual Machine
- Simulate scenarios

<p>
<img src="https://i.imgur.com/EpCycrM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
