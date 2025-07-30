# 🚀 Wazuh SIEM Deployment (Ubuntu Server + Kali Agent)

This project demonstrates the deployment of a **Security Information and Event Management (SIEM)** solution using **Wazuh**.  
The setup uses **Ubuntu (Linux)** as the Wazuh server host and **Kali Linux** as the Wazuh agent to monitor and analyze security events.

---
## 🔹 Server Setup (Ubuntu – Wazuh Manager)

I deployed the Wazuh server on an Ubuntu VM and installed the Wazuh stack.

## ✅ Installation Steps:

 Download and run the Wazuh installation script

curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh && sudo bash ./wazuh-install.sh -a

## 🎥 Wazuh Installation Video
[![Watch the video](https://img.youtube.com/vi/M8YfFubt5jE/0.jpg)](https://youtu.be/M8YfFubt5jE)
<img width="960" height="540" alt="wazuh setup" src="https://github.com/user-attachments/assets/1579059c-75de-40d2-a2ea-3efac2bbcbc3" />
[![Watch the video](https://img.youtube.com/vi/KGr-SxNpS2M/0.jpg)](https://youtu.be/KGr-SxNpS2M)

## ✅ Key Configurations (Wazuh Server – Ubuntu)

- Verified system hardware requirements.
- Configured the web interface (port 443).
- Generated SSL certificates for secure communication.
- Installed Wazuh indexer and dashboard components.
---

## 🔹 Agent Setup (Kali Linux – Wazuh Agent)

The Kali Linux VM was configured as an endpoint agent to send logs and events to the Wazuh server.

[![Watch the video](https://img.youtube.com/vi/VoAweGVJ9Nk/0.jpg)](https://youtu.be/VoAweGVJ9Nk)

### ✅ Steps:
- Installed the Wazuh agent package.

<img width="960" height="540" alt="wazuh Agent on kali" src="https://github.com/user-attachments/assets/cdcc4761-4f83-45bc-a124-3aff5da5eedb" />

- Configured the agent to connect to the Wazuh manager’s IP.
- Verified registration and communication via the dashboard.

[![Watch the video](https://img.youtube.com/vi/QsujWtLnlJM/0.jpg)](https://youtu.be/QsujWtLnlJM)


<img width="960" height="540" alt="wazuh agent dashboard" src="https://github.com/user-attachments/assets/f189a50b-3aae-4c19-bd5f-f052a28e3d70" />

---

## 🔹 Dashboard & Monitoring

The **Wazuh Dashboard** provides a centralized view for log monitoring and threat detection.

### 🔍 Features:
- **Events Count Evolution:** Visualizes event trends in real-time.
- **MITRE ATT&CK Mapping:** Detects tactics like *Defense Evasion*.
- **Compliance Reports:** Includes PCI DSS, CIS Benchmarks, File Integrity Monitoring.
- **Vulnerability Detection:** Identifies vulnerable packages and misconfigurations.

### 🔹 The Agent Dashboard allows:
- Monitoring logs from the Kali endpoint.
- Performing Security Configuration Assessments (SCA).
- Tracking user activity, network events, and file integrity.
---

## 🔖 Tags:
`CyberSecurity` `SIEM` `Wazuh` `Linux` `Ubuntu` `Kali Linux` `Blue Team`  
`Threat Detection` `Incident Response` `SOC` `Open Source` `Vulnerability Management`  
`MITRE ATT&CK` `Homelab` `Security Tools`

---

## 📌 About This Project

This lab showcases a **fully functional SIEM environment** for detecting, analyzing, and responding to security events using open-source technology.  
Perfect for SOC monitoring, incident response, and compliance testing.
