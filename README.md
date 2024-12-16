# Remote-Desktop-Connection

<p align="center">

</p>

This tutorial shows how to use RDP to connect with a virtual machine<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)


<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Account
- Internet Connection
- Computer or Laptop


<h2>Connection Steps</h2>

<p>
<img src="https://imgur.com/tcqwRXq.png" height="80%" width="80%"/>
</p>
<p>
On the overview page of the virtual machine you created, copy the public IP address. We are going to need it to connect remotely to the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/fBzUs1i.png" height="80%" width="80%"/>
</p>

1. The screen above shows the basics tab. Select your Azure subscription.
2. You can now create a resource group or select one that has already been made.
3. Then, choose a name for your virtual machine and then select the region that you are operating in.
4. For availability zones and security type, you can select the first option.
5. The next option is for the operating system, you can just select Windows 10 or 11.
6. The last step is the size. For now you can choose the 1 vcpu thats the cheapest. For larger projects like running Osticket or an active directory, i would use an option with more virtual processors.
7. Create your username and password
8. Select the networking tab.


<br />

<p>
 <img src="https://imgur.com/P9vPF63.png" height="80%" width="80%"/>
</p>

<p>
 The above image is the network tab. Here you can see the default name for your virtual network, subnet and public IP address. Make note of them and select review+create, which is the final tab.
</p>
<br />

<p>
<img src="https://imgur.com/osYsKsl.png" height="80%" width="80%"/>
</p>
<p>
On this tab, we can see an overview of the virtual machine along with its cost, which is mostly determined by the size that was chosen. The fewer the virtual processors, the cheaper it usually is. From here, we can just click on create at the bottom.                        
</p>
<br />

<p>
 <img src="https://imgur.com/uDJ7qqV.png" height="80%" width="80%"/>
</p>
<p>
 It will take a little bit for the virtual machine to deploy.
</p>

<p>
 <img src="https://imgur.com/6LFV9qt.png" height="80%" width="80%"/>
</p>

<p>
 This screen confirms that the virtual machine has been successfully deployed.
</p>

<p>
 <img src="https://imgur.com/zxRnLfd.png" height="80%" width="80%"/>
</p>

<p>
Back on the home screen, you can see both the virtual machine and the resource group associated with it. If they do not appear at all, refresh the webpage.
</p>

<p>
 <img src="https://imgur.com/sCu252E.png" height="80%" width="80%"/>
</p>

<p>
 Clicking on the virtual machine will show you all it's resources including the ip address and the security group where you can tinker with the firewall.
</p>

<p>
 <img src="https://imgur.com/zMYwUvI.png" height="80%" width="80%"/>
</p>

<p>
 To delete the virtual machine and the resource group, select the resource group and and then press delete resource group. You then have to type it out at the bottom of the right window it order to confirm it.
</p>

  We now have a working virtual machine running in Azure. In the next session, we will discuss how to use remote desktop connection with the virtual machine.




