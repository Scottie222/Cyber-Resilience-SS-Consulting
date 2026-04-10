# SS-Consulting — Insider Threat Simulation & Assessment
## ISO 27001:2022 | NIST CSF 2.0 | AI Phishing & Deepfake Scenario | Johannesburg, ZA

![Status](https://img.shields.io/badge/Status-Live-brightgreen)
![NIST CSF](https://img.shields.io/badge/NIST-CSF%202.0-blue)
![ISO 27001](https://img.shields.io/badge/ISO-27001:2022-teal)
![Threat](https://img.shields.io/badge/Threat-Insider%20Attack-red)

## Live Interactive Simulation

**[scottie222.github.io/Cyber-Resilience-SS-Consulting](https://scottie222.github.io/Cyber-Resilience-SS-Consulting/)**

No install. No login. Play through the insider threat incident as SOC analyst — your decisions determine the outcome.

---

## What Makes This Different

Most GRC portfolio projects are static documents. This one is playable.

A recruiter can sit at the SOC console, make real incident response decisions across 5 attack phases, watch ISO 27001 controls flip from FAIL to PASS in real time, and receive a scored debrief at the end. Built around a real SA cybersecurity firm — SS-Consulting (Pty) Ltd — and grounded in actual insider threat patterns.

---

## The Scenario

SS-Consulting integrates cloud platforms, SaaS tools and third-party vendors into its consulting operations. An attacker targets a finance employee using AI-generated phishing and deepfake CEO impersonation:

- **Day 1** — AI-generated phishing email with deepfake voice note sent to finance team
- **Day 2** — Credentials harvested. No MFA. VPN access gained in 4 minutes.
- **Days 1-18** — Lateral movement across 12 network shares. No SIEM. Undetected.
- **Day 18** — 2.3GB exfiltrated. Discovered via external dark web intelligence.
- **Day 19** — Incident declared. IR plan untested. Chaotic response.
- **Day 21** — This assessment commissioned.

**Root causes:** No MFA (A.8.5) · No SIEM (A.8.16) · No awareness training (A.6.3) · Untested IR plan (A.5.24)

---

## Dashboard Features

| Tab | What It Shows |
|---|---|
| **Live Simulation** | 5-phase playable SOC incident — make decisions, get scored, see ISO controls update live |
| **Overview** | Full breach timeline, root cause analysis, pre-breach NIST maturity |
| **Attack Path** | Interactive MITRE-aligned kill chain — click each phase for detail |
| **Risk Matrix** | Clickable heat map — likelihood x impact with ISO control references |
| **Controls** | 10 control failures mapped to ISO 27001 clause and NIST CSF function |
| **NIST CSF** | 6-function maturity comparison — current vs 90-day target |
| **Remediation** | 3-phase 90-day roadmap with maturity progression table |

---

## NIST CSF 2.0 Maturity

| Function | Pre-Breach | 90-Day Target |
|---|---|---|
| GV — Govern | 1.0 | 3.0 |
| ID — Identify | 1.5 | 2.5 |
| PR — Protect | 1.0 | 3.5 |
| DE — Detect | 0.5 | 3.0 |
| RS — Respond | 1.0 | 2.5 |
| RC — Recover | 1.5 | 2.5 |

---

## Key Control Failures

| Control | ISO 27001 | NIST CSF | Severity |
|---|---|---|---|
| No phishing / deepfake awareness training | A.6.3 | PR.AT | Critical |
| No MFA on VPN or internal systems | A.8.5 | PR.AC | Critical |
| No SIEM or centralised logging | A.8.16 | DE.CM | Critical |
| Incident response plan untested | A.5.24 | RS.RP | Critical |
| No privileged access management | A.9.2.3 | PR.AC | Critical |
| No vendor risk assessments | A.5.19 | ID.SC | High |
| No data classification framework | A.5.12 | PR.DS | High |

---

## Files in This Repo

| File | Description |
|---|---|
| `index.html` | Full interactive simulation dashboard — live on GitHub Pages |
| `README.md` | This file |
| `RESULTS.md` | Detailed written assessment — ISO 27001 and NIST CSF findings |
| `SS-Consulting-Cybersecurity-Challenge-for-SANCS26-Insider.pdf` | Original challenge brief |

---

## Related GRC Portfolio Projects

| Project | Description |
|---|---|
| [TechCorp-Resilience-Assessment](https://github.com/Scottie222/TechCorp-Resilience-Assessment) | Post-breach ransomware assessment — NIST CSF 2.0 live dashboard |
| [StandardBank-Risk-Assessment](https://github.com/Scottie222/StandardBank-Risk-Assessment) | ISO 27001 Risk Assessment — live dashboard |
| [RetailCo-Security-Awareness](https://github.com/Scottie222/RetailCo-Security-Awareness) | Security Awareness + AI Detector — live dashboard |
| [CloudSec-Assessment-SA](https://github.com/Scottie222/CloudSec-Assessment-SA) | Cloud Security — CIS Benchmarks AWS and Azure |
| [LifeHealthcare-BCP](https://github.com/Scottie222/LifeHealthcare-BCP) | BCP/DR — Life Healthcare ransomware 2020 |

---

*Built by Bakithi Scott Ngcampalala | Junior Security Administrator @ Open Vantage*
*LinkedIn: https://www.linkedin.com/in/bakithi-scott-ngcampalala-0051a4105*