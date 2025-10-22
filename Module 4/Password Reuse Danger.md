---
tags:
  - Module_4_Sub
---
---
## ⚠️ **What is Password Reuse?**

> **Password reuse** is when a user uses the same password (or a slight variation) across multiple accounts and services.

---


---
## 💥 **Why It's Dangerous**

If **one** account gets compromised (e.g., in a data breach), attackers can:
If **one** account gets compromised (e.g., in a data breach), attackers can:

- **Try the same password** on other platforms (called **Credential Stuffing**).
- Gain access to:
    
    - 🔐 Email
    - 💰 Bank Accounts
    - 🛒 Shopping Portals
    - 💼 Work Applications     
    - 📷 Social Media

> 🔓 _“One breached account = all your accounts could be at risk”_

---


---
## **Real-World Breach Example**
| Breach               | Accounts Exposed | Reused Password Impact                                |
| -------------------- | ---------------- | ----------------------------------------------------- |
| LinkedIn (2012)      | 117 million      | Same password used on Gmail & PayPal                  |
| Adobe (2013)         | 150 million      | Password reuse led to multiple compromised accounts   |
| Collection #1 (2019) | 773 million      | Compilation of reused passwords from various breaches |

---


---
## **Credential Stuffing Demo (Concept)**

- Attacker gets:
    - Email + Password from breached website
- Runs a **script/tool** to try that login on:
    - Gmail, Facebook, Instagram, PayPal, Amazon
- If reused password works → Account compromised!

---


---
## 🔐 **How to Prevent Password Reuse**

- **Use a unique password** for every site
- **Enable 2FA** wherever possible
- Use a **password manager**:
	- Bitwarden (Free/Open Source)
	- 1Password
	- KeePassXC
	- LastPass (use cautiously after its breach history)

🚫 Avoid:
- `pass@123` reused as `pass@1234`
- Modifying the same base password like: `MyPasswordGmail`, `MyPasswordAmazon`

---


---
## 📉 **Password Reuse Statistics**

- 🔁 Over **65%** of people reuse passwords across multiple sites
- 🧠 Only **12%** of users use password managers
- 🔓 Most reused passwords are from the **top 1000 most common** list

---


---
## 👥 **How Attackers Exploit Reuse**

- **Credential Stuffing**: Automated login attempts on thousands of sites
- **Business Email Compromise (BEC)**: Access work email → spear phishing/internal fraud
- **Account Takeover (ATO)**: Hijack accounts and change recovery options
- **Lateral Movement** in organizations: One reused password → entire network breach

---


---
## 🛡️ **Final Advice for Users**

> 🔑 _“Treat your passwords like your toothbrush: never share them and change them regularly.”_
> 🧩 Passwords should be **complex**, **unique**, and **stored securely** (never in plain text or browser memory).

---