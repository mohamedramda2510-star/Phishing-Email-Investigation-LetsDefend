Phishing Email Investigation – LetsDefend

1. Overview

This project documents a practical email phishing investigation completed on the LetsDefend platform.

Objective: Analyze a suspicious email, examine its headers, identify suspicious indicators, and determine whether the email is a phishing attempt.

- Platform: LetsDefend
- Category: Email Security
- Status: Completed (100%)

---

2. Investigation Process & Findings

Step 1 – Return-Path Analysis

Question: What is the Return-Path of the email?

Finding:
"bounce@rjttznyzjjzydnillquh.designclub.uk.com"

Evidence:

<img width="671" height="433" alt="Screenshot 2026-11-18 130650" src="https://github.com/user-attachments/assets/29ddd17a-7054-496f-810b-c87adf61280e" />


"Return Path Analysis" (01-return-path.jpg)

Step 2 – URL Domain Analysis

Question: What is the domain name of the URL in this mail?

Finding:
"storage.googleapis.com"

Lab Assessment: Suspicious domain – Yes.

Evidence:

<img width="727" height="223" alt="Screenshot 2026-11-18 131121" src="https://github.com/user-attachments/assets/a87e909c-d0d2-40cd-9c42-b569f10bcb8a" />


"URL Domain Analysis" (02-url-domain.jpg)

Step 3 – Sender IP Identification

Question: What is the sender IP address listed in the Received-SPF header?

Finding:
"134.195.196.43"

Evidence:

<img width="716" height="235" alt="Screenshot 2026-11-18 131335" src="https://github.com/user-attachments/assets/09c84abe-3e58-431b-9882-7e95c86e3e00" />


"Sender IP Identification" (03-sender-ip.jpg)

---

3. Final Verdict

Is this email a phishing email?

Answer: YES – Phishing Email.

The investigation was completed successfully, and all lab questions were answered correctly.

---

4. Skills Demonstrated

- Email Header Analysis
- Return-Path Analysis
- URL and Domain Analysis
- Sender IP Identification
- Phishing Email Investigation
- Email Security Analysis

---

5. Disclaimer

This investigation was completed in an educational lab environment on LetsDefend for cybersecurity learning and portfolio purposes.
