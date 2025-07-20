# Penetration Testing & Vulnerability Assessment Report

This repository contains the documentation of penetration testing and vulnerability assessment activities conducted on **Windows and Ubuntu Virtual Machines**, as well as the web application **testphp.vulnweb.com**.

## 📄 Files Included

- `Penetration_Testing_Report.pdf`: Complete report with both technical and non-technical findings.

---

## 🔍 1. VM Penetration Testing

### ✅ Platforms Tested
- **Windows VM**
- **Ubuntu VM**

### 🔧 Tools Used
- Nmap
- Metasploit
- Nessus
- Nikto
- Wireshark
- Burp Suite
- John the Ripper

### 🚨 CVEs Identified

#### 🖥️ Windows
- CVE-2020-0796 (SMBGhost)
- CVE-2019-0708 (BlueKeep)
- CVE-2017-0143 (MS17-010)

#### 🐧 Ubuntu
- CVE-2020-8597 (PPP Daemon)
- CVE-2019-5736 (runc container)
- ProFTPD 1.3.3cL Backdoor

---

## 🌐 2. Web Vulnerability Assessment

### 🔎 Target Site
- [testphp.vulnweb.com](http://testphp.vulnweb.com)

### 🧪 Techniques
- Manual SQL Injection via Burp Suite
- Automated enumeration with SQLmap

### 📚 Findings
- SQL injection in login form
- Full database enumeration (`acuart` DB)
- Retrieved user credentials

### 🔐 CVEs
- CVE-2020-9484 (Apache Tomcat RCE)
- CVE-2019-0232 (Apache Tomcat CGI RCE)

---

## 🔐 Recommendations

- Patch known CVEs immediately.
- Close unused ports, disable unnecessary services.
- Use MFA and strong passwords.
- Apply least-privilege on database users.
- Monitor system and DB logs regularly.

---

## ✅ Author

**Jogi Venkata Sai Kiran**  
Reg. No: 42614048  
Cyber Security, Sathyabama University
