---
tags:
  - Module_5_Sub
---
---
## What Are USB Attacks?
|Type|Description|
|---|---|
|**Rubber Ducky**|A USB device that acts like a **keyboard**, rapidly typing malicious commands when plugged in|
|**BadUSB**|A USB drive with **reprogrammed firmware** to emulate trusted devices (keyboard, network adapter, etc.) and execute harmful actions|

---


---
## Real-World Dangers
- 🖥️ **Auto-Execution of Malware**: Installs keyloggers, ransomware, or backdoors in seconds
- 🔑 **Credential Theft**: Steals saved passwords and browser data
- 🔗 **Lateral Movement**: Spreads malware to internal networks from one infected device
- 💥 **Disruption**: Could wipe data, encrypt files, or open security holes for later attacks

---


---
## Don’t Trust That USB!

**Do Not:**
- Pick up and use **“found” USBs**
- Use **free giveaways** from unknown sources
- Plug in unverified devices into workstations
**Do:**
- Use **approved, encrypted USBs**
- Disable **auto-run** features    
- Report **suspicious USBs** to IT immediately

---


---
## Organization Defenses

- ✋ Disable USB ports on critical systems
- 🔐 Implement **endpoint protection**
- 🕵️ Monitor for unauthorized **HID (keyboard/mouse) devices**
- ✅ Use **read-only** media for sensitive environments

---


---
## Note

> “A USB can pretend to be a keyboard, type 1000 words per minute, and own your computer — before your coffee finishes pouring.”