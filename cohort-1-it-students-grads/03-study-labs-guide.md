# Cohort 1 - 03 - 90-Day Study & Lab Guide – IT Students / Grads

Assume ~7–10 hours/week. Adjust up/down as needed.

## Days 1–30 – Foundations & Exposure

### Study (3–5 hrs/week)
- Networking fundamentals (TCP/IP, ports, OSI model, basic routing/switching).
- Security fundamentals (CIA triad, common attacks, basic controls).
- Operating systems basics (Windows + Linux CLI).

Suggested resources (pick 1 per topic):
- Networking: Free CCNA/Network+ style playlists (e.g., Bombal / NetworkChuck / Messer).
- Security basics: Any Security+‑style free course or playlist.[
- Linux: Beginner Linux tutorials (Ryan’s Tutorials / equivalent).

### Labs (3–5 hrs/week)
Goal: Touch real systems and tools.

- Set up a small lab:
  - Hypervisor (VirtualBox/VMware) + 1 Linux VM + 1 Windows VM.
- Networking:
  - Use `ping`, `traceroute`, `nslookup`, `netstat` between your lab VMs.
- Security platforms:
  - Do 5–10 beginner blue‑team / general cyber labs (TryHackMe “Intro” / HTB beginner tracks).

Checklist by day 30:
- [ ] Lab environment with at least 2 VMs.
- [ ] Completed at least 8–10 beginner labs.
- [ ] One page of notes on networking and security basics.

---

## Days 31–60 – Core Blue-Team Skills

### Study (3–5 hrs/week)
- Logs & SIEM basics: event types, log sources, correlation ideas.
- Intro incident response: phases, basic playbooks, common IOCs.
- Basic scripting: Python or PowerShell for simple parsing/automation.

Suggested resources:
- Blue-team / SOC fundamentals articles/roadmaps.
- Beginner Python for security playlists or interactive course.

### Labs (4–6 hrs/week)
Goal: Work with logs and alerts.

- Logging lab:
  - Enable logging on your VMs (Windows Event Log, Linux syslog).
  - Forward to a lightweight stack (e.g., local ELK / Splunk free / Graylog) if you can.
- SIEM-style practice:
  - Use free SOC / SIEM labs (e.g., HTB Academy “SOC / SIEM” style modules, Blue‑team ranges).
- Scripting:
  - Write a simple script that:
    - Reads a log file.
    - Filters failed logins.
    - Prints counts by username/IP.

Checklist by day 60:
- [ ] Have run basic queries in at least one SIEM‑like tool.
- [ ] Script that parses logs or automates a tiny analysis task.
- [ ] Short writeup describing one “incident” you simulated and how you saw it in logs.

---

## Days 61–90 – Projects & Portfolio

### Study (3–4 hrs/week)
- MITRE ATT&CK basics for defenders.[web:51]
- Cloud fundamentals (AWS/Azure/GCP security overview).
- Light touch on your preferred niche: SOC, DFIR, cloud, etc.

### Labs (4–6 hrs/week)
Goal: Produce 1–2 showable artifacts.

Pick 1–2 project tracks:

**Track A – Mini SOC lab**
- Expand your lab:
  - One “attacker” VM (Kali) and one “victim” VM.
- Simulate 2–3 simple attacks (e.g., brute‑force, basic web scan) within your lab.
- Capture and analyze:
  - Show which logs and alerts fired, with screenshots and notes.

**Track B – Cloud‑focused**
- Free tier cloud account.
- Enable basic logging (CloudTrail / activity logs, security center).
- Create:
  - One insecure configuration.
  - One improved/hardened variant.
- Capture the logs and write a short explanation.

Checklist by day 90:
- [ ] At least one documented mini‑project in GitHub or a portfolio doc.
- [ ] Clear evidence of working with logs, alerts, and basic triage.
- [ ] Notes on what you want to go deeper on next (SOC, DFIR, cloud, etc.).
