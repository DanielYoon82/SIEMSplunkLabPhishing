<h1>Home Lab - Splunk SIEM | Phishing Alert Investigation</h1>

<h3>Project Overview</h3>
This home lab demonstrates the use of Splunk as a Security Information and Event Management (SIEM) platform to investigate and triage a suspected phishing alert.<br />
<br />
Using a simulated security incident from a TryHackMe lab environment, I analyzed alert information, correlated email and event data in Splunk, reviewed sender and recipient details, investigated a suspicious URL, and documented the final determination as a false positive.<br />
<br />
The lab demonstrates a structured approach to security alert triage, investigation, evidence analysis, and incident documentation.
</p>
<br />

<h3>Architecture & Investigation Workflow</h3>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabPhishing/blob/main/image/SplunkSiemDiagram.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br /> 


<h3>Objectives</h3>

- Practice security alert triage using Splunk
- Investigate a suspected phishing attempt
- Correlate information from multiple sources
- Analyze timestamps, sender, recipient, and URL information
- Determine whether an alert represents a legitimate threat or false positive
- Document investigation findings and conclusions

<h3>Environment </h3>
- Splunk
- TryHackMe Lab Environment
- Simulated phishing alert
- Email and security event data

<h3>Skills Demonstrated </h3>
- SIEM Investigation
- Security Alert Triage
- Phishing Investigation
- Event Correlation
- Log Analysis
- Evidence-Based Investigation
- False Positive Identification
- Incident Documentation
- Security Operations Workflow


<h2>Security Incident Scenario</h2>

<h3>Alert </h3>

A security alert is assigned for investigation after an email is identified as a potential phishing attempt.<br />
<br />
The alert is categorized as Medium severity, requiring investigation to determine whether the email represents a legitimate security threat or a false positive.

<h2>Step 1 – Alert Assignment and Initial Triage</h2>
The alert is assigned for investigation and reviewed to determine the severity, alert type, and available evidence.

<h3>Actions Performed</h3>

- Reviewed the assigned security alert
- Identified the alert as a potential phishing attempt
- Confirmed the alert severity as Medium
- Reviewed the available incident information
- Began the investigation using Splunk

<h3>Investigation Focus</h3>
- Alert timestamp
- Sender information
- Recipient information
- Email details
- Suspicious URL
- Related security events

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem1.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem2.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Splunk investigation data matches timestamp and sender information. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Company information confirms recipient and email that was targeted. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

URL in the email confirms in the tool that it is clean and not malicious. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Email confirmed as a false positive noted with detailed documentation.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

