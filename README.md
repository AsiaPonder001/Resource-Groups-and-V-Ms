<p align="center">
  <img src="https://i.imgur.com/wWBmJ7Q.png">

  
<h1> Creating Resource Groups and Deploying Virtual Machines</h1>

Hello! In this quick tutorial I will be creating a Resource Group in Azure and Deploying two Virtual Machines.
<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
<br/>

<h1> Create a Resource Group</h1>

<b> Click Resource Groups </b>

<img src="https://i.imgur.com/NrGgVuJ.png">

<b> Click Create </b>

<img src="https://i.imgur.com/UJTuszX.png">

<b> Name Resource Group and Select a Region</b>

<img src="https://i.imgur.com/fLHYXfd.png">

<b> Once it Passes Validation, Click Create </b>

<img src="https://i.imgur.com/6deTcDx.png">

<b> The Resource Group is Created successfully</b>

<p> Now Click on Virtual Machines. If you do not see It at the top type It In the bar above</p>

<img src="https://i.imgur.com/xL1DRc5.png">

<b> Click Azure Virtual Machine </b>

<img src="https://i.imgur.com/NhP73RP.png">

- Click the resource group we just created
- Name the Virtual Machine
- Select the region (should be the same as the resource group)
- Select Windows 10 under Image
- Choose Standard size

<img src="https://i.imgur.com/dCdqLvl.png">
<img src="https://i.imgur.com/LWfS961.png">

<b> Pick a username and password </b>

<p>Click Review+Create at the bottom (generally don't need to select any of the other tabs; possibly the Networking tab however you should be able to successfully create the VM) </p>

<img src="https://i.imgur.com/aOgot3Z.png">
<b> Click Create</b>
<img src="https://i.imgur.com/VygfVOP.png">
<img src="https://i.imgur.com/9Xorpyy.png">

<b>Create Another VM</b>
<p> This time it will be a Domain Controller (Windows server 2022) </p>
- Same Resource Group
- Same location

<img src="https://i.imgur.com/x80cYg2.png">
<img src="https://i.imgur.com/s59AcEf.png">
<img src="https://i.imgur.com/bW3yEsO.png">

<img src="https://i.imgur.com/uH5X8d0.png">


<h1>Log Into Your VMs Using Remote Desktop</h1>

<img src="https://i.imgur.com/9xZm757.png">
<img src="https://i.imgur.com/pQ75TNI.png">

<img src="https://i.imgur.com/63QtNtj.png">
<img src="https://i.imgur.com/G5Rd7kJ.png">

The End.
