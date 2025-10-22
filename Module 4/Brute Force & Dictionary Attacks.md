---
tags:
  - Module_4_Sub
---
---
## 🛠️ **What is a Brute Force Attack?**
> A brute force attack is a trial-and-error method used to decode encrypted data such as passwords or PINs by systematically trying every possible combination.

### 🔎 **How it Works:**
- The attacker writes or uses a program that keeps trying:
	- Single characters → a, b, c...
	- Combinations → aa, ab, ac...
	- Alphanumeric/symbols → A1!, A2!, A3!...
- The more complex the password (length + variety of characters), the longer it takes to crack.

### 💣 **Types of Brute Force Attacks:**

- **Simple Brute Force** – Tries every combination
- **Credential Stuffing** – Uses breached usernames/passwords on other sites
- **Reverse Brute Force** – Uses a known password against many usernames
- **Hybrid Attack** – Combines dictionary + brute force (e.g., `Password123!`)

---


---
## 📚 **What is a Dictionary Attack?**
> A dictionary attack uses a predefined list of likely passwords, often derived from leaked breaches or common patterns.

### 🔍 **Example Wordlists:**

- - **rockyou.txt** (most famous, 32 million real passwords)
- `top10000.txt` – Top 10k passwords used globally
- `SecLists` – GitHub repository with username/password lists, payloads

### 🔥 **Why It Works:**

- Users often use weak passwords:
    - `123456`
    - `admin`
    - `welcome@123`
- 60%+ of users reuse passwords across platforms

---


---
## 🏁 **Real-World Examples**

- **2012 LinkedIn Breach**
    - 117 million password hashes leaked
    - Most passwords: `123456`, `linkedin`, `password`
- **2019 Collection #1 Leak**
    - 773 million emails + passwords dumped
    - Used for large-scale credential stuffing
- **Wi-Fi Attacks (WPA2)**
    - Attacker captures a 4-way handshake
    - Runs dictionary attack to find PSK

---


---
## 🛡️ **How to Protect Against These Attacks**
### 🔐 Password Hygiene
- Use **12+ character** passwords with mix of:
	- 🔠 Uppercase
	- 🔡 Lowercase
	- 🔢 Number
	- 🔣 Special Characters

### 🛡️ Multi-Layered Defenses
|Protection|Description|
|---|---|
|**MFA/2FA**|Second factor like OTP, app code, biometric|
|**Rate Limiting**|Blocks or delays repeated login attempts|
|**Account Lockout**|Temporarily locks account after N failed logins|
|**CAPTCHAs**|Prevent automated brute force|
|**Hashing Algorithms**|Store passwords with strong hashes (bcrypt, Argon2)|

### Behavioral Monitoring
- Detects login anomalies (e.g., impossible travel, geo-velocity)
- Alerts for brute force signatures

---
