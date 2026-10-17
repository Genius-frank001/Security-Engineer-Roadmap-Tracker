# Security Engineering Roadmap: My Learning Journey

I'm moving into a Security Engineer / AppSec role. This repo tracks my progress through a structured 24-month roadmap, using free resources only (with a few flagged exceptions).

**Live tracker:** https://genius-frank001.github.io/Security-Engineer-Roadmap-Tracker/

## About the roadmap

The roadmap has 69 modules (about 1,007 hours) across six phases, plus a continuous leadership and consulting track. The approach is *break it, then fix it*: attack a system, then write the control that stops the attack.

| Phase | Months | Focus |
|---|---|---|
| 1 | 1-4 | Advanced AppSec: business logic, access control, OAuth, JWT, APIs, GraphQL, gRPC, Semgrep, threat modeling |
| 2 | 4-9 | DevSecOps: CI/CD attacks, secrets, containers, Kubernetes, infrastructure-as-code |
| 3 | 9-13 | Cloud security: AWS first, then Azure, GCP optional |
| 4 | 13-16 | Mobile security: Android, iOS optional |
| 5 | 16-21 | AI engineering: Python, ML, neural networks, transformers, RAG agents |
| 6 | 21-24 | AI security: LLM Top 10, prompt injection, jailbreaks, agent attacks |
| Continuous | 1-24 | Frameworks, risk, reporting, communication |

## How progress is measured

A module counts as **Gate cleared** only when all three are true:

1. I can run the attack unaided.
2. I can name the exact control that stops it.
3. I can write a clear finding with impact and remediation.

Two out of three stays *In progress*.

## How I track it

- **Dashboard:** gates cleared, hours cleared, progress per phase, and a module table with status and notes.
- **Activity log:** dated entries with hours and what I worked on.
- **Write-ups:** every module ends with something written. If it isn't written, it didn't happen.

The tracker page is updated after each study session or at least weekly.

## Weekly rhythm

| Slot | Time | Purpose |
|---|---|---|
| Tue and Thu | 2 x 1.5 hrs | Theory and reading |
| Wednesday | 1.5 hrs | Small hands-on lab |
| Saturday | 4 hrs | Deep block |
| Sunday | 1.5 hrs | Write-up and review |

## Main resources

- **Phase 1:** PortSwigger Web Security Academy, OWASP crAPI, OWASP ASVS and WSTG, Semgrep, Threat Dragon
- **Phase 2:** CI/CD Goat, Kubernetes Goat, GitHub Actions Goat, Trivy, Falco, Kyverno
- **Phase 3:** flaws.cloud, CloudGoat, IAM Vulnerable, Prowler
- **Phase 4:** OWASP MASTG, InsecureBankv2, Frida
- **Phases 5-6:** Karpathy's Zero to Hero, Hugging Face courses, OWASP Top 10 for LLM Apps, Garak, PyRIT

Not free: CISSP/CISM/CISA exams (about $600-760 each). Cloud labs deploy into my own AWS account, so I set billing alerts and destroy resources after every session.

## Repo contents

| File | What it is |
|---|---|
| `index.html` | The tracker page, served through GitHub Pages |
| `README.md` | This file |

## Updating the tracker

1. Open the live tracker and click **Edit as owner**.
2. Update statuses, notes and log entries.
3. Click **Download updated page**.
4. Upload the new `index.html` to this repo to replace the old one.

## Credits

The roadmap is adapted from a Security Engineering Mastery Tracker. All lab platforms and learning resources belong to their respective authors.
