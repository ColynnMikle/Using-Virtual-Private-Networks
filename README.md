# Using-Virtual-Private-Networks
A process outlining the installation and use of virtual private networks, or VPNs.
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN
<p></p>
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Objectives</h2>

- Create virtual machine (VM) inside of Azure portal.
- Obtain public IP address
- Create a Proton VPN account
- Select a geographic region inside of Proton VPN
- Test browsing within new VPN

<h2>Configuration Steps</h2>

<p>
<p>
- To begin, create a virtual machine from the Azure portal. Using an active Azure subscription, navigate to the Resource Group page via the search bar. Create a new resource group. 
<p></p>
- Access the Virtual Machines page via the Azure portal. Create a new VM using a Windows 10 operating system. Take default settings unless other specifications are desired.
<p></p>
- Once creation and deployment are complete, go to the virtual machine page for the newly created VM and make a note of the public IP address.
<p></p>
- Access your PC's remote desktop window via the start menu and select the new PC option. Input the public IP found earlier. Access the VM with the created username and password. Complete initial start up process and navigate to Edge. 
<p></p>
- Search for Proton VPN online and select the download page. Create a Proton VPN account. Make a note of the login credentials used. Press the blue "Download Proton VPN". A download will start. When the download is complete, open the file and complete the download wizard. It is fairly straightfoward and no elaboration is required. Alternatively, you can create your account in your physcial PC and simply access the Proton portal and login inside the VM.
<p></p>
- When all installation is complete, open Proton VPN and use the login credentials. A page will be displayed that looks similar to the one displayed below.
<p></p>
<p></p>
<img src=https://i.imgur.com/YwShlXZ.png
</p>
<p>
- Here, you may use the menu to the bottom left to select your desired geographic region depending on the subscription you created. Alternatively you can select quick connect, which will randomly assign a region to you and connect you. 
</p>
- NOTE: After selecting a region to connect to, if using a VM, you may be momentarily disconnected from your remote connection. This is normal.
<p></p>
- I was assigned the Netherlands and when testing the browser, my Google homepage appeared as shown below.
<p>
<p>
<img src=https://i.imgur.com/qiHMGn1.png</p>
<p>
<img src=https://i.imgur.com/xz9UD8L.png
<p>
<p>  
- The page you browse to after selecting a region through Proton will now default to that region's version of whichever page you search.
</p>
- You can visit whatismyipaddress.com after connecting to the VM to see your new public IP and assigned geographic location. Below is a before and after of my experience.
<p></p>
-Before
<p>
<p>
<img src=https://i.imgur.com/PZgGdyF.png)https://i.imgur.com/PZgGdyF.png</p>  
</p>
<p></p>
-After
<p>
<p>
<img src=https://i.imgur.com/u4dizBQ.png  
</p>
  /
