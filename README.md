# 📧 Phishing Email Analysis – Cybersecurity Internship Task 2

## 🏢 Internship Program
**Cybersecurity Internship – Elevate Labs**  
**Task 2:** Phishing Email Investigation  
**Intern:** ABINASH I 
**Date:** 05/08/2025

---

## 🔍 Task Objective
Analyze a suspicious phishing email to identify key phishing indicators, including spoofed sender details, suspicious links, and malicious attachments.

---

## 📁 Files in This Repository

- 📄 `from_paypal.txt` – Raw content of the phishing email  
- 📄 `header.txt` – Original email header for analysis  
- 📄 `Phishing_analyzer.pdf` – Complete investigation report  with 📁 `screenshots/` – Supporting images 

---

## 📄 Email Sample Summary

- **Sender:** `support@paypalsecure.com`
- **Subject:** Urgent: Your PayPal Account Has Been Suspended!
- **Content:** Claims suspicious login activity and urges verification
- **Link:** `http://paypal.verify-login-secure.com`
- **Attachment:** `verify_account_form.exe`

---

## 🚩 Key Phishing Indicators

- 🕵️ **Spoofed Sender Domain** – Pretends to be PayPal, but uses a fake domain (`paypalsecure.com`)
- 🌐 **Suspicious URL** – Imitates official PayPal login
- 📎 **Malicious .exe Attachment** – Potentially harmful malware
- ⚠️ **Urgency & Threats** – Attempts to scare the user into immediate action
- ✍️ **Grammatical Errors** – Common in phishing campaigns
- 🔗 **Mismatched URLs** – Hover text differs from actual link

---

## 🧪 Tools Used

| Tool | Purpose | Link |
|------|---------|------|
| 🔍 **MxToolbox** | Analyze email headers and domain reputation | [https://mxtoolbox.com/](https://mxtoolbox.com/) |
| 📧 **Google Header Analyzer** | Parse and visualize email headers | [https://toolbox.googleapps.com/apps/messageheader/](https://toolbox.googleapps.com/apps/messageheader/) |
| 🛡️ **VirusTotal** | Scan links and files for known threats | [https://www.virustotal.com/](https://www.virustotal.com/) |
| 🧪 **Any.Run** | Dynamic malware analysis sandbox | [https://any.run/](https://any.run/) |
| 🧬 **Hybrid Analysis** | Sandbox for malware behavior | [https://www.hybrid-analysis.com/](https://www.hybrid-analysis.com/) |

---

## ✅ Conclusion

The investigation confirms that the email is a **phishing attack**, using **social engineering** and **malware distribution** to steal user credentials and infect devices.

---

## 🛡️ Recommendations

- 🚫 Never download or run `.exe` files from unknown sources  
- 🔍 Always inspect email headers and links before clicking  
- 📢 Report phishing to the original service provider (e.g., PayPal)  
- 🧠 Educate users on common phishing tactics

---

## 📌 Disclaimer

This project was created as part of the **Elevate Labs Cybersecurity Internship** for educational and awareness purposes only. All tools and techniques were used within legal and controlled environments.
