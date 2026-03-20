# 03 - Cohort 3 - Study Labs and Guides - IT Professionals 

Ref: https://github.com/farhanashrafdev/90DaysOfCyberSecurity

Assume ~5–8 hours/week, with emphasis on using your current stack.

## Days 1–30 – Observe, Document, Learn

### Study (2–3 hrs/week)
- Refresh on:
  - Networking and OS security in the context of what you manage.[
- Read about blue‑team fundamentals and SOC workflows.[

### Labs (3–5 hrs/week)
Goal: Turn your current environment into a “lab”, plus a small home/sandbox.

At work (where allowed):
- Map:
  - Where logs come from.
  - What monitoring/alerting/SIEM tools are used.
  - How incidents are handled.

At home:
- Create a simplified mirror:
  - One VM that looks like a common server/workstation you use.
  - Enable logging and remote access similar to your day job.

Hands‑on:
- Use native tools or a free SIEM to ingest some home‑lab logs.
- Run basic queries that answer:
  - Who logged in?
  - From where?
  - What processes ran?

Checklist by day 30:
- [ ] Map of your org’s logging and incident flows (high level).
- [ ] Home lab that mirrors at least one work‑like system.
- [ ] Comfort running a few basic log queries.

---

## Days 31–60 – Security-Flavoured Projects in Your Context

Pick the track closest to your role (you can mix).

### Track A – Helpdesk / Sysadmin

Study (2–3 hrs/week):
- Hardening guides for OS you support.
- Patch/vulnerability management basics.

Labs (3–5 hrs/week):
- At work (if allowed) or in lab:
  - Baseline a system: what services, what ports, what logs.
  - Apply hardening steps (e.g., disable legacy protocols, tighten RDP/SSH, logging).
- Simulate:
  - A simple misuse/attack (e.g., repeated failed logins, basic scan).
  - Confirm that:
    - You see it in logs.
    - You can create an alert or report for it.

Outputs:
- Before/after documentation for one system’s hardening.
- A small “playbook” for one common issue (e.g., account compromise suspicion).

### Track B – Developer / DevOps

Study (2–3 hrs/week):
- Secure coding basics and OWASP Top 10 at high level.
- CI/CD security basics (secrets, dependency scanning).

Labs (3–5 hrs/week):
- Take a sample app or demo service:
  - Add logging around auth, errors, and security‑relevant events.
- In CI/CD (even a local pipeline):
  - Add simple security checks (SAST, dependency scanning, linting).
- Capture:
  - One “bug” or misconfiguration you found and fixed.

Outputs:
- Short doc: “Security improvements I added to <app/pipeline> and why they matter.”

### Track C – Cloud / Platform

Study (2–3 hrs/week):
- Provider security basics: IAM, logging, network security.
- Best practices for your cloud stack.

Labs (3–5 hrs/week):
- Use a sandbox account:
  - Build a minimal environment similar to something at work.
  - Turn on logging and a native security center.
- Introduce 2–3 misconfigurations (e.g., open ports, permissive roles).
- Fix them and record:
  - How they showed up in logs or security findings.
  - What policy/guardrail you’d recommend.

Outputs:
- Mini “security review” of the sandbox: findings + remediations.

Checklist by day 60:
- [ ] At least one meaningful security‑oriented project tied to your existing skills.
- [ ] Evidence of using logs/monitoring or pipelines in a security‑aware way.
- [ ] One or more short internal writeups or diagrams.

---

## Days 61–90 – Ownership & Next-Step Positioning

### Study (2–3 hrs/week)
- Explore more advanced blue‑team topics that align with your path:
  - Detection engineering, automation, or deeper cloud/AppSec.
- Read one 90‑day SOC/defender roadmap to benchmark yourself.

### Labs (3–5 hrs/week)
Goal: Own a repeatable slice of security work.

- Choose one domain from your previous work (patching, logging, app security, cloud account hygiene, etc.).
- Define:
  - A small “service” you will own for 4–6 weeks (e.g., monthly patch review, dashboards, pipeline security checks).
- Implement:
  - Docs or runbooks.
  - Basic metrics (e.g., open vulns over time, failed logins, pipeline scan results).
- Optionally:
  - Automate a small part (script, scheduled query, or CI/CD step).

Outputs by day 90:
- [ ] Documented “mini security domain” you own (what it is, what you do, how it helps).
- [ ] A short deck or one‑pager you could show a security hiring manager.
- [ ] Notes on next 6–12 months: what role you’re targeting and what to learn next.

