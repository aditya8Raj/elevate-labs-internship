# Task 2: Analyze a Phishing Email Sample

This task helped me understand how phishing emails are crafted to trick users and how to analyze them effectively. I created a realistic phishing email sample to inspect key indicators like spoofed senders, suspicious links, and headers.

---

## Key Concepts I Explored

- **Phishing Emails:**
  I learned how phishing attacks manipulate human behavior through fear, urgency, and fraud to steal sensitive information.

- **Email Spoofing:**
  I analyzed a forged sender email like `support@netflix-cancellation-alerts.com`, which mimicked a legitimate service but came from a fake domain.

- **Header Analysis:**
  I reviewed forged email headers showing a failed SPF check and missing DKIM signature—signs that the email is likely simulated and unauthentic.

- **Suspicious URLs:**
  I spotted a fake domain like `https://netflix.com-loginverify-securityupdate.icu` that appears legitimate at first glance but is actually a phishing domain.

- **Language and Grammar:**
  I looked for aggressive tone, urgency, and slightly robotic wording, all typical of phishing campaigns.

---

## My Takeaways

- Phishing emails don’t always look suspicious on the surface. You have to look deeper, at headers, sender info, and link domains.
- Social engineering is powerful. The fear of losing access, mixed with urgency, tricks people into acting fast without thinking.
- Learning to manually analyze phishing emails builds a solid foundation for defending against real-world email threats.

---

For full report of the steps and indicators I analyzed, open this file: [`workflow.md`](workflow.md)  
The email sample used is in: [`phishing-email.txt`](phishing-email.txt)
