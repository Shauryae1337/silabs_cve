# ![Silicon Labs Vulnerabilities](https://raw.githubusercontent.com/Shauryae1337/silabs_cve/refs/heads/main/cve.png)

<p align="center">
  <img src="https://img.shields.io/badge/CVEs-10-red?style=for-the-badge&logo=cve" alt="10 CVEs Discovered">
  <img src="https://img.shields.io/badge/Severity-High-critical?style=for-the-badge&logo=alert" alt="High Severity">
  <img src="https://img.shields.io/badge/Researcher-Shaurya-blue?style=for-the-badge&logo=github" alt="Researcher Shaurya">
  <img src="https://img.shields.io/badge/Status-Disclosed-success?style=for-the-badge&logo=shield" alt="Status: Disclosed">
</p>

---

## Overview
🎯 This repository highlights my contribution as a **security researcher** in uncovering **10 critical DLL hijacking vulnerabilities** in Silicon Labs products. These vulnerabilities, caused by **uncontrolled search paths**, could lead to **privilege escalation** and **arbitrary code execution**, posing significant risks to system security.

---

## 🚨 Vulnerability Details

### Key Highlights:
- **Researcher Name:** Shaurya  
- **Collaborators:** Sahil Shah, Ramya Shah, Vidhi Patel  
- **Published CVEs:**  
  1. **[CVE-2024-9490](https://www.cve.org/CVERecord?id=CVE-2024-9490)**: DLL hijacking in Silicon Labs IDE installer  
     - Researchers: Shaurya, Sahil Shah  
  2. **[CVE-2024-9491](https://www.cve.org/CVERecord?id=CVE-2024-9491)**: DLL hijacking in Configuration Wizard 2 installer  
     - Researchers: Shaurya, Sahil Shah  
  3. **[CVE-2024-9492](https://www.cve.org/CVERecord?id=CVE-2024-9492)**: DLL hijacking in Flash Programming Utility installer  
     - Researchers: Shaurya, Sahil Shah  
  4. **[CVE-2024-9493](https://www.cve.org/CVERecord?id=CVE-2024-9493)**: DLL hijacking in ToolStick installer  
     - Researchers: Shaurya, Sahil Shah  
  5. **[CVE-2024-9494](https://www.cve.org/CVERecord?id=CVE-2024-9494)**: DLL hijacking in CP210 VCP Win 2k installer  
     - Researchers: Shaurya, Sahil Shah, Ramya Shah  
  6. **[CVE-2024-9495](https://www.cve.org/CVERecord?id=CVE-2024-9495)**: DLL hijacking in CP210x VCP Windows installer  
     - Researchers: Shaurya, Sahil Shah, Vidhi Patel  
  7. **[CVE-2024-9496](https://www.cve.org/CVERecord?id=CVE-2024-9496)**: DLL hijacking in USBXpress Dev Kit installer  
     - Researchers: Shaurya, Sahil Shah  
  8. **[CVE-2024-9497](https://www.cve.org/CVERecord?id=CVE-2024-9497)**: DLL hijacking in USBXpress 4 SDK installer  
     - Researchers: Shaurya, Sahil Shah  
  9. **[CVE-2024-9498](https://www.cve.org/CVERecord?id=CVE-2024-9498)**: DLL hijacking in USBXpress SDK installer  
     - Researchers: Shaurya, Sahil Shah  
  10. **[CVE-2024-9499](https://www.cve.org/CVERecord?id=CVE-2024-9499)**: DLL hijacking in USBXpress Win 98SE Dev Kit installer  
      - Researchers: Shaurya, Sahil Shah  

---

## ⚙️ Technical Summary
The vulnerabilities stem from **uncontrolled search paths** in the impacted installers, making them susceptible to **DLL hijacking attacks**. These vulnerabilities allow attackers to execute arbitrary code with elevated privileges when the installer is executed.

- **CVSS Base Score:** 8.6 (High)  
- **Vector String:** `CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:C/C:H/I:H/A:H`

---

## 🔒 Mitigation and Recommendations
To reduce risks, follow these steps:  
1. Always download installers directly from [Silicon Labs' official website](https://www.silabs.com).  
2. Execute installers from directories with **limited write access**.  

---

## 🏆 Acknowledgments
This research was made possible through collaboration with:  
- **Sahil Shah**  
- **Ramya Shah**  
- **Vidhi Patel**  

Special thanks to Silicon Labs for supporting the responsible disclosure process.

---

## 📚 References
- [CVE-2024-9490 on CVE.org](https://www.cve.org/CVERecord?id=CVE-2024-9490)  
- [Silicon Labs Security Page](https://www.silabs.com/security)  
- [Silicon Labs Technical Support](https://www.silabs.com/support)  

---

<p align="center">
  <img src="https://media.giphy.com/media/QMkPpxPDYY0fu/giphy.gif" alt="Stay Secure!" width="200"/>
</p>
