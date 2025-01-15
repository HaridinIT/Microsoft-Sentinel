<h1>Microsoft Sentinel</h1>

<h2>Description</h2>
This project focused on implementing and configuring Microsoft Sentinel, a cloud-native Security Information and Event Management (SIEM) and Security Orchestration, Automation, and Response (SOAR) platform. Using a lab environment, I connected Microsoft Sentinel to various data sources, including Azure Active Directory, Office 365, and custom log sources, to aggregate and analyze security events. I created custom analytic rules, incident alerts, and playbooks to detect and respond to threats in real time. Additionally, I configured workbooks and dashboards to provide comprehensive visualization of security metrics and system performance, enabling actionable insights for proactive threat management.
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
  
<br />
<br />

<p align="center">
Configure Microsoft Sentinel to use Azure Activity Data Connector: <br/>
<img src="https://imgur.com/RqAt1Oa.png" height="80%" width="80%" alt="Configure Microsoft Sentinel to use Azure Activity Data Connector"/>

<br />
<br />

<p align="center">
Create a rule that uses the Azure Activity Data Connector: <br/>
<img src="https://imgur.com/ZU1Ao6m.png" height="80%" width="80%" alt="Create a rule that uses the Azure Activity Data Connector"/>
<img src="https://imgur.com/01vjBS1.png" height="80%" width="80%" alt="Create a rule that uses the Azure Activity Data Connector"/>
<img src="https://imgur.com/MpGIyPd.png" height="80%" width="80%" alt="Finish creating rule"/>

<br />
<br />

<p align="center">
Create a Playbook: <br/>
.json file was downloaded and loaded from \Allfiles\Labs\15\changeincidentseverity.json

<img src="https://imgur.com/HytZDBP.png" height="80%" width="80%" alt="Custom Deployment for the Playbook"/>
<img src="https://imgur.com/Qmsy4CQ.png" height="80%" width="80%" alt="Custom Deployment for the Playbook"/>  
<img src="https://imgur.com/ob98Vp6.png" height="80%" width="80%" alt="Custom Deployment for the Playbook Complete"/>  
<img src="https://imgur.com/yqjLGlc.png" height="80%" width="80%" alt="Configuring Logic Apps Designer"/>
<br />
<br />

<p align="center">
Create custom alert and configure playbook: <br/>
<img src="https://imgur.com/pX67NaQ.png" height="80%" width="80%" alt="Create Scheduled Query Rule"/>
<img src="https://imgur.com/JqrFzi8.png" height="80%" width="80%" alt="Create Scheduled Query Rule"/>
<img src="https://imgur.com/u2EI1cj.png" height="80%" width="80%" alt="Create Scheduled Query Rule"/>
<br />
<br />

<p align="center">
Create New Automation Rule: <br/>
<img src="https://imgur.com/JTasMMh.png" height="80%" width="80%" alt="Create New Automation Rule"/>
<img src="https://imgur.com/2eflGUJ.png" height="80%" width="80%" alt="Scheduled Query Rule"/>
<img src="https://imgur.com/32rSZZT.png" height="80%" width="80%" alt="Analytics Rule Saved"/>
<br />
<br />
  
<h2>Verification</h2>

<p align="center">
Invoke an Incident and review actions: <br/>
<img src="https://imgur.com/JrQJp0P.png" height="80%" width="80%" alt="Invoke an Incident to view associated actions"/>


<h2>Conclusion:</h2>
This Microsoft Sentinel project demonstrates my ability to deploy and optimize a powerful SIEM/SOAR platform for advanced threat detection and response. By integrating diverse data sources, configuring automated playbooks, and developing custom dashboards, I reinforced my hands-on experience in enhancing an organization's security posture through real-time monitoring and automated incident response. This project reflects my expertise in leveraging Microsoft Sentinel to streamline security operations and enable robust, data-driven decision-making in dynamic environments.
