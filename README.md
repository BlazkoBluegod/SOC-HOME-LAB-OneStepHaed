# SOC-HOME-LAB-OneStepHaed
Documentation about the configuration and log analysis of my Personal Soc Lab :D
# SOC & Network Security Home Lab

This repository documents the design, configuration, and log analysis of my personal cybersecurity laboratory, aimed at simulating real-world attack and defense scenarios (Blue Teaming).

## 🗺️ Network Architecture (Under Development)
The laboratory is structured to isolate traffic and simulate an enterprise environment using VLANs managed by **pfSense**:

*   **Attacking Zone **: Kali Linux / Parrot OS (Vulnerability analysis and threat simulation).
*   **Victim Zone**: Monitored endpoints (Windows Server Active Directory / Linux) for system log generation.
*   **SIEM & Management Zone**: **Splunk (Free License)** dedicated to centralizing, indexing, and analyzing security logs.

## 🚀 Project Objectives (2026-2028)
1. Configure routing and firewall rules on pfSense to isolate network segments via VLANs.
2. Set up log ingestion from pfSense and endpoints into Splunk.
3. Simulate known attacks (e.g., Brute Force, Port Scanning,Golden ticket,kerberoasting,malicious command executition, C2 and persistens in linux/windows) and create dedicated Splunk queries (SPL) for threat detection, also using powershell and common security events correlated, also want to learn Regex.
4. Build automated incident response workflows to simulate modern SOC operations.
5. If all this plan goes well, we will update this into a SOAR system and also adding some agents to it ;), wish me good luck and let's have fun and progress togheter! Open to all kind of comment or discussion to make this project better every day!

see ya
