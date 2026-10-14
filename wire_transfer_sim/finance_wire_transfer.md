# Simulation Template: Urgent Executive Wire Transfer (BEC)

## 1. Campaign Metadata
* **Campaign ID:** SIM-2026-002
* **Target Audience:** Finance, Accounting, and Executive Support Staff
* **Primary Psychological Vectors:** Authority Bias, Urgency, Fear of Causing Business Disruption
* **Difficulty Level:** Advanced (Utilizes executive persona spoofing and confidential context)

---

## 2. Email Copy (The Lure)

**Subject:** CONFIDENTIAL: Urgent Vendor Settlement - [Target Company Name] Acquisition
**Sender Display Name:** [CEO Name] <ceo.executive.office@gmail-secure-portal.com> *(Simulated Lookalike/External Domain)*

> Hi [Target Name],
> 
> I am currently tied up in an all-day board meeting with our prospective acquisition partners in London. 
> 
> We need to execute an emergency wire transfer to our primary escrow account today to lock down the initial phase before markets close. Our regular banking portal token is currently locked out while I am remote.
> 
> Please process the transfer using the updated banking coordinates attached below immediately. Do not discuss this externally yet as it is under strict NDA.
> 
> Let me know once the transaction receipt is sent over.
> 
> Best,  
> **[CEO Name]**  
> *Chief Executive Officer*  
> *(Sent via mobile device)*

---

## 3. Landing Page Experience (The Teachable Moment)
When a user clicks the tracking link or downloads the attached "coordinates," they should immediately hit a safe micro-training landing page:

* **Header:** ⚠️ *Simulation Notice: This was a Business Email Compromise (BEC) awareness test.*
* **Immediate Feedback:** Displays *why* this spear-phishing attack succeeded or failed:
  1. **The Authority Trap:** Leveraging the CEO's name combined with a strict NDA/confidentiality constraint to bypass independent verification.
  2. **Out-of-Band Failure:** The lure explicitly discourages checking via normal communication channels ("Do not discuss this externally yet").
  3. **Domain Anomaly:** The sender address uses a deceptive external or lookalike domain rather than the corporate email infrastructure.
* **Actionable Remediation:** Reminds staff of the mandatory dual-authorization policy: *Any financial wire or account modification initiated via email must be verified via a secondary verbal or internal Slack confirmation.*

---

## 4. Telemetry & Behavioural Metrics to Track
* **Inquiry vs. Compliance Rate:** Do users attempt to verify the request with the CEO via text/Slack, or do they blindly follow the instructions?
* **Bypassed Controls:** Frequency with which standard financial double-check protocols are skipped under time pressure.
* **Reporting Speed:** Time elapsed before the finance team flags the email as suspicious to the security operations center.
