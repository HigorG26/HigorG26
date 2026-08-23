<div align="center">

# Higor Gabriel Ferreira Silva

**Systems Analyst · Offensive Security & Secure Development**

Florianópolis, SC — Brazil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/higorgabrielfs/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:higor.gabrielfds@gmail.com)

</div>

---

I build applications by day and take them apart in the lab by night.

Four years of back-end and full stack development (C#/.NET, SQL Server, REST APIs) now pointed at offensive security. That combination is the whole point: I read code the way a developer does and attack it the way an attacker does — which makes findings land with remediation attached, not just a severity label.

Currently completing a postgraduate program in **Cybersecurity** at IDESP / Instituto Daryus, preparing for **OSCP**, and open to security roles internationally.

```
Focus      →  Web, infrastructure & mobile penetration testing
Building   →  VulnScan Toolkit — modular scanner orchestrator in Python
Learning   →  OSCP path · Active Directory · cloud security
Languages  →  Portuguese (native) · English (C1) · Spanish (B2)
```

---

## Featured Project

### [VulnScan Toolkit](https://github.com/HigorG26/h-scan/tree/master/Cyber/vulnscan-toolkit)

A containerized, modular orchestrator for web vulnerability scanning that unifies **Nikto, SQLMap, OWASP ZAP and Nuclei** behind a single CLI and consolidates everything into one professional report.

- **Decoupled architecture** — every tool is a thin adapter that normalizes output into a single `Finding` model, so scanners can be swapped or added without touching the core
- **Reporting engine** — Jinja2 + WeasyPrint produce HTML/PDF with executive summary, CVSS-based severity, technical evidence and remediation guidance
- **Scope enforcement** — a `ScopeGuard` allowlist in YAML plus a mandatory `--i-have-authorization` flag; scans against unlisted targets are aborted by design
- **Fully containerized** — Docker isolates sqlmap, Nikto, Nuclei and ZAP from the host, so nothing conflicts with an existing Kali setup

`Python 3.11` · `Docker` · `Jinja2` · `WeasyPrint` · `PyYAML`

> Built for authorized engagements and lab environments only.

---

## Security

<p align="left">
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square&logo=owasp&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/Nuclei-1A1A1A?style=flat-square&logo=projectdiscovery&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/SQLMap-C41E3A?style=flat-square&logo=sqlite&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=nmap&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/Nessus-00A4E4?style=flat-square&logo=tenable&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/JADX-3DDC84?style=flat-square&logo=android&logoColor=white" height="26" />
<img src="https://img.shields.io/badge/MobSF-6A1B9A?style=flat-square&logo=android&logoColor=white" height="26" />
</p>

**Web & infrastructure** — OWASP Top 10 in practice: SQL Injection, XSS (reflected, stored, DOM), CSRF, XXE, IDOR, file upload/inclusion, broken access control · full cycle from reconnaissance and enumeration through exploitation and reporting

**Mobile (Android)** — static and dynamic analysis: APK decompilation, endpoint and cached-data mapping, hardcoded secret discovery, runtime traffic manipulation

**OSINT & forensics** — metadata and GPS extraction, breach-index research, evidence consolidation

**Secure development** — SDLC practices, application hardening, access control with JWT/OAuth and Azure AD

---

## Development

<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="34" title="C#" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" height="34" title=".NET" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="34" title="Python" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="34" title="Bash" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="34" title="TypeScript" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="34" title="JavaScript" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="34" title="Angular" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="34" title="React" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="34" title="Node.js" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" height="34" title="SQL Server" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="34" title="MySQL" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" height="34" title="Oracle" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="34" title="Docker" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="34" title="Linux" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" height="34" title="Azure" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="34" title="Git" />
</p>

Day to day I work on enterprise C#/.NET applications with SQL Server and NHibernate, JWT/OAuth authentication integrated with Azure AD, access controls and input validation, and process automation with N8N.

I also use LLMs (Claude) as part of my workflow — code triage, findings review, evidence correlation and report standardization — always with manual validation of the output, because an unverified finding is worse than no finding.

---

## Other Repositories

| Repository | What it is | Stack |
|---|---|---|
| [CRAG_WEB](https://github.com/HigorG26/CRAG_WEB) | Web interface for an AI application | TypeScript · Angular |
| [taskManager](https://github.com/HigorG26/taskManager) | Task CRUD with add, edit and delete | React · TypeScript · Tailwind |
| [API-Express-TS](https://github.com/HigorG26/API-Express-TS) | Back-end API for React integration | Node.js · Express · TypeScript |
| [Python_DataAnalysis](https://github.com/HigorG26/Python_DataAnalysis) | Automation of a manual date-validation task | Python · Jupyter |

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=HigorG26&layout=compact&langs_count=6&card_width=340&theme=dark&hide_border=true" height="150" alt="Top languages" />

**Open to security opportunities — Brazil and international.**

</div>
