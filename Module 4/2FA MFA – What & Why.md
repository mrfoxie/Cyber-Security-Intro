---
tags:
  - Module_4_Sub
---
---
## **What is 2FA / MFA?**
- **2FA = Two-Factor Authentication**
- **MFA = Multi-Factor Authentication**
- It adds an **extra layer of security** beyond just a username and password.
- - Instead of relying on just _something you know_ (password), they combine two or more of the following:

### 🔑 The Three Factors:

1. **Something You Know** – Password, PIN    
2. **Something You Have** – Phone, security key, authenticator app
3. **Something You Are** – Fingerprint, face scan, retina

---


---
## 🛡️ **Why Use 2FA / MFA?**

- Passwords **alone are not enough** — they can be stolen, guessed, or cracked.    
- 2FA/MFA helps **block 99.9% of account compromise attacks** (source: Microsoft).
- Even if your password is stolen (via phishing or data breach), the attacker **can’t access your account** without the second factor.

---

## 💡 **Real-World Example**

- Login attempt from a new device? You'll get a prompt on your phone or email asking to verify. Without it, the login fails — even with the right password.

---


---
## 🔐 **Common 2FA Methods**
| Method            | Description                                               | Security Level |
| ----------------- | --------------------------------------------------------- | -------------- |
| SMS Code          | A code sent to your phone via text                        | 🟡 Medium      |
| Authenticator App | Code from Google Authenticator, Authy etc.                | 🟢 Strong      |
| Push Notification | Tap to approve login (e.g., Duo, Microsoft Authenticator) | 🟢 Strong      |
| Hardware Key      | Physical USB key like YubiKey                             | 🟢 Very Strong |

---


---
## ### Practice Tip:

Avoid **SMS-based 2FA** where possible — it’s better than nothing, but vulnerable to SIM swapping.

---

