# Enterprise-Network-For-Small-Office

<h2>Description</h2>
Design a network in CISCO packet tracer to connect ACCOUNTS and DELIVERY departments. 

1) Each department should contain at least 2 PCs. An appropriate number of switches and routers should be used in this network.

2) The ISP has given the network address of 192.168.40.0; all interfaces  should be configured with  appropriate IP addresses, subnet mask, and gateways.
 
3) All devices in the network should be connected using  the appropriate cables.

4) Test the connectivity between the ACCOUNTS and DELIVERY department PCs; the DELIVERY department should be able to ping the PCs in the ACCOUNTS department.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Command Prompt</b> 

<h2>Environments Used </h2>

- <b>CISCO packet tracer</b> 

<h2>Program walk-through:</h2>

<p align="center">
Both departments were cabled in correctly: <br/>
<img src="https://reasonable-fuchsia-thx1ds7cio-vqd46fow67.edgeone.dev/Screenshot%202025-11-30%20194813.png" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
Static addresses were given to each PC and printer in both departments: <br/>
<img src="https://unfortunate-magenta-y6oadwtsh3-fx4d5ig140.edgeone.dev/Screenshot%202025-12-01%20213614.png" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
Here I configured the router to be enabled with each Ethernet cable going to each department switch to have them powered on and processed static IP addresses for each device after the switch: <br/>
<img src="https://i.imgur.com/jfa1icJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A simple ping test from PC3 to all printers was performed for connectivity: <br/>
<img width="2515" height="1221" alt="Screenshot 2025-11-30 194913" src="https://github.com/user-attachments/assets/a3911b93-df43-4c76-86c9-91ae00b8ffd4" />
<br />
<br />
Here I tested connectivity from one department to another pc in another department (PC0 TO PC2): <br/>
<img width="2483" height="1243" alt="Screenshot 2025-11-30 194739" src="https://github.com/user-attachments/assets/bddbcdb7-c800-47fe-bdfb-aa820fe49ace" />
<br />
<br />
I assigned a static IP address range here in the router to receive traffic, and a subnet mask is assigned as well for each department:  <br/>
<img width="2546" height="1382" alt="Screenshot 2025-12-01 213317" src="https://github.com/user-attachments/assets/99cc993a-5534-4416-9b59-c20a589bf665" />
<br />
 <br />
This is an example of a static address used for the delivery department (PC2) as follows. Each department obtains 2 pcs and a printer:  <br/>
<img width="2460" height="1198" alt="Screenshot 2025-12-01 213614" src="https://github.com/user-attachments/assets/ca375740-b25f-47df-a0d8-73fa746e87f4" />
<br />
 <br />
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
