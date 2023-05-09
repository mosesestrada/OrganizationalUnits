<p align="center">
 <img src="https://i.imgur.com/02ZF2ak.jpg" height="80%" width="80%" alt="ou logo"/>
</p>

<h1>Creating Organizational Units </h1>


<h2>Description</h2>

Organizational Units (OUs) are the backbone of efficient network infrastructure management! With OUs, you can effortlessly organize and control crucial domain objects, such as users, groups, and computers. By creating OUs, you gain the power to delegate administrative control over specific sets of objects, making network management a breeze.

And today, we're taking things up a notch! In our demonstration, we'll be adding not just one, but several OUs to our domain. But that's not all. We'll also be diving deep into the world of OU nesting, as we show you how to group multiple OUs within a single one for optimal organization. Trust me, it's going to revolutionize the way you manage your network infrastructure.

Get ready to unlock the full potential of your domain with the incredible organizational capabilities of OUs. It's simple, it's efficient, and it's essential for any network administrator.

<br />

<h2>Environments Used </h2>
 <b>Windows Server 2019 </b> <p>
 <b>Hyper-V</b></p>
<h2>Program walk-through:</h2>

<p align="center">
From the left pane of Hyper-V Manager, select your Hyper-V host server which in this demonstration is "CORPSERVER". From the Virtual Machines pane, right-click your domain controller, which in this example is "CorpDC" and then select Connect.


<br/>
<img src="https://i.imgur.com/jLl9Z4k.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
From Server Manager's menu bar, select Tools then select Active Directory Users and Computers.
Select Next.
 <br/>
<img src="https://i.imgur.com/xipIW1F.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
From the left pane, right-click CorpNet.xyz and then select New then Organizational Unit.
 <br/>
<img src="https://i.imgur.com/7hUq1U7.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Enter the name of the OU to be created.

 <br/>
<img src="https://i.imgur.com/iw6j2za.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Repeat those steps until you've inserted all your OU's. For this demo I've added the following OU's: Accounting,
Admins, Marketing, Research-Dev, Servers Support, Workstations, & Sales.
<br/>
<img src="https://i.imgur.com/ZFwlWZL.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
From the left pane, select CorpNet.xyz and highlight Sales.
From the menu bar, select the Create a new organizational unit in the current container icon.

 <br/>
<img src="https://i.imgur.com/tGmjcOi.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Enter the name of the OU to be created. For this demo we will be nesting the following OU's within the Sales OU: SalesManagers & TempSales.

 <br/>
<img src="https://i.imgur.com/6PSXVB0.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
And that's it we are finished. This is what our result looks like:
 <br/>
<img src="https://i.imgur.com/on0ltiK.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Hope you enjoyed my demonstration. <br/>
<img src="https://i.imgur.com/fUrUQ2y.jpg" height="80%" width="80%" alt="Create OU's"/>
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
