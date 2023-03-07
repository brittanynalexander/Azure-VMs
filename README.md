<p align="center">
<img src="https://i.imgur.com/Z0tGfHN.png" alt="Virtual Machine"/>
</p>


# Creating an Azure Virtual Machine (VM)
In this tutorial, we'll walk through how to create an Azure Virtual Machine (VM) and utilize Remote Desktop to connect to the created VM!


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>High-Level Steps</h2>

- Step 2
- Step 3
- Step 6
- Step 7

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/NqNnOVs.png" height="80%" width="80%" alt="Step 1 Creating Resource group"/>
</p>
<p>
Before we can create our VM we first have to create a Resource group, which you can have multiple of. Think of Resource groups as folders to store the resources you create such as VMs, Databases, Storage accounts, etc. From your Azure portal you can either click on the Resource groups icon or simply search "Resource groups" in the search bar then click "create". With that being said, let's create one. Scroll with me!
</p>
<br />

<p>
<img src="https://i.imgur.com/l2BALfL.png" height="80%" width="80%" alt="Step 2 Creating Resource group"/>
</p>
<p>
After filling in various details click "Review + create" to make sure everything entered is acceptable then click "create". You can double check this action by simply going to the Resource groups section. (Remeber you can click the icon or search for it.) Your section won't be empty anymore! Now that we have our resource group, let's get to creating our VM. Scroll with me!
</p>
<br />

<p>
<img src="https://i.imgur.com/QQC83PL.png" height="80%" width="80%" alt="Step 3 Creating Virtual machine"/>
</p>
<p>
If the Virtual machines icon doesn't appear on your home screen you can do a quick search then click "create". As always, there will be information to fill in and/or select. Hit "Review + create" then "create". It may take a little while until the process is completed because there are multiple resources being made with your VM. Let's take a look at those resources, scroll with me!
</p>
<br />


<p>
<img src="https://i.imgur.com/drkOJ5A.png" height="80%" width="80%" alt="Step 4 Resources made"/>
</p>
<p>
As stated, there are resources being simultaneously created along with your VM. The Disk is your hard drive. The Network Interface or Network Interface Card (NIC) is essentially like a virtual adapter which connects a computer to a network. The Virtual network is comparable to a switch, which is a device used to connect other devices that are on the same network. So instead of using a physical device, the virtual network or " virtual switch" being used is in the cloud. The Network security group is essentially like a firewall, in which you can control inbound and outbound network traffic according to a set of rules. Your Public IP address is accessible from the internet in comparison to your Private IP address which only you should have access to. The Virtual machine is, well, your VM! Let's view some essential information regarding it, scroll with me!
</p>
<br />


<p>
<img src="https://i.imgur.com/Z9rwAti.png" height="80%" width="80%" alt="Step 5 Virtual machine essentials"/>
</p>
<p>
To view the information regarding your VM simply go to the Virtual Machines section. You guessed it, either click the icon or search for it. Click on the name of your VM, I named mine "VM1". Within the Essentials section, you can see important information such as the type of Operating system (OS) you selected as your Virtual machine and your Public IP address to name a couple. The OS I chose as my VM is Windows. Let's get connecting, scroll with me!
</p>
<br />


<p>
<img src="https://i.imgur.com/kEn3Yix.png" height="80%" width="80%" alt="Step 6 Remote Desktop"/>
</p>
<p>
To connect to the VM on a Windows desktop computer you'll need to utilize Remote Desktop Connection. On your desktop next to the start key, type in "remote desktop" and click on "Remote Desktop Connection". On a MacOS you'll have to download "Microsoft Remote Desktop". Come on, we're getting closer to the actual connection, scroll with me!
</p>
<br />


<p>
<img src="https://i.imgur.com/X769Wy5.png" height="80%" width="80%" alt="Step 7 IP address"/>
</p>
<p>
Copy your Public IP address which you can easily find in your Virtual machine essentials and paste it in the "computer" section of your Remote Desktop Connection or your Microsoft Remote Desktop. Click "connect". You will then be asked if you still want to connect due to security reasons, hit "yes"! We're connecting .. Scroll with me!
</p>
<br />


<p>
<img src="https://i.imgur.com/EsdQGgm.png" height="80%" width="80%" alt="Step 8 Connection"/>
</p>
<p>
This is the desktop of your Virtual Machine, specifically running Windows 10. So cool right?! Cheers technology, cheers!
</p>
<br />
