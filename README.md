# 🛡️ SOC L1 Learning Journey
Welcome to my cybersecurity portfolio! Here, I document my daily learning, hands-on labs, and incident reports as I prepare for a SOC L1 role.
## 📂 Directory of Reports
### 1. Nmap Scan & Host Discovery
*   **Objective:** To identify live hosts and open ports on a local network.
*   **Tools Used:** Nmap, Kali Linux.
*   **What I did:** I used the command `sudo nmap -Pn -sV -F 192.168.7.193` to scan a mobile device on my local network.
*   **Observation:** The scan showed that all 100 scanned ports were in a **"filtered"** state. This means the target device's firewall is actively blocking incoming connections and dropping packets without responding.
*   **SOC Analyst Takeaway:** As a defender, seeing filtered ports is a good sign. It shows the firewall is doing its job. As an attacker, this means I need to find another way in, like exploiting a web application (Layer 7).
