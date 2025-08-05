# Phishing-Email-Analysis
Report for phishing email investigation - Cybersecurity Internship

# 📧 Phishing Email Analysis - Cybersecurity Internship Task 2

## 🔍 Task Objective
Analyze a suspicious phishing email to identify key phishing indicators, including spoofed sender details, suspicious links, and malicious attachments.

---

## 📄 Email Sample Details

- **Sender:** `support@paypalsecure.com`
- **Subject:** Urgent: Your PayPal Account Has Been Suspended!
- **Body:** Claims suspicious activity and demands urgent verification.
- **Link:** `http://paypal.verify-login-secure.com`
- **Attachment:** `verify_account_form.exe`

---

## 🚩 Phishing Indicators Identified

- **1. Spoofed Email Address:**  
  Appears to be from PayPal but is actually a fake domain (`paypalsecure.com`).

- **2. Fake Verification Link:**  
  The link redirects to a phishing domain that imitates PayPal.

- **3. Malicious Attachment:**  
  `.exe` file likely contains malware to compromise the system.

- **4. Urgent & Threatening Language:**  
  Phrases like "your account will be permanently locked" are meant to create panic.

- **5. Grammar and Spelling Errors:**  
  Unprofessional tone and minor language issues in the email body.

- **6. Mismatched URLs:**  
  Hovering the link reveals a different destination than what is displayed.

---

## 🧪 Tools Used

- Online Email Header Analyzer (e.g., MxToolbox, Google Header Analyzer)
- URL Inspection (Hover and VirusTotal)
- Attachment Analysis using Any.Run or Hybrid Analysis Sandbox
- Screenshot Tools for Evidence Collection

---

## ✅ Conclusion

The analyzed email is a **phishing attempt** containing both a **malicious link** and a **malicious executable file**. It uses social engineering tactics to trick the user into revealing personal information or infecting their system.

---

## 🛡️ Recommendation

- Never click links or download attachments from suspicious emails.
- Always verify the sender's domain and report phishing to relevant platforms (e.g., PayPal phishing report center).

---


