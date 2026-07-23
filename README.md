# IT Homelab

A collection of hands-on labs where I build, configure, and secure real IT and cloud infrastructure from the ground up. Each lab is self-contained, documented step by step, and focused on identity and access management (how access is granted, governed, enforced, and monitored) alongside the systems administration, cloud, and security work that surrounds it..

## Labs

| Lab | Description |
|-----|-------------|
| [Active Directory](active-directory/) | Stand up a Windows Server 2025 domain controller on Azure, build a full Active Directory structure (OUs, security groups, users, Group Policy), and run day-one help desk tasks. |
| [Wireshark & Network Analysis](wireshark/) | Capture and analyze live network traffic — dissect a DNS lookup, watch the TCP three-way handshake, expose cleartext credentials over HTTP, and reassemble a full conversation with Follow TCP Stream. |
| [Splunk SIEM & Log Analysis](./splunk) | Forward Windows Active Directory security logs into Splunk, write SPL searches to detect brute force, account lockouts, and suspicious logins, and build a security dashboard and automated alert. |
| [ServiceNow ITSM](./servicenow) | Build core IT Service Management workflows on a free ServiceNow developer instance — create and resolve an incident, build a self-service catalogue item, route a change through a multi-tier approval chain, and build a report. Framed as the access-request-and-approval pattern at the heart of Identity and Access Management. |
| [Nessus Vulnerability Scanning](./nessus) | Deploy Nessus Essentials and scan a live Azure domain controller — interpret findings by severity and CVSS score, diagnose a failed credentialed scan from the tool's audit trail, and work the scan-find-prioritise-remediate-verify loop. |
## Background

I build these labs to develop and demonstrate practical, job-ready skills toward an identity and access management role. My background spans IT general controls (ITGC) auditing, enterprise access administration, and SQL-based reporting. I've tested access controls from the audit side, and these labs are where I build them from the engineering side.

*More labs added over time.*
