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
A simple ping test from PC1 to all printers was performed for connectivity: <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445253184468811927/Screenshot_2025-11-30_194913.png?ex=694c04aa&is=694ab32a&hm=42bace6035560268351783d2097949fa77be62fa9b9a739b0f2c376d52a8968f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Here I tested connectivity from one department to another pc in another department (PC0 TO PC2): <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445254540109545563/Screenshot_2025-11-30_194739.png?ex=6969afad&is=69685e2d&hm=c7dd02d42bdd69614ea8ee39eb809afec39ba6adda986e5d3908e67971ed72fa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I assigned a static IP address range here in the router to receive traffic, and a subnet mask is assigned as well for each department:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445256985133187072/Screenshot_2025-12-01_213317.png?ex=693ed934&is=693d87b4&hm=5f0595a2494f0fc22670ce7619b5d8f6cd92d349a12ea83eced7f790bae32894"/>
<br />
 <br />
This is an example of a static address used for the delivery department (PC2) as follows. Each department obtains 2 pcs and a printer:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445257958404522045/Screenshot_2025-12-01_213614.png?ex=69690a1c&is=6967b89c&hm=aff06da2ffc2ecd128b647e33f3a596dd7c06bd4c8d5503f1a74d12465a79c7c"/>
<br />
 <br />
 This is a full-scale look at all connections on the enterprise network:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445253629840855143/Screenshot_2025-11-30_194813.png?ex=6969aed4&is=69685d54&hm=45ba5853a2cdcbcb40e76059586d233770c86cbd9086f6e9c23c7e0574661014"/>
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
