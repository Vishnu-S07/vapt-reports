# OWASP Juice Shop VAPT Report

This folder contains the Vulnerability Assessment and Penetration Testing (VAPT) report for the OWASP Juice Shop application, completed as part of my cybersecurity internship under the guidance of **Abimel S Kulumala**.

---

## 📌 Project Objective

To identify and exploit common web application vulnerabilities using OWASP Juice Shop — a deliberately insecure web app for security testing and education. The goal was to gain hands-on experience in ethical hacking, and to recommend proper remediations.

---

## 🧰 Tools Used

- **OWASP Juice Shop** – Vulnerable web application
- **Burp Suite Community Edition** – HTTP interceptor and testing tool
- **Browser Dev Tools** – For inspecting and interacting with web content

---

## 🐞 Vulnerabilities Identified

1. **SQL Injection** – Bypassed login and found admin credentials
2. **Reflected Cross-Site Scripting (XSS)** – Executed malicious script via search input
3. **Insecure Direct Object Reference (IDOR)** – Accessed another user's basket
4. **Sensitive Data Exposure** – Discovered and downloaded confidential files from an exposed FTP path

---

## 📄 Report

👉 [Download Full Report (PDF)](./JuiceShop_project_report.pdf)

---

## 🛡️ Suggested Remediations (Summary)

- Use parameterized queries to prevent SQL injection
- Sanitize and encode user inputs to prevent XSS
- Implement object-level permission checks to fix IDOR
- Disable directory listing and protect sensitive files on the server

---

## 🧠 What I Learned

This project helped me:
- Understand how real-world vulnerabilities work
- Practice offensive security in a safe, legal environment
- Improve my skills in Burp Suite and HTTP request manipulation
- Appreciate the importance of secure coding practices

---

## 📚 References

- [OWASP Juice Shop](https://github.com/juice-shop/juice-shop)
- [Burp Suite Documentation](https://portswigger.net/burp/documentation)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)






