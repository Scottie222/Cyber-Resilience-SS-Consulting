# SS-Consulting Cyber Resilience Assessment — Results & Evidence

## Insider Threat Risk Summary

| Threat Vector | Likelihood | Impact | Control Status |
|--------------|-----------|--------|---------------|
| AI-generated phishing | High | Critical | PARTIAL — no AI-specific training |
| Deepfake executive impersonation | Medium | Critical | FAIL — no detection capability |
| Compromised vendor account | Medium | High | PARTIAL — limited monitoring |
| Credential theft via social engineering | High | High | PARTIAL — basic awareness only |
| Lateral movement post-compromise | Medium | Critical | FAIL — no SIEM |

---

## ISO 27001 Control Assessment

| Control | Requirement | Status | Gap |
|---------|------------|--------|-----|
| A.7.2.2 | Security awareness training | PARTIAL | No AI impersonation scenarios |
| A.9.2.1 | User registration & de-registration | PARTIAL | Orphaned accounts present |
| A.9.2.3 | Privileged access management | FAIL | Excessive permissions in place |
| A.12.4.1 | Event logging & monitoring | PARTIAL | Logs exist — no automated analysis |
| A.16.1 | Incident management | PARTIAL | Plan exists — not tested for insider threats |

---

## NIST CSF 2.0 Function Gaps

| Function | Finding | Recommendation |
|----------|---------|---------------|
| Protect — PR.AC | MFA not enforced for all accounts | Enforce MFA across all systems |
| Protect — PR.AT | Training lacks AI threat scenarios | Add deepfake and AI phishing modules |
| Detect — DE.CM | No SIEM or anomaly detection | Deploy SIEM with insider threat rules |
| Respond — RS.RP | IR plan not tested for insider scenarios | Conduct insider threat tabletop |
| Recover — RC.RP | Recovery not linked to IR lifecycle | Integrate recovery with IR plan |

---

## Simulated Phishing Exercise Results

| Scenario | Click Rate | Reported | Outcome |
|---------|-----------|----------|---------|
| Standard phishing email | 28% | 12% | High risk |
| AI-generated executive email | 41% | 6% | Critical risk |
| Deepfake voice note | 35% | 4% | Critical risk |

> These are simulated results for portfolio demonstration purposes.

---

## Risk Priority Matrix

| Risk | Priority | Action | Timeline |
|------|---------|--------|----------|
| AI phishing — no detection | P1 | Deploy AI-aware email filtering | 0–30 days |
| Excessive privileges | P1 | RBAC review and least privilege | 0–30 days |
| No SIEM | P1 | Deploy SIEM with insider rules | 30–60 days |
| Untested IR plan | P2 | Tabletop exercise | 30–60 days |
| Vendor monitoring gaps | P2 | Enforce vendor access reviews | 60–90 days |

---

## Conclusion

SS-Consulting faces elevated insider threat risk primarily due to human factors —
AI-generated phishing and deepfake impersonation represent emerging threats
that current training programs do not address. Implementing SIEM, enforcing
least privilege, and updating awareness training to cover AI threats would
significantly reduce the organisation's risk exposure within 90 days.
