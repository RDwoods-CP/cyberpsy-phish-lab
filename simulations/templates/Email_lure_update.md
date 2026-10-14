# Simulation Template: Urgent IT MFA Re-enrollment

## 1. Campaign Metadata
* **Campaign ID:** SIM-2026-001
* **Target Audience:** General corporate staff (High focus on Operations and Finance)
* **Primary Psychological Vectors:** Authority Bias, Urgency, Fear of System Lockout
* **Difficulty Level:** Intermediate (Utilizes localized domain spoofing context)

---

## 2. Email Copy (The Lure)

**Subject:** URGENT: Mandatory Security Update Required for Single Sign-On (SSO)
**Sender Display Name:** Global IT Security Desk <security-updates@corp-internal-support.com> *(Simulated Lookalike Domain)*

> Dear Employee,
> 
> Following recent credential intelligence alerts affecting our regional network perimeter, the IT Security Department is enforcing an immediate mandatory multi-factor authentication (MFA) re-synchronization.
> 
> All employees must re-verify their corporate credentials within the next **2 hours** to prevent temporary suspension of email, Slack, and internal application access.
> 
> **[ CLICK HERE TO COMPLETE MFA RE-ENROLLMENT ]** *(Hyperlinked to tracking server landing page)*
> 
> If you have questions, contact the helpdesk through your normal internal channels.
> 
> Best regards,  
> **IT Infrastructure & Security Operations**

---

## 3. Landing Page Experience (The Teachable Moment)
When a user clicks the tracking link, they should **never** be met with a credential harvester in a live lab environment. Instead, they should immediately hit a safe landing page designed for micro-training:

* **Header:** ⚠️ *Simulation Notice: This was a security awareness test.*
* **Immediate Feedback:** Displays *why* this email was suspicious:
  1. **The Urgency Trap:** A 2-hour threat window is designed to cause panic (System 1 thinking).
  2. **Domain Anomaly:** The sender address `corp-internal-support.com` is external and unverified.
  3. **Out-of-Channel Request:** Real IT updates never demand verification through random email links.
* **Actionable Next Step:** A single button to report the email via the official phish-reporting plugin.

---

## 4. Telemetry & Behavioural Metrics to Track
* **Time-to-Click (TTC):** Duration between email delivery and clicking the link.
* **Peak Vulnerability Window:** Correlation between click times and time-of-day/workload peaks.
* **Reporting Velocity:** How many users reported the email via the internal reporting button instead of clicking.
