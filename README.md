# Task-2-Phishing-Analysis
Phishing Email Analysis | Cybersecurity Internship Task 2

🎯 Objective
To investigate the contents of a suspicious email and detect common phishing traits using manual analysis and online tools.

🧰 Tools Used
- **Email Header Analyzer**: [MXToolbox],[Google Header Analyzer]
- **Sample Phishing Email**: From open-source repositories
- **Web browser tools** to hover and inspect real URLs

📝 Steps Performed

1. Collected a phishing email from a free sample database.
2. Checked the sender email address and domain.
3. Analyzed the full email header using an online tool.
4. Examined hyperlinks, text body, attachments.
5. Listed all suspicious traits with explanations.

 ✉️ Sample Email Analyzed

**Subject:** Urgent: Verify Your PayPal Account to Avoid Suspension  
**From:** `support@paypal.com` <`notify@secure-p4ypal.net`>  
**To:** user@example.com  
**Date:** June 24, 2025

---

**Email Body:**
Dear Customer,

We detected suspicious activity in your PayPal account and have temporarily limited it for your protection.

Please verify your account immediately by clicking the link below:

https://paypal.com.secureverify-login.com

Failure to verify within 24 hours will result in permanent account suspension.

Thank you,
PayPal Security Team


🔍 Phishing Indicators Found

| Indicator                  | Observation                                                                 |
|---------------------------|------------------------------------------------------------------------------|
| **Sender Email**          | Appears legitimate, but domain is `secure-p4ypal.net` not `paypal.com`      |
| **Mismatched Link**       | Text says `paypal.com` but URL is a fake domain (`secureverify-login.com`) |
| **Urgent Language**       | "Failure to verify within 24 hours..." = fear-based urgency                 |
| **Spoofed Branding**      | Uses PayPal logo and formatting, but not from the real domain               |
| **Grammar Issues**        | Slightly odd sentence: "have temporarily limited it for your protection"    |
| **Header Analysis**       | Return-path IP was from a server in Eastern Europe (not PayPal-owned)       |

---



