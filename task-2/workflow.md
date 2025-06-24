# 1. Getting a Phishing Email Sample

### For this task, I needed a sample phishing email to analyze for suspicious indicators such as spoofed sender, malicious links, urgent language, etc.

### Since most samples on the internet are just screenshots, I created a realistic phishing email myself in plain text format for analysis.

### Below is a small part of the sample email content:

```text
From: Netflix Support <support@netflix-cancellation-alerts.com>
To: user@example.com
Subject: Urgent: Your Account Will Be Deactivated!

Dear Customer,

We noticed unusual activity in your Netflix account. To restore access, confirm your details immediately:

👉 https://netflix.com-loginverify-securityupdate.icu
```

---

# 2. Examining the Sender's Email Address

### The sender email address was:

```text
support@netflix-cancellation-alerts.com
```

### This is **not a legitimate Netflix domain**. It’s a clear example of **email spoofing** and is crafted to look real.

---

# 3. Checking Email Headers

### I created a sample email header file with forged entries to simulate real-world phishing. A portion of the headers looked like this:

```text
Return-Path: <support@netflix-cancellation-alerts.com>
Received-SPF: Fail
DKIM-Signature: none
```

- `SPF` check failed : indicates unauthorized sender.
- `DKIM` signature missing : reduces trust score.
- Return path domain doesn't match the real sender.

---

# 4. Identifying Suspicious Links

### The email body contained this suspicious link:

```text
https://netflix.com-loginverify-securityupdate.icu
```

- Although it appears to reference `netflix.com`, the actual domain is **`securityupdate.icu`**, which is completely unrelated.
- The structure is designed to **mislead users** by including legitimate-looking parts in the URL.

---

# 5. Looking for "Urgent" or "Threatening" Language

### The email said:

> _"If you do not verify within 24 hours, your account will be permanently closed."_

- This is a classic phishing tactic, using fear and urgency to pressure users into clicking malicious links or submitting sensitive info.

---

# 6. Verifying Spelling and Grammar Issues

### The body text had slightly awkward phrasing and robotic tone, such as:

> _"confirm your details immediately"_ and _"Your account will be permanently closed"_

- These are **subtle signs** of poorly crafted or automated phishing emails.

---

# 7. Summarising the phishing indicators

- Fake Sender: `support@netflix-cancellation-alerts.com`
- Header Check failed authenticity.
- Suspicious URL: `netflix.com-loginverify-securityupdate.icu`
- Urgency: Threatens account closure in 24 hours.
- Grammar/Tone: Slightly off and robotic.

---
