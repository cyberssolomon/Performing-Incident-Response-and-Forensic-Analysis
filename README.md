<h1>Performing Incident Response and Forensic Analysis</h1>

<h2>Tools and Software Used</h2>

- <b>NetWitness Investigator</b> 
- <b>Autopsy</b>


 

<h2>Environments Used </h2>

- <b>vWorkstation (Windows: Server 2019)</b> 




 
<h2>Description</h2>
Project consists of imitating the Analysis step of the incident response process: using NetWitness Investigator to analyze a PCAP file taken during a recent incident, using Autopsy to identify forensic evidence related to the incident, preparing an incident response report.
<br />

### Section 1

<h2>Analyze a PCAP File for Forensic Evidence:</h2>








<p align="center">
Show the Time Graph: <br/>
<img src="https://i.imgur.com/85l3YQy.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the details of the 2021-Jul-13 15:33:00 session:  <br/>
<img src="https://i.imgur.com/Kfe3eMK.png" height="80%" width="80%" alt="Section 1 Steps"/>

 <h2>Analyze a Disk Image for Forensic Evidence:</h2>







<p align="center">
Show the email message containing FTP credentials and the associated timestamps: <br/>
<img src="https://i.imgur.com/XJyPQNL.png" height="80%" width="80%" alt="Section 2 Steps"/>


 <h2>Prepare an Incident Response Report:</h2>







<p align="center">
Date, Name, Incident Priority: <br/>
<img src="https://i.imgur.com/r8SV0Vg.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Incident Type, Incident Timeline, Incident Scope:  <br/>
<img src="https://i.imgur.com/7LkQCrT.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Systems Affected by the Incident, Users Affected by the Incident:  <br/>
<img src="https://i.imgur.com/xLajRd0.png" height="80%" width="80%" alt="Section 1 Steps"/>













 ### Section 2

<h2>Identify Additional Email Evidence:</h2>










<p align="center">
Show the email from Dr.Evil demanding that Marvin install a keylogger: <br/>
<img src="https://i.imgur.com/XjoJeh1.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the email from Dr.Evil reminding Marvin to update the firewall and scheduler:  <br/>
<img src="https://i.imgur.com/tkKk1mu.png" height="80%" width="80%" alt="Section 2 Steps"/>



 <h2>Identify Evidence of Spyware:</h2>










<p align="center">
Show the three events that are related to the Actual Keylogger file in the /Windows/System32/Tasks folder with a June 30 timestamp: <br/>
<img src="https://i.imgur.com/4dxDIyF.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the one event that is related to the Actual Keylogger file in the /Windows/System32/Tasks folder with a July 1 timestamp: <br/>
<img src="https://i.imgur.com/rtZlzwj.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Record the date and time when the keylogger's executable file was last started: <br/>
<img src="https://i.imgur.com/MDPIak6.png" height="80%" width="80%" alt="Section 2 Steps"/>


<h2>Update an Incident Response Report:</h2>










<p align="center">
Date, Name, Incident Priority: <br/>
<img src="https://i.imgur.com/BHyF3Ko.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Incident Type, Incident Timeline, Incident Scope: <br/>
<img src="https://i.imgur.com/ajIOFwR.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Systems Affected by the Incident, Users Affected by the Incident: <br/>
<img src="https://i.imgur.com/AqLFK21.png" height="80%" width="80%" alt="Section 2 Steps"/>












 













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
