<h1>JWipe - Disk Sanitization</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://imgur.com/JL8zPIx.png" height="80%" width="80%" alt="scenario overview"/>
<br />
<br />
TCPdump Log Overview:  <br/>
<img src="https://imgur.com/fmG7f6k.png" height="80%" width="80%" alt="TCPdump Log"/>
<br />
<br />
Log Findings: <br/>
<img src="https://imgur.com/ac1eXBc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
My analysis:  <br/>
<img src="https://imgur.com/5fVRWZj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
my analysis (Part 2):  <br/>
<img src="https://imgur.com/H8IvL0J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

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
