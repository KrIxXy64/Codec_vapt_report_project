# Codec_vapt_report_project
VAPT Project – DVWA & OWASP Juice Shop

🔍 Overview

This project is a complete Vulnerability Assessment and Penetration Testing (VAPT) performed on two intentionally vulnerable applications running in a controlled local environment:
	•	DVWA
	•	OWASP Juice Shop

The objective was to learn practical web application pentesting techniques and document the findings in a structured VAPT report.

⸻

🛠 Tools Used
	•	Kali Linux
	•	Nmap – Port & service discovery
	•	Nikto – Web vulnerability scanning
	•	Browser (Firefox/Chromium)
	•	DVWA (Damn Vulnerable Web Application)
	•	OWASP Juice Shop

⸻

⚙️ Methodology
	1.	Reconnaissance
	•	Identified active hosts
	•	Performed service detection & OS fingerprinting using Nmap
	2.	Vulnerability Scanning
	•	Ran Nikto for web server misconfiguration & outdated software
	•	Observed results manually
	3.	Manual Exploitation
	•	SQL Injection (DVWA)
	•	XSS (DVWA & Juice Shop)
	•	Command Injection (DVWA)
	4.	Documentation
	•	Screenshots captured & stored
	•	Professional PDF report createdVAPT-Project/

  project structure
 ├── scans/
 ├── screenshots/
 ├── exploitation/
 ├── report/
 └── README.md
 Key Vulnerabilities Found

DVWA
	•	SQL Injection
	•	Reflected XSS
	•	Command Injection

Juice Shop
	•	Reflected XSS in Search Feature

⸻

📄 Report

The complete report is available here:

👉 report/VAPT_Report.pdf

⸻

🙌 Author

Sarthak Singh Dangi
Intern – CodeCTe Technologies

 
