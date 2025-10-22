---
tags:
  - Module_2_Sub
---
 ---

## 👥🔗 **Man-in-the-Middle (MITM) Attack**

```text
[ YOU ] 🔁 📶 → 👤 (HACKER) ← 📶 🔁 [ WEBSITE / SERVER ]
```

1. You think you're securely connected to a trusted website
2. The attacker secretly **intercepts** the connection
3. They **can read, steal, or modify data** being transmitted
4. **You never know your data was intercepted**

---


---

## **Real-World Examples:**

- **Public Wi-Fi Snooping**:
	- On an open Wi-Fi (airport, café), attacker can monitor your web activity and steal logins
- **Fake Wi-Fi Hotspot**:
	- Hacker sets up “Free_WiFi” that looks legit, but routes your data through their system
- **HTTPS Stripping**:
	- MITM tool forces your browser to use an unsecure HTTP connection instead of HTTPS
- **Session Hijacking**:
	- Hacker steals a user's session cookie to impersonate them on a site

---


---

## 🛡️ **How to Protect Yourself:**

- [ ] Avoid using public Wi-Fi for sensitive logins
- [ ] Always check for **HTTPS** (padlock symbol) in browser
- [ ] Use a **VPN** when on public or untrusted networks
- [ ] Don’t click on certificate warnings or bypass security prompts
- [ ] Enable **2FA** – even if credentials are stolen, the account remains safe

---


> 💡 _If a hacker gets between you and your destination, they can see or change everything._


![[Man in the Middle.png]]