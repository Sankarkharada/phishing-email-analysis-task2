# 📄 Phishing Email Analysis Report

## 🔍 Email Overview

This email claims to be from "ABC Bank" and warns the recipient about unauthorized login attempts. It pressures the user to click a link to verify their account within 24 hours, or risk permanent suspension.

---

## 🚩 Phishing Indicators Identified

### 1. 🧑‍💻 Spoofed Sender Address
- **Display Name:** ABC Bank
- **Email Address:** abc.bank.verify@gmail.com
- **Issue:** Reputable banks use their official domains (like `@abcbank.com`) — this Gmail address is suspicious.

---

### 2. 🧾 Header Discrepancies (via MxToolbox)
Sample headers:
- **IP Address** is geolocated to Nigeria, not related to ABC Bank.
- **SPF & DKIM failed**, which means this email likely wasn’t authorized by Gmail.

---

### 3. 🔗 Suspicious Link
- **Displayed Link:** http://abc-bank-security-update.weebly.com
- **Issue:** Legitimate banks do not host services on free platforms like Weebly.

---

### 4. ⚠️ Urgent/Threatening Language
- "Your account will be permanently suspended in 24 hours."
- Classic **social engineering tactic** to create panic and make the user act quickly.

---

### 5. 🧠 Generic Greeting
- Uses “Dear Customer” instead of recipient’s name — phishing emails often skip personalization.

---

### 6. 📎 Attachment Check
- No attachment in this example, but phishing emails often include `.zip` or `.exe` files that contain malware.

---

### 7. ✍️ Grammar/Spelling
- Minor grammatical issues like tone and spacing — not as obvious here, but real-world emails often contain mistakes.

---

## 🧠 Conclusion

This email contains multiple phishing red flags:
- Spoofed sender
- Failing SPF/DKIM
- Suspicious URL
- Urgent call to action
- Lack of personalization

It is a textbook example of a **credential phishing attack** using **social engineering**.

---

## 🛡 Recommended Action

- **Do not click the link.**
- **Report the email** to your organization’s IT/security team.
- **Block sender** and mark as phishing in your email client.
