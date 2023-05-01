<p align="center">
 <img src="https://i.imgur.com/laVKUOH.jpg" alt="Raid Array logo"/>
</p>

<h1>Creating Organizational Units</h1>


<h2>Description</h2>

Organizational Units (OUs) are the backbone of efficient network infrastructure management! With OUs, you can effortlessly organize and control crucial domain objects, such as users, groups, and computers. By creating OUs, you gain the power to delegate administrative control over specific sets of objects, making network management a breeze.

And today, we're taking things up a notch! In our demonstration, we'll be adding not just one, but several OUs to our domain. But that's not all. We'll also be diving deep into the world of OU nesting, as we show you how to group multiple OUs within a single one for optimal organization. Trust me, it's going to revolutionize the way you manage your network infrastructure.

Get ready to unlock the full potential of your domain with the incredible organizational capabilities of OUs. It's simple, it's efficient, and it's essential for any network administrator.

<br />

<h2>Environments Used </h2>

 <b>Microsoft Server 2016</b> 

<h2>Program walk-through:</h2>

<p align="center">
Right-click Start and select Disk Management.
Select GPT as the partition style.
Select OK to initialize all disks.
<br/>
<img src="https://i.imgur.com/OcMGkdW.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Right-click Disk 1 and select New Striped Volume.
Select Next.
 <br/>
<img src="https://i.imgur.com/2eQuXo3.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Under Available, select Disk 2 then select Add. Select Next.
 <br/>
<img src="https://i.imgur.com/QTzQw3i.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Use the Assign the following drive letter drop-down list to select E.
Select Next.
Make sure NTFS is selected as the file system.
Use Editing as the Volume label.
Select Next.
Select Finish.
 <br/>
<img src="https://i.imgur.com/bSLAXfj.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Select Yes to convert the disks to dynamic disks. <br/>
<img src="https://i.imgur.com/WXsNO5v.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Right-click Disk 3 and select New Mirrored Volume.
Select Next.
 <br/>
<img src="https://i.imgur.com/K9IIE18.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Under Available, select Disk 4. Select Add. Then select next
 <br/>
<img src="https://i.imgur.com/ZIzjMdW.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Use the Assign the following drive letter drop-down list to select M.
Select Next.
Make sure NTFS is selected as the file system.
Use Media as the Volume label; then select Next.
Select Finish.
 <br/>
<img src="https://i.imgur.com/oOWAQXr.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
Select Yes to convert the disks to dynamic disks. Your final result should look like this <br/>
<img src="https://i.imgur.com/MsVOmTw.png" height="80%" width="80%" alt="Create Raid Array"/>
<br />
<br />
That's it! <br/>
<img src="https://i.imgur.com/uhKlKpv.jpg"  alt="Create Raid Array"/>
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
