<p align="center">
<img src="https://github.com/veralestina/Images/blob/main/97_virtual-machine.21c22fa0f5.png" alt="Microsoft Azure Logo"/>
</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
- MAC OS


<h2>Deployment and Configuration Steps</h2>
<p>
First step, is to go to the Azure website. Type in 'portal.azure.com' to get to the correct site.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/gotoportal.png" height="50%" width="50%" alt="portal website"/>
</p>
<p>
The next step is to create a resource group. In order to do this we need to go to the resource group page. Type in 'Resource Group' into the search bar and click on the image below.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/gotoresourcegroup.png" height="50%" width="50%" alt="Go to Resource Group"/>
</p>
<p>
We need to create a rource group in order to create a virtual machine, so we are going to click on the 'Create' button like below to create our Resource Group.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/clickcreateforresourcegroup.png" height="50%" width="50%" alt="Click Create Resource Group"/>
</p>
<p>
It will open to a page that looks similar to below. Fill out the the page, make sure to pick the location that works best for you, depending on what your needs are and what the cost will be. Once everything is filled out, click 'Create'. 
</p>
<br />

<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/createresourcegroup.png" height="50%" width="50%" alt="Create Resource Group"/>
</p>
<p>
Once you click 'create' you will be taken to a validation page. It will tell you whether or not you have correctly created a resource group and will give you the opportunity to see what the costs will be to run the resource group that has been created. It should like below if the resource group has been successfully validated. Click 'Create' when satisfied that the information is correct and validated in order to create the Resource Group.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/resourcegvalidated.png" height="50%" width="50%" alt="Resource Group Validated"/>
</p>
<p>
It may take some time for the Resource Group to fully load after clicking create. Head back to the Resource Group page and when the Resource Group is successfully created, it should look like below, with the name you gave it.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/rglab01created.png" height="50%" width="50%" alt="RGlab01 created successfully"/>
</p>
<p>
Once the Resource Group has been created successfully, we can create our virtual machine. In order to do this, we must go to the Virtual Machine page. Type 'Virtual Machine' into the search page and the below should pop up. Click on it to go to the virtual machine page.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/gotovirtualmachine.png" height="50%" width="50%" alt="Go to Virtual Machine"/>
</p>
<p>
Once at the Virtual Machine page, click on 'Create' to create the virutal machine.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/clickcreateforvm.png" height="50%" width="50%" alt="Click create Virtual Machine"/>
</p>
<p>
The below will pop up after clicking 'Create'. We want to click on 'Azure Virtual Machine' for this lab.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/clickazurevirtualmachine.png" height="50%" width="50%" alt="Click Azure Virtual Machine"/>
</p>
<p>
We will be taken to a page like below. Choose Subscription 1 and make sure to choose the Resource Group that you previously created for your resource group for your virtual machine, like the picture below.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/clickresourcegroupalreadycreated.png" height="50%" width="50%" alt="Choose Resource Already Created"/>
</p>
<p>
Next fill in the rest of the blanks, we want to create a windows 10 computer and we want to make sure that the location of the virtual machine is the same as the resource group that we previously created. Next, make sure to create a username and password for the virtual machine. You're going to use this username and password in order to login to the remote desktop into the virutal machine at the very end of this lab so make sure to remember them.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/createusernameandpasswordforlogin.png" height="50%" width="50%" alt="Create username and password for virtual machine"/>
</p>
<p>
Click create virutal machine. You should then be taken to a page like the one pictured below.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/createvm.png" height="50%" width="50%" alt="Create virtual machine"/>
</p>
<p>
It may take a while for the virtual machine to load but click 'Create' again. Go back to the virtual machine page using the search function and if the virtual machine creates successfully, it should like the picture below.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/vmlab01created.png" height="50%" width="50%" alt="Successfully created virtual machine"/>
</p>
<p>
We're going to use a MAC computer to login to our windows virtual machine. In order to do this, you need to download Microsoft Remote Desktop to your MAc computer. In order to login to a virtual machine, you need to virtual machine's IP address. Go back to the virtual machine page and click on your newly created virtual machine. It should open to a page like the picture below.
</p>
<br />

<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/openvmforipaddress.png" height="50%" width="50%" alt="Open VM for IP address"/>
</p>
<p>
next, go to the public IP address for the virtual machine and copy it.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/copyipaddress.png" height="50%" width="50%" alt="Copy IP address"/>
</p>
<p>
Open the Remote Desktop application for MAC and get to the page like below.
</p>
<br />
<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/remotedesktop(mac).png" height="50%" width="50%" alt="open remote desktop for MAC"/>
</p>
<p>
Click on 'Add PC' When prompted, paste the IP address you copied from the virtual machine. Click enter.
</p>
<br />

<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/ADDIPADDRESS.png" height="50%" width="50%" alt="Add IP address"/>
</p>
<p>
It may take a while to load but should look like the picture below with the IP address that you copied from the virtual machine listed on your remote desktop application. Click on it and the login page should appear. Here is where you enter the username and password that you created earlier when you created your virtual machine. You should successfully be able to login to your virtual windows computer from your mac!
</p>
<br />

<p>
<img src="https://github.com/veralestina/Images/blob/main/Creating%20a%20virtual%20machine%20in%20azure/successfullyaddremote.png" height="50%" width="50%" alt="Successfully added IP address for remote access of virtual machine"/>
</p>


