# RISKS & VULNERABILITIES

## Executive Summary

This project focuses on developing a sensor-based monitoring strategy to detect threats and support operational awareness across key systems in a simulated enterprise environment. Using Paessler PRTG, I identified and prioritized sensors for systems such as a SQL database, Linux development server, and IIS web server. Each sensor was evaluated based on its connection to known indicators of compromise (IoCs), expected behavior, and system criticality.

The project includes a structured analysis of each sensor's role, alert thresholds, and justification based on potential risks. 

Additional recommendations were made to improve monitoring coverage, including the use of a web application firewall, privilege escalation detection, and multi-factor authentication. 

## Objective

The goal of this project was to evaluate available monitoring sensors and recommend those best suited for detecting known threats, vulnerabilities, and abnormal system behavior across core business systems. The selected sensors were mapped to relevant IoCs and prioritized based on system importance and risk exposure. Alert thresholds were also defined to support timely incident response without generating unnecessary noise.

### Skills Learned

- Evaluated and prioritized monitoring sensors based on risk relevance and asset criticality.
- Mapped Indicators of Compromise (IoCs) to specific system behaviors and monitoring points.
- Captured and interpreted network traffic to understand communication patterns, detect anomalies, and trace service activity using Wireshark.
- Applied knowledge of IPv4 architecture and subnetting to propose efficient and secure network segmentation.

### Virtual Machine Setup
- Windows Server
- Linux Server
- Kali Server (Primary platform used for this analysis)
  
### Tools Used

- Nmap: For active scanning and device enumeration
- Wireshark: For passive packet capture and protocol analysis
- VirtualBox: For lab environment deployment and simulation scenarios.


## Steps
