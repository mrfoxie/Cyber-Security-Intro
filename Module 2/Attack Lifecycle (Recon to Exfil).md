---
tags:
  - Module_2_Sub
---
---

## ## 🔁 **Cyber Attack Lifecycle – From Recon to Exfiltration**

> Most cyberattacks follow a **step-by-step lifecycle**. Understanding each stage helps us **detect and defend** better.

## **1. Reconnaissance (Research & Targeting)**
> 🔍 _“Know before you go”_

- Attacker gathers info about the target (websites, emails, employees, software used)
- Passive: Google, LinkedIn, company websites
- Active: Scanning ports, phishing tests

➡️ **Goal:** Find weak points & entry paths

## **2. Weaponization**
> ⚙️ _“Build the attack tools”_

- Attacker creates or customizes malware/tools
- Combines exploit + delivery (e.g., phishing doc + macro code)
- Chooses tactic: Trojan, ransomware, exploit kit, etc.

➡️ **Goal:** Prepare for silent, undetected entry

## **3. Delivery**
> ✉️ _“Send the attack”_

- Delivers payload via:
    - Phishing emails
    - Malicious USBs
    - Fake websites / links
    - Compromised software updates

➡️ **Goal:** Get the target to trigger the infection

## **4. Exploitation**
> 💥 _“Break in”_

- The malware activates, exploiting system flaws or user mistakes
- Could exploit unpatched OS, apps, or user privileges 

➡️ **Goal:** Gain initial control over system

## **5. Installation**
> 📌 _“Establish a foothold”_

- Installs malware/backdoors
- Often includes persistence techniques (e.g., autostart, service disguise)

➡️ **Goal:** Stay hidden and maintain access

## **6. Command & Control (C2/C&C)**
> 📡 _“Phone home”_

- Infected system connects to attacker’s remote server
- Attacker can now issue commands, spread laterally, download more tools

➡️ **Goal:** Full remote control over target

## **7. Actions on Objectives (Exfiltration, Destruction)**
> 🎯 _“Mission complete”_

- Data theft (credentials, files, PII, IP)
- Deploy ransomware
- Sabotage or wipe data
- Move laterally to other systems

➡️ **Goal:** Complete attacker’s purpose — money, damage, espionage

---


---

## _Persistence & Evasion Throughout_
> Attackers often hide their tracks using encryption, stealthy malware, fileless attacks, and time-delays.

---


---

## **Defend at Every Stage**

|Stage|Defense Tactic|
|---|---|
|Recon|Limit public exposure (OPSEC)|
|Delivery|Email filters, awareness|
|Exploitation|Patch management|
|Install/C2|Endpoint protection, EDR|
|Exfiltration|DLP tools, network monitoring|

---


![[Cyber Attack Lifecycle.png]]