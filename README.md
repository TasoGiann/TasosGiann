# Tasos Giannoulis
 
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tasos-giannoulis/)
[![Focus](https://img.shields.io/badge/Focus-DFIR-0B3D91?style=for-the-badge)]()
[![Location](https://img.shields.io/badge/Location-Greece-004080?style=for-the-badge)]()
 
Aspiring **Digital Forensics & Incident Response (DFIR) Analyst**. Cybersecurity & Networks student at Metropolitan College (in partnership with University of East London), based in Greece.
 
I'm building a public portfolio of hands-on DFIR work — home lab builds, triage tooling, Windows artifact deep-dives, memory forensics cases, network analysis, and end-to-end incident investigations — because the fastest way to a junior DFIR role is not another certificate. It's visible evidence that I can actually do the work.
 
---
 
## What I'm focused on
 
**Investigative skills** — building the mindset that separates DFIR analysts from alert-triagers: hypothesis → evidence → revised hypothesis → conclusion. Every writeup in my repos is structured that way on purpose.
 
**The core DFIR domains** — working my way systematically through disk forensics, memory forensics, network forensics, and log analysis. Not specializing yet. The plan is to stay broad for 2–3 years before picking a lane.
 
**Cloud forensics** — the highest-leverage specialization in modern IR, and the one most junior candidates ignore. Starting AWS CloudTrail investigations as my differentiator project.
 
**Writing clearly** — DFIR is 30% technical work, 70% report writing that non-technical stakeholders act on. I treat every README and writeup as a writing sample.
 
---
 
## Portfolio (in progress through 2026)
 
A phased 12-project portfolio. Each repo is standalone, documented, and tied to real hands-on lab work — never theory alone.
 
**Foundations**
- `dfir-home-lab` — documented lab build: network diagram, VM specs, setup steps, baselines
- `linux-triage-toolkit` — bash + Python scripts for first-minute IR triage on Linux hosts
**Blue Team Core**
- `windows-artifacts-walkthrough` — per-artifact deep dives (Prefetch, Amcache, ShimCache, UserAssist, event logs) with parsed samples from my own lab
- `pcap-investigations` — network forensics writeups from public pcap challenges
- `splunk-detection-lab` — local Splunk with the BOTS v3 dataset, my own SPL detections, MITRE ATT&CK mappings
**DFIR Skills**
- `memory-forensics-cases` — Volatility 3 walkthroughs on public memory samples
- `sherlocks-writeups` — HTB Sherlock investigations, methodology-focused (no spoilers)
- `ir-playbooks` — written IR procedures for ransomware, phishing, webshells, insider exfil, cloud sign-in anomalies
**Specialization**
- `malware-triage-lab` — static analysis writeups of safe samples from MalwareBazaar
- `cloud-forensics-aws` — CloudTrail-based investigations in an AWS free-tier lab
- `dfir-capstone-case` — a fully built end-to-end incident investigation with IR report and presentation deck
---
 
## Home Lab
 
A segmented, host-only lab where all the work above is done.
 
- **Analyst workstation:** Parrot OS
- **Windows target:** Windows 11 (Sysmon + PowerShell script-block logging + process auditing enabled)
- **Linux target:** Ubuntu Server
- **Platform:** MSI Cyborg 15 / VMware / host-only networking
- **Baselines captured:** running processes, listening sockets, SUID binaries, enabled services, Run keys
Full build documentation lives in the `dfir-home-lab` repo.
 
---
 
## Tools & Techniques
 
**Forensic toolkits:** Eric Zimmerman's Tools (EvtxECmd, PECmd, RECmd, MFTECmd, LECmd), Volatility 3, Autopsy, KAPE (learning)
 
**SIEM / detection:** Splunk, Sigma rules (reading), MITRE ATT&CK framework
 
**Network analysis:** Wireshark, Zeek (beginner), tcpdump
 
**Linux IR:** journalctl, grep/awk/sed pipelines, lsof, ss, systemd analysis, bash + Python scripting
 
**Windows IR:** Event Log analysis (4624, 4625, 4688, 7045, 1102), registry forensics, PowerShell for triage, Sysmon telemetry
 
**Environments:** Linux (Parrot, Ubuntu, Kali), Windows 10/11, AWS (free tier, in progress)
 
---
 
## Education
 
**BSc (Hons) Cybersecurity & Networks** — Metropolitan College, Greece, in partnership with **University of East London**, UK · currently enrolled
 
---
 
## Certifications
 
**Completed**
- Google Cybersecurity Professional Certificate
**Active goal**
- Blue Team Level 1 (BTL1) by Security Blue Team — my chosen first professional DFIR certification, targeting exam in 2026
I am deliberately not pursuing vendor-neutral fundamentals certifications (Security+, Network+, CEH) because they do not map to the DFIR work I want to do. My certification budget goes toward practical, scenario-based DFIR credentials: BTL1, and eventually GCFE / GCFA via an employer.
 
---
 
## Open to
 
Junior SOC Analyst · Junior DFIR Analyst · Incident Response Intern · Blue Team roles across the EU (remote, hybrid, or on-site). Open to relocation.
 
---
 
## Contact
 
- **LinkedIn:** [tasos-giannoulis](https://www.linkedin.com/in/tasos-giannoulis/)
- **Email:** *(add your professional email here before publishing)*
---
 
<sub>Everything in my repositories is original work, done in my own lab, written in my own words. I use AI as a tutor and sparring partner — never as a ghostwriter for anything that gets published.</sub>
