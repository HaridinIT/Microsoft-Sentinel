<h1>Microsoft Sentinel</h1>

<h2>Description</h2>
In this project, an Azure SQL Database was deployed and secured with Microsoft Defender for SQL for threat protection and vulnerability assessment. Sensitive data was identified and classified to meet compliance standards, while auditing was configured to track database activities. This project demonstrated robust approach to protecting Azure SQL Databases through monitoring, compliance, and security tools. 
<br />
<p align="center">
<img src="https://imgur.com/luAcaxB.png" height="85%" width="85%" alt="Microsoft Sentinel"/>
</p

<h2>Languages and Environments Used (PaaS Components) </h2>


- <b>Azure</b>
- <b>Azure Virtual Network</b>
- <b>Azure VM</b>
- <b>Log Analytics Workspace</b>
- <b>Microsoft Sentinel</b>
- <b>Azure Defender for Cloud</b> 


<h2>Project walk-through:</h2>

<p align="center">
Onboard Microsoft Sentinel and add Log Analytics Workspace: <br/>
<img src="https://imgur.com/hTEgpQC.png" height="80%" width="80%" alt="Onboard Microsoft Sentinel and add Log Analytics Workspace"/>
<img src="https://imgur.com/u3OciNw.png" height="80%" width="80%" alt="Deploy SQL Database"/>

Configure Microsoft Sentinel to use Azure Activity Data Connector: <br/>
<img src="https://imgur.com/RqAt1Oa.png" height="80%" width="80%" alt="Configure Microsoft Sentinel to use Azure Activity Data Connector"/>
<br />
<br />
Create a rule that uses the Azure Activity Data Connector: <br/>
<img src="https://imgur.com/ZU1Ao6m.png" height="80%" width="80%" alt="Create a rule that uses the Azure Activity Data Connector"/>
<img src="https://imgur.com/01vjBS1.png" height="80%" width="80%" alt="Create a rule that uses the Azure Activity Data Connector"/>
<img src="https://imgur.com/MpGIyPd.png" height="80%" width="80%" alt="Finish creating rule"/>
<br />
<br />

Create a Playbook: <br/>

<p align="center">
.json file was downloaded and loaded from \Allfiles\Labs\15\changeincidentseverity.json

<img src="https://imgur.com/HytZDBP.png" height="80%" width="80%" alt="Custom Deployment for the Playbook"/>
<img src="https://imgur.com/Qmsy4CQ.png" height="80%" width="80%" alt="Custom Deployment for the Playbook"/>  
<img src="https://imgur.com/ob98Vp6.png" height="80%" width="80%" alt="Custom Deployment for the Playbook Complete"/>  
<br />
<br />
Create Storage Account: <br/>
<img src="https://imgur.com/j5yq41q.png" height="80%" width="80%" alt="Creating Storage Account"/>
<br />
<br />
Configure Auditing: <br/>
<img src="https://imgur.com/5JYoZ6M.png" height="80%" width="80%" alt="Configuring Auditing"/>
<img src="https://imgur.com/APCd2zt.png" height="80%" width="80%" alt="Configuring Auditing"/>
<br />
<br />
View Audit Logs: <br/>
<img src="https://imgur.com/CjGK0xe.png" height="80%" width="80%" alt="Audit Logs"/>
<br />
<br />
<h2>Conclusion:</h2>
The project provided a comprehensive approach to securing an Azure SQL Database by leveraging key security features such as Microsoft Defender for SQL, data classification, and auditing. The project demonstrated effective strategies for protecting sensitive data, ensuring regulatory compliance, and monitoring database activities. 
