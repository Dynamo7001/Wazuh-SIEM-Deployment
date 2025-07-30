# 🚀 Wazuh SIEM Deployment (Ubuntu Server + Kali Agent)

This project demonstrates the deployment of a **Security Information and Event Management (SIEM)** solution using **Wazuh**.  
The setup uses **Ubuntu (Linux)** as the Wazuh server host and **Kali Linux** as the Wazuh agent to monitor and analyze security events.

---

## 🔹 Server Setup (Ubuntu – Wazuh Manager)

I deployed the Wazuh server on an Ubuntu VM and installed the Wazuh stack.

### ✅ Installation Steps:
```bash
# Download and run the Wazuh installation script
curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
