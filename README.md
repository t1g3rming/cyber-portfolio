<!-- ===== README: Cyber Portfolio ===== -->
# ⚡ Tiger Ming — Cybersecurity Portfolio
> Hands-on security labs • SOC triage • pentest writeups • cloud audits  
> _I build, break (in my lab), and fix — then I explain it simply._

[![Projects](https://img.shields.io/badge/Projects-4-green)]()
[![Skills](https://img.shields.io/badge/Skills-Nmap%20%7C%20Python%20%7C%20Splunk%20%7C%20AWS-blue)]()
[![Contact](https://img.shields.io/badge/Contact-tiger.ming%40example.com-orange)]()

---

## ✨ Quick Pitch (TL;DR)
- **What:** Real, reproducible security labs — network recon, exploit writeups, SOC incident triage, and cloud misconfigurations.  
- **Why:** Show employers *what I can do* — not just what I studied.  
- **Where to start:** Open `project-port-scanner/` for a runnable demo, or jump to `project-soc-incident/` for a SOC playbook.

---

## 🔎 Featured Projects (click a folder)
> Each project includes: a one-line executive summary, step-by-step reproduction, sanitized artifacts, remediation, and a resume-ready line.

- 🧰 **Port Scanner (Python)** — `project-port-scanner/`  
  Multithreaded TCP scanner + report. Run locally, study the code, improve it.

- 🕵️ **Network Recon → Exploit** — `project-network-recon/`  
  Nmap → service enumeration → lab exploit → privilege escalation. Includes `nmap` XML and screenshots.

- 🛡️ **SOC Incident Triage (Let’sDefend)** — `project-soc-incident/`  
  Phishing -> IOC extraction -> Splunk queries -> containment & playbook. Real SIEM workflows.

- ☁️ **AWS Misconfig Audit** — `project-aws-audit/`  
  Found public S3 & loose IAM roles in my test account — fixed with Terraform & least-privilege rules.

---

## 🚀 Quick Start (run the Port Scanner)
```bash
# clone repo (replace <your-github-username> below)
git clone https://github.com/<your-github-username>/cyber-portfolio.git
cd cyber-portfolio/project-port-scanner

# run scanner (lab use only)
python3 port_scanner.py 127.0.0.1 1 1024

# view results
cat scan_results.txt

Performed network reconnaissance and documented exploitation & remediation steps for controlled lab VMs (Nmap, Metasploit).

Triaged SOC alerts with Splunk and produced IOC timelines + containment playbooks (Let’sDefend labs).

Implemented secure AWS IAM & S3 configurations and validated with Terraform in a disposable test account.

🛠 Skills & Tools

Networking: Nmap, Wireshark, tcpdump
Offensive: Metasploit, Burp Suite, sqlmap
Blue Team / SIEM: Splunk, Splunk SPL, Microsoft Sentinel basics
Cloud: AWS (IAM, S3), Terraform (test infra)
Scripting: Python (automation, scanners), Bash

🎥 2-min demos (replace with your unlisted links)

Port Scanner demo → https://youtu.be/UNLISTED_PORT_SCANNER_LINK

SOC incident walkthrough → https://youtu.be/UNLISTED_SOC_WALKTHROUGH_LINK

(Replace the two links above with your YouTube unlisted/demo links or remove if you don’t have videos yet.)

⚠️ Ethics & scope

I only test systems I own or have explicit permission to test. All published artifacts are sanitized — no keys, no customer data, no live targets.

📬 Contact / Next steps

If you want a walkthrough or a mock interview code review, DM me on LinkedIn or email: tiger.ming@example.com

(Replace with your real contact info.)
