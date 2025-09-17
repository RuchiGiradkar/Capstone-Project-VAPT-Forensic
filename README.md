# Capstone-Project-VAPT-Forensic

# Capstone Project – VAPT & Forensic Analysis

## Project Overview  
This project focuses on **Vulnerability Assessment and Penetration Testing (VAPT)** combined with **Forensic Evidence Collection**.  
The assessment simulated real-world attacks on **TechShield’s corporate lab environment**, identifying system weaknesses, exploiting them ethically, and validating findings with forensic investigation.  

**Key Goals:**  
- Identify and assess vulnerabilities in network and web applications.  
- Perform password security testing to detect weak credentials.  
- Apply forensic techniques to recover hidden evidence and ensure chain of custody.  

---

## Problem Statement  
TechShield reported recurring security incidents caused by:  
- Weaknesses in **network, web applications, and passwords**.  
- Lack of **forensic readiness** to investigate incidents.  

**Need:**  
A comprehensive **VAPT engagement** with integrated **digital forensics**.  

---

## Tools & Platforms Used  
- Reconnaissance & Scanning: Netdiscover, Nmap, Greenbone (OpenVAS)  
- Web Testing: DVWA (SQL Injection, XSS, File Upload, Reverse Shell)  
- Password Attacks: Hydra, Metasploit (EternalBlue)  
- Forensics: Autopsy, md5sum  

---

## Approach (Phased Testing)  
1. Reconnaissance – Information gathering (hosts, ports, OS, services).  
2. Target Assessment – Vulnerability scanning & enumeration.  
3. Exploitation & Validation – SQLi, XSS, Hydra password cracking, reverse shells.  
4. Forensic Analysis – Hash verification, hidden file recovery, and evidence documentation.  

---

## Project Outcomes  
- 58 vulnerabilities identified (16 High, 38 Medium, 4 Low).  
- Outdated OS and SMB vulnerabilities (MS17-010) exploited.  
- Weak passwords cracked (`Administrator: P@ssw0rd`, `student: P@ssw0rd`).  
- Web application flaws (SQLi, XSS, File Upload) successfully exploited.  
- 5 hidden images recovered during forensic investigation (chain of custody preserved).  

---

## Recommendations  
- Patch outdated systems (migrate from unsupported Windows versions).  
- Enforce strong password policies & MFA.  
- Apply secure coding practices (input validation, WAF).  
- Standardize forensic investigation procedures and train staff.  

---

## Repository Contents  
- **Capstone_Project_Ruchi_Giradkar.pptx** – Final project presentation.  
- **Final_VAPT_Report-Ruchi_Giradkar.pdf** – Detailed assessment report.  
- **Screenshots/** – Evidence and findings from the engagement.  

---

## Author  
**Ruchi Giradkar**  
- Master’s in Mechatronic & Cyber-Physical Systems – Deggendorf Institute of Technology, Germany.  
- Cybersecurity Specialist with 3+ years of experience in **risk assessment, vulnerability analysis, and security architecture**.  
