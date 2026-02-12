# 🛡️ Microsoft Sentinel: Real-Time Global Threat Map (Honeypot Project)

## 📝 Project Overview
This project showcases the deployment of a **cloud-native Honeypot** on Microsoft Azure to monitor and visualize real-time RDP brute-force attacks from around the globe. Leveraging **Microsoft Sentinel (SIEM)** and **Kusto Query Language (KQL)**, I transformed raw security logs into an interactive dashboard and configured automated threat detection.

## 🛠️ Key Technologies & Skills
* **Cloud Platform:** Microsoft Azure
* **SIEM Solution:** Microsoft Sentinel
* **Log Management:** Azure Log Analytics Workspace
* **Threat Detection:** KQL (Kusto Query Language) for data querying and analytics rules
* **Automation:** PowerShell scripting for IP geolocation data enrichment
* **Network Security:** Azure Network Security Groups (NSG) & Windows Firewall configuration

## 📊 Results & Insights
* Successfully captured and analyzed **over 11,000 failed RDP login attempts** within a few hours.
* Identified **Singapore (6.21K attacks)** and **Taiwan (4.83K attacks)** as the primary sources of brute-force activity.
* Detected a high volume of attempts targeting common usernames, including 'AmalLabs$'.
* Implemented a real-time analytics rule to automatically generate security incidents upon detecting brute-force patterns.

## 📸 Project Screenshots

### 1. Global Attack Map: Visualizing Brute-Force Attempts
![Global Attack Map](Azure-Sentinel/d2.png)


### 2. Top Attacking Countries

![Top Attacking Countries](Azure-Sentinel/d3.png)

### 3. Common Usernames Targeted by Hackers

![Common Usernames Targeted](Azure-Sentinel/d4.png)

### 4. Real-Time Brute-Force Detection Rule

![Brute Force Detection Rule](Azure-Sentinel/Rule.png)

## 🚀 Future Enhancements
* Integrate additional threat intelligence feeds.
* Develop automated response actions for detected threats.
* Expand honeypot to other services (e.g., web servers).

---
*This project demonstrates practical skills in **Cyber Security, Cloud Computing, SIEM operations, and Threat Hunting.** Feel free to connect and discuss!*


