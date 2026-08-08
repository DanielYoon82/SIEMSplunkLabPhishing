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

<h2>Step 2 – Investigate Alert Data in Splunk</h2>
Splunk was used to investigate the event and correlate information associated with the reported phishing attempt.

<h3>Actions Performed</h3>

- Searched relevant event data in Splunk
- Compared event timestamps with the reported email
- Reviewed sender information
- Reviewed recipient information
- Correlated the available event information with the original alert
<br />
The Splunk investigation produced data consistent with the timestamp and sender information associated with the reported email.

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Step 3 – Validate Sender and Recipient Information</h2>

<h3>Actions Performed</h3>

- Reviewed the targeted recipient information
- Compared sender information with the reported email
- Verified the company and recipient details associated with the event
- Correlated the information with the original security alert

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Step 4 – Investigate the Suspicious URL</h2>
The URL contained within the email was investigated to determine whether it represented a known malicious destination.

<h3>Actions Performed</h3>

- Extracted the URL associated with the email
- Investigated the URL using the available security analysis tool
- Reviewed the resulting reputation information
- Determined that the URL was identified as clean/non-malicious within the lab environment
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Step 5 – Determine Incident Classification and Documentation</h2>
After reviewing the available evidence, the investigation did not identify sufficient indicators of a malicious phishing attempt. The investigation findings were documented to maintain an accurate record of the alert, evidence reviewed, actions performed, and final determination.

<h3>Finding</h3>

**Classification: False Positive**<br />

The alert was determined to be a false positive based on the available evidence reviewed during the investigation.

<h3>Evidence Reviewed</h3>

- Alert severity
- Email timestamp
- Sender information
- Recipient information
- Splunk event data
- URL reputation results
- Company and email information

<h3>Documentation Included</h3>

- Initial alert details
- Investigation steps
- Splunk findings
- Email and recipient information
- URL investigation results
- Final classification
- Investigation conclusion

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/SIEMSplunkLabs/blob/main/image/SplunkSiem7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Key Takeaways</h2>
This lab demonstrates a structured approach to security alert investigation using Splunk. The investigation involved reviewing a suspected phishing alert, correlating event information, validating email details, investigating a URL, and documenting the final determination.<br />
<br />
The project demonstrates foundational SOC and security analyst skills, including SIEM investigation, alert triage, log analysis, evidence correlation, false positive identification, and incident documentation.

