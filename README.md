<!-- ========================================================= -->
<!--  HEADER                                                   -->
<!-- ========================================================= -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,30:0a0a0a,60:140000,100:ff1a1a&height=200&section=header&text=Website%20Security%20Report&fontSize=34&fontColor=ff1a1a&animation=fadeIn&fontAlignY=38&desc=Web%20Application%20VAPT%20%C2%B7%20Proof%20of%20Concept%20%C2%B7%20Remediation&descSize=15&descColor=a3a3a3&descAlignY=58"
    width="100%"
    alt="Website Security Report"
  />
</p>

<p align="center">
  <a href="https://sachincybersecurity.site.je/"><img src="https://img.shields.io/badge/Portfolio-ff1a1a?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="./Pentest_Report_sachincybersecurity.pdf"><img src="https://img.shields.io/badge/Full%20Report-ff0033?style=for-the-badge&labelColor=000000&logo=adobeacrobatreader&logoColor=white" alt="Full report"></a>
  <a href="https://github.com/sachinpatil19-cyber-security"><img src="https://img.shields.io/badge/GitHub%20Profile-b91c1c?style=for-the-badge&labelColor=000000&logo=github&logoColor=white" alt="GitHub profile"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Type-Web%20App%20VAPT-ff1a1a?style=flat-square&labelColor=0a0a0a" alt="Type">
  <img src="https://img.shields.io/badge/Standard-OWASP%20Top%2010-7f1d1d?style=flat-square&labelColor=0a0a0a" alt="OWASP">
  <img src="https://img.shields.io/badge/Target-Own%20Website-b91c1c?style=flat-square&labelColor=0a0a0a" alt="Target">
  <img src="https://img.shields.io/badge/Format-PDF%20Report-ff0033?style=flat-square&labelColor=0a0a0a" alt="Format">
</p>

<p align="center">
  <em>A hands-on web application vulnerability assessment and penetration test of my own cybersecurity portfolio website.</em>
</p>

---

## What this report shows

| | |
|---|---|
| **Role fit** | VAPT / Cyber Security Associate |
| **Target** | My own portfolio website ([sachincybersecurity.site.je](https://sachincybersecurity.site.je/)) |
| **Focus areas** | Authentication · Session management · Input validation |
| **Deliverable** | Client-style report with scope, methodology, risk-rated findings, PoC and remediation |

---

## Report at a glance

<!-- EDIT: replace X with the real numbers from your PDF -->

| **9** <br> Total Findings | **2** <br> High / Critical | **4** <br> Medium | **1** <br> Low / Info |
|:---:|:---:|:---:|:---:|

---

## Methodology

```text
Reconnaissance → Vulnerability Identification → Manual & Automated Testing
      → Exploitation Validation → Proof of Concept → Remediation & Reporting
```

| Phase | What was done |
|---|---|
| **1. Recon** | Mapped the attack surface, technologies and entry points |
| **2. Identification** | Scanned and reviewed for known weakness classes |
| **3. Testing** | Manual and automated testing of auth, sessions and inputs |
| **4. Validation** | Confirmed exploitability and removed false positives |
| **5. PoC** | Documented reproducible steps and evidence |
| **6. Reporting** | Risk-rated findings with clear remediation guidance |

---

## Focus areas

| Area | What was checked |
|---|---|
| **Authentication** | Login flow, credential handling, access control |
| **Session management** | Cookie flags, session lifetime, token handling |
| **Input validation** | Injection and XSS-type weaknesses, error handling |

---

## Key findings

<!-- EDIT: replace the example rows with the real findings from your report -->

| # | Finding | Severity | Status |
|:---:|---|:---:|:---:|
| 1 | _Finding title_ | ![High](https://img.shields.io/badge/High-ff0000?style=flat-square) | Fixed |
| 2 | _Finding title_ | ![Medium](https://img.shields.io/badge/Medium-f59e0b?style=flat-square) | Fixed |
| 3 | _Finding title_ | ![Low](https://img.shields.io/badge/Low-6b7280?style=flat-square) | Open |

---

## Tools used

<!-- EDIT: remove any tool you did not use in this assessment -->

<p>
  <img src="https://img.shields.io/badge/Burp%20Suite-ff3b30?style=for-the-badge&labelColor=0a0a0a" alt="Burp Suite">
  <img src="https://img.shields.io/badge/Nmap-ff1a1a?style=for-the-badge&labelColor=0a0a0a" alt="Nmap">
  <img src="https://img.shields.io/badge/Nessus-7f1d1d?style=for-the-badge&labelColor=0a0a0a" alt="Nessus">
  <img src="https://img.shields.io/badge/Kali%20Linux-450a0a?style=for-the-badge&labelColor=0a0a0a&logo=kalilinux&logoColor=white" alt="Kali Linux">
  <img src="https://img.shields.io/badge/SQLMap-b91c1c?style=for-the-badge&labelColor=0a0a0a" alt="SQLMap">
  <img src="https://img.shields.io/badge/Nuclei-991b1b?style=for-the-badge&labelColor=0a0a0a" alt="Nuclei">
</p>

---

## Repository contents

| File | Description |
|---|---|
| [`Pentest_Report_sachincybersecurity.pdf`](./Pentest_Report_sachincybersecurity.pdf) | Full penetration testing report |
| [`security-assessment-animated.svg`](./security-assessment-animated.svg) | Animated assessment dashboard |

<p align="center">
  <img src="./security-assessment-animated.svg" alt="Animated Security Assessment Dashboard" width="760">
</p>

---

## Scope and ethics

All testing was performed on a website I own, with full authorization. No third-party systems were tested. Please do not use anything here against systems you do not own or have written permission to test.

---

<p align="center">
  <strong>Open to VAPT / Cyber Security Associate roles</strong> — Web, API and Network penetration testing<br><br>
  <a href="https://github.com/sachinpatil19-cyber-security">GitHub</a> ·
  <a href="https://sachincybersecurity.site.je/">Portfolio</a> · Mumbai, Maharashtra
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff1a1a,40:140000,100:000000&height=100&section=footer" width="100%" alt="">
</p>
