<h1>Configure Configure Custom script extensions</h1>

<h2>Description</h2>
This lab will Configure Custom script extensions. Extensions are great way to have applications installed when you VM is launched.<br />
This lab will be configure Custom script extensions for a Windows web server. The process in the same for a Linux server.<br />
The IIS web server application will be installed on the Virtual machine.<br />
This lab will assumes that you know the basics of Powershell.<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Step 1</h4>
Write the code script for you Extension<br/>
<img src="https://i.imgur.com/xFOhN2H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<h4>Step 2</h4> 
Create a storage account.<br/>
<img src="https://i.imgur.com/htqL70S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
Place the script in your storage account.<br/>
<img src="https://i.imgur.com/QCwk07j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Step 3</h4> 
Create a new Windows virtual machine, allow port 80 for web traffic.<br/>
<img src="https://i.imgur.com/XJiMtiA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
In the advanced tab, add your custom script extension.<br/>
<img src="https://i.imgur.com/KIOaSh6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>


<h4>Step 4</h4> 
Confirm that your script has been provisioned.<br/>
<img src="https://i.imgur.com/A3zQ7WW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
Confirm that you can access your we server, via apublic IP address.<br/>
<img src="https://i.imgur.com/gOeblc7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

