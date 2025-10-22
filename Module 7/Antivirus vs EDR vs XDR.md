---
tags:
  - Module_7_Sub
---
---
## **Antivirus (AV)**

- **Basic Protection**
	- Detects and removes known malware (viruses, trojans, worms).
	- Works on **signatures** (like a blacklist of bad files).  
	- Runs on individual devices (laptops, desktops).

> Example: Norton, McAfee, Windows Defender

---


---
## **EDR – Endpoint Detection & Response**

 - **Advanced Endpoint Security**
	 - Goes beyond antivirus.
	- Monitors **device behavior in real-time**.
	- Detects **new/unknown threats** (not just known viruses).
	- Provides **forensic data** (how attack happened, spread, impact).
	- Can isolate infected devices from the network.

> Example: CrowdStrike, SentinelOne

---


---
### **XDR – Extended Detection & Response**

- **Holistic Security**
	- Expands EDR beyond just devices.
	- Covers **endpoints, networks, cloud, email, servers**.
	- Correlates data from multiple sources → gives **big picture of attack**.
	- Uses **AI/automation** for faster response.
	- Helps security teams detect **complex, multi-stage attacks**.

> Example: Palo Alto Cortex XDR, Microsoft Defender XDR

---


---
## **Quick Comparison Table**

| Feature                 | Antivirus (AV) | EDR | XDR |
| ----------------------- | -------------- | --- | --- |
| Detects Known Malware   | ✅              | ✅   | ✅   |
| Detects Unknown Threats | ❌              | ✅   | ✅   |
| Behavioral Monitoring   | ❌              | ✅   | ✅   |
| Device Isolation        | ❌              | ✅   | ✅   |
| Covers Beyond Endpoint  | ❌              | ❌   | ✅   |
| Centralized Threat View | ❌              | ❌   | ✅   |

> Key Takeaway
> **AV = First layer (basic protection)**
> **EDR = Smarter, deeper defense for endpoints**
    **XDR = Unified, all-in-one security view across your whole organization**
---