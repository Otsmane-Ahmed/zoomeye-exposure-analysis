# Exposed Critical Systems: A Cybersecurity Risk Analysis Using ZoomEye

## Abstract
This research explores the risks associated with publicly exposed critical systems by leveraging ZoomEye's cyberspace search capabilities. By identifying vulnerable SCADA/ICS devices, IoT systems, and end-of-life software running on internet-facing infrastructure, we highlight the potential threats these misconfigurations pose. This study aims to raise awareness among organizations and security professionals about the dangers of unprotected systems.

## 1. Introduction
With the increasing interconnectivity of critical infrastructure, many organizations unintentionally expose high-risk systems to the internet. Attackers actively scan for such systems using platforms like ZoomEye. This research uses ZoomEye's search capabilities to identify vulnerable devices and analyze the security risks they pose.

## 2. Research Methodology
To conduct this study, we used specific ZoomEye queries targeting SCADA/ICS, IoT, and outdated software versions that are known to have security vulnerabilities. The methodology involves:

- Constructing targeted search queries for known vulnerable devices.
- Analyzing search results to determine exposure levels.
- Identifying trends in geographical distribution and ISP ownership.

## 3. ZoomEye Search Queries & Data Collection
The following queries were used to identify potentially vulnerable devices:

- **SCADA/ICS Devices:** `app:"Siemens SIMATIC" OR app:"Schneider Electric"`
- **IoT Devices:** `device:"D-Link" OR device:"Hikvision"`
- **End-of-Life Software:** `app:"Microsoft Exchange 2013"` (no longer supported but still widely used)

Using these queries, thousands of exposed systems were identified. Many of these devices were found to be running outdated firmware or lacking proper authentication mechanisms.

## 4. Data Analysis & Findings

### SCADA/ICS Exposure
- Over **3,000** exposed industrial control systems were found, with the highest concentration in the United States and Germany.

### IoT Risks
- Thousands of IoT devices, including security cameras and routers, were identified, many of which were using default passwords.

### Outdated Software
- Hundreds of Microsoft Exchange servers running unsupported versions were discovered, making them prime targets for exploitation.

## 5. Ethical Considerations
This research strictly follows ethical guidelines. No unauthorized access or exploitation was performed. All data is publicly available via ZoomEye’s search index. The purpose of this study is to highlight security risks and encourage organizations to secure their exposed systems.

## 6. Conclusion & Recommendations
Organizations must take proactive steps to secure internet-facing infrastructure. Recommendations include:

- Regular security audits to detect exposed systems.
- Applying security patches to outdated software.
- Implementing firewall rules to limit access to critical services.
- Disabling default credentials on IoT devices.

This research demonstrates the importance of proactive cybersecurity measures and how platforms like ZoomEye can be leveraged to improve security awareness.

## 7. References

- **ZoomEye Official Documentation:** [https://www.zoomeye.ai/doc](https://www.zoomeye.ai/doc)
- **CVE Database:** [https://cve.mitre.org/](https://cve.mitre.org/)
- **SCADA Security Guidelines:** [https://www.cisa.gov/scada-security](https://www.cisa.gov/scada-security)

This research aims to contribute to cybersecurity awareness and responsible disclosure efforts by providing a deeper analysis of exposed critical systems using ZoomEye.
