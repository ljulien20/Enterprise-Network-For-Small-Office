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
Static addresses were given to each PC and printer in both departments:  <br/>
<img src="https://unfortunate-magenta-y6oadwtsh3-fx4d5ig140.edgeone.dev/Screenshot%202025-12-01%20213614.png" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
Here I configured the router to be enabled with each Ethernet cable going to each department switch to have them powered on and processed static IP addresses for each device after the switch: <br/>
<img src="https://i.imgur.com/jfa1icJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A simple ping test from PC1 to all printers was performed for connectivity:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445253184468811927/Screenshot_2025-11-30_194913.png?ex=693ed5aa&is=693d842a&hm=f2eaee48407c4ad1e9791bbeeaa0acce32aee44af97f7e4f3cb2a47e9a19477a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Here I tested connectivity from one department to another pc in another department (PC0 TO PC2):  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445254540109545563/Screenshot_2025-11-30_194739.png?ex=693ed6ed&is=693d856d&hm=0f3e69123fe180ad10eeb598247c4832246ad7700a54ff5f7855501bb21eaaf4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I assigned a static IP address range here in the router to receive traffic, and a subnet mask is assigned as well for each department:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445256985133187072/Screenshot_2025-12-01_213317.png?ex=693ed934&is=693d87b4&hm=5f0595a2494f0fc22670ce7619b5d8f6cd92d349a12ea83eced7f790bae32894"/>
<br />
 <br />
This is an example of a static address used for the delivery department (pc2) as follows. Each department obtains 2 pcs and a printer:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445257958404522045/Screenshot_2025-12-01_213614.png?ex=693eda1c&is=693d889c&hm=52e2977e2fc4a8e66f0e73620c41a75ce0a11d06cbbf4087c2538f54f9f7227c"/>
<br />
 <br />
 This is a full-scale look at all connections on the enterprise network:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445253629840855143/Screenshot_2025-11-30_194813.png?ex=693ed614&is=693d8494&hm=0804d84d64e4b57d050a5fca6aa93965d694e9caddd35407673a0db1fc5af6cc"/>
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
