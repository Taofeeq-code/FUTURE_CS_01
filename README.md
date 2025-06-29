# FUTURE_CS_01
Cybersecurity Internship
OVERVIEW
This repository contains the task 01 of my cybersecurity internship assessment.
the objective of this task is to successfully conduct a security testing on web application, identify vulnerabilities and document the findings.


[Install & Launch ZAP](url)
1.	Download OWASP ZAP:
https://www.zaproxy.org/download/


2.	Install and open ZAP.
    • Automated Scan” for quick analysis or
    • Manual Explore” for more control (recommended for auth testing).


[Pull the Docker Image for OWASP Juice Shop](url)
In your terminal, run: docker pull bkimminich/juice-shop


[Run OWASP Juice Shop with Docker](url)
docker run -d -p 3000:3000 bkimminich/juice-shop


[Access the app in browser:](url)
http://localhost:3000/
 Juice Shop is now live and vulnerable.


[STEPS FOR VULNERABILITY ASSESSMENT](url)
     • Deployed a vulnerable app (Juice Shop)
     • Scanned it using ZAP Proxy (via Docker)
     • Find real-world issues (SQLi, XSS, Auth flaws)
     • Documented results in a formal report


[EXPECTED RESULTS](url)
• identify vulnerabilities ans severity
• suggest remediation process


[DEPENDENCIES & REQUIREMENTS](url)
        • OWASP ZAP (for automated security scanning)
	• SQLmap (for SQL injection testing, optional)
	• Modern Web Browser (Chrome/Firefox with Developer Tools)
	• Operating System Compatibility: Works on Windows, Linux, macOS
