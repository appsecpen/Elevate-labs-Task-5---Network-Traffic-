# Task 5: Network Traffic Capture and Analysis using Wireshark
## 🎯 Objective
To capture live network traffic using Wireshark, identify common network protocols, and analyze the captured packets.
## 🛠️ Tools Used
- **Wireshark** (Windows version)
- **Command Prompt / Web Browser**
## 🔍 Task Steps
1. Installed Wireshark on Windows.
2. Selected the active network interface (Wi-Fi).
3. Started capturing live packets.
4. Generated traffic by:
   - Visiting websites: `https://google.com`
   - Running `ping google.com` in Command Prompt.
5. Stopped the capture after 2 minutes.
6. Applied filters for protocols: `dns`, `http`, `icmp`, `tcp`.
7. Identified at least 3 different protocols.
8. Saved the capture file as `traffic.pcap`.(https://shorturl.at/8asCk)
9. Created a summary report (`traffic.txt`).
---
## 📦 Files Included

| File Name            | Description                                 |
|----------------------|---------------------------------------------|
| `traffic.pcap` | Raw packet capture of live network traffic. |
| `traffic.txt`   | Summary report of protocols and findings.   |

---
## 📊 Protocols Identified
- **DNS** – Domain name resolution
- **HTTP** – Web traffic (unencrypted)
- **ICMP** – Ping requests and replies
- **TCP** – Transport control packets for HTTP
---
## ✅ Outcome
This task demonstrates basic traffic monitoring skills using Wireshark and the ability to analyze and filter protocol-specific packets from a live capture session.
---


