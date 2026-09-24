# Marcus de Paula

## Security & Infrastructure Engineer | IAM | Endpoint Security | PowerShell Automation | Security Operations | Ireland

**IT Operations · Infrastructure · IAM · Endpoint Security · PowerShell · Security Operations**

> I build reliable IT operations and turn recurring support problems into documented, secure and repeatable processes.

Enterprise IT operations and infrastructure experience, complemented by hands-on security engineering labs in identity automation, Windows detection and incident response.

Irish and Italian citizen with unrestricted right to work in Ireland. Available for Ireland-based and remote opportunities.

[LinkedIn](https://www.linkedin.com/in/marcuspaula/) · [GitHub](https://github.com/marcuspaula-seceng)

---

## Professional profile

My experience follows one connected path:

**IT operations → infrastructure engineering → identity and endpoint security → security operations**

I started with frontline support and workplace technology, then progressed into infrastructure ownership, lifecycle operations, technical escalation, documentation and automation. My current direction combines that operational background with security engineering: IAM, endpoint controls, PowerShell automation, detection and incident response.

---

## Core capabilities

| Area | What I work with |
|---|---|
| **IT operations** | Incident triage, request fulfilment, escalation, operational documentation, vendor coordination and service continuity |
| **Workplace technology** | Windows and macOS endpoints, mobile devices, meeting-room technology, remote support and user enablement |
| **Infrastructure support** | Endpoint deployment, connectivity, VPN and remote access, systems troubleshooting and change discipline |
| **Windows endpoint administration** | Endpoint configuration, imaging and deployment workflows, encryption and recovery processes |
| **Identity and access** | Joiner/mover/leaver workflows, access reviews, least privilege, account lifecycle and authorised data transfer |
| **Endpoint security** | Secure configuration, device lifecycle controls, operational hardening and investigation support |
| **Automation** | PowerShell, Bash and Python for repeatable administration, validation and reporting |
| **Security operations** | Evidence-led triage, root-cause analysis, containment planning, escalation and remediation runbooks |
| **SOC / DFIR development** | Windows event analysis, detection logic, chain of custody and incident-response methodology |

---

## Enterprise IT operations — EMEA

### TikTok Technology Ireland — IT Support Engineer

Supported workplace technology and IT operations in Dublin within a global technology environment. The work included:

- Supporting Windows, macOS, mobile devices, monitors and collaboration technology.
- Managing device deployment, replacement, collection and employee offboarding activities.
- Supporting Apple Business Manager enrolment and Apple device lifecycle processes.
- Supported Microsoft BitLocker Administration and Monitoring (MBAM), BitLocker encryption, recovery and compliance workflows for Windows endpoints.
- Built and maintained Windows laptop imaging workflows and an imaging/deployment server.
- Supporting account access, collaboration platforms and remote troubleshooting.
- Coordinating secure data-ownership transfer during offboarding, with authorisation checked before action.
- Handling incidents, service requests and structured escalation across distributed teams.
- Coordinating equipment logistics with employees, couriers, vendors and internal stakeholders.
- Supporting physical-access processes and workplace technology.
- Creating reusable procedures and communication templates for operational consistency.
- Sharing process knowledge with colleagues and helping improve repeatability.

This section describes professional responsibilities at a capability level. It deliberately excludes internal metrics, screenshots, ticket content, personal data, system topology and confidential operational details.

---

## Infrastructure and engineering approach

I treat reliable operations as the foundation of security:

1. **Stabilise the service** — restore access, connectivity or endpoint function.
2. **Establish the cause** — separate symptoms from identity, endpoint, network and process failures.
3. **Control the change** — use documented, reversible steps with clear ownership.
4. **Prevent recurrence** — convert repeated work into runbooks, validation or automation.
5. **Preserve evidence** — record decisions and technical facts without exposing sensitive data.

---

## Featured projects

Three laboratories where every claim ships with the script that produced it, the raw output, a test suite and a statement of what it does *not* prove. All data is synthetic; none of it ran in any employer's environment.

| Project | Problem | What I built | How to verify |
|---|---|---|---|
| [**llm-agent-security-lab**](https://github.com/marcuspaula-seceng/llm-agent-security-lab) | Does a system prompt protect a secret? Does an agent with tools obey a poisoned file? | Measured attacks against a local LLM (5/5 leaked → 1/5 with a hardened prompt → 0/5 with the secret out of context; agent tool-abuse 2/2 → 0/2 with a code guard) and the two guards that came out of it | `python -m unittest discover -s tests` · CI on every push · raw outputs committed unedited |
| [**it-ops-ai-cyber-lab**](https://github.com/marcuspaula-seceng/it-ops-ai-cyber-lab) | IT-operations processes I ran — imaging validation, asset audit, device return, MDM, meeting rooms — had no security layer and no safe way to use AI | Read-only PowerShell and Python modules with security gates (`Unknown ≠ Pass`, `-WhatIf` proven) and a local model that ranks findings behind validators for commands, intent, invented identifiers and numbers | `python -m unittest discover` per module (35, in CI) · Pester 3.4 locally (62) · limits of the guards documented |
| [**sentinel-detection-lab**](https://github.com/marcuspaula-seceng/sentinel-detection-lab) | Detection engineering for Microsoft Sentinel without a workspace | Four analytics rules in the community template format, a local evaluator for their KQL subset, 45 declared fixtures, a correlation case showing why three telemetry families do not join, an automation rule against the ARM schema | `python topicos/03-sentinel/tools/lab.py all` · CI on every push |

---

## Security engineering portfolio

My security work is separated clearly from employer experience. Every project listed below is public and independently built.

| Workstream | Status | Focus |
|---|---|---|
| [**Active Directory security automation**](https://github.com/marcuspaula-seceng/active-directory-automation) | Hands-on lab | Joiner/mover/leaver logic, access review, privileged-account and password-policy auditing |
| [**Windows detection engineering**](https://github.com/marcuspaula-seceng/windows-detection-engineering-lab) | Hands-on lab | Event-driven detection, fixtures, positive/negative testing and schema validation |
| [**Incident Response Playbooks**](https://github.com/marcuspaula-seceng/dfir-playbook) | Independent project | Evidence collection, chain of custody, triage, containment, remediation and lessons learned |
| [**IAM and Zero Trust Architecture**](https://github.com/marcuspaula-seceng/iam-zero-trust-architecture) | Independent project | Identity lifecycle, access governance, least privilege and operational controls |
| [**Cloud Threat Hunting Platform**](https://github.com/marcuspaula-seceng/cloud-threat-hunting-platform) | Independent project | Cloud logging, threat detection, investigation, automation and platform security |

Public case studies are released only after technical validation and confidentiality review. Private or unpublished repositories are not presented as publicly reviewable evidence.

---

## Tools and technologies

**Operations and infrastructure:** Windows · macOS · Linux · Active Directory · Google Workspace · VPN · remote support · ticketing systems · endpoint lifecycle

**Endpoint and encryption:** Windows imaging and deployment · Microsoft BitLocker Administration and Monitoring (MBAM) · BitLocker encryption and recovery workflows · device lifecycle controls

**Security and identity:** IAM · access governance · endpoint security · Windows Event Logs · incident response · evidence handling

**Automation and engineering:** PowerShell · Bash · Python · Git · GitHub Actions · Pester

**Currently developing:** Microsoft Defender for Endpoint · KQL · Microsoft Sentinel · Entra ID governance · cloud security engineering

Items under “currently developing” are study and lab areas, not claims of production experience.

---

## How work is classified

| Label | Meaning |
|---|---|
| **Professional experience** | Paid work performed as part of an employment role |
| **Independent project** | Work built on my own initiative |
| **Hands-on lab** | Controlled work in a self-built or synthetic environment |
| **Study** | Technology being learned but not yet demonstrated |
| **In progress** | Work that is not yet ready to be presented as complete |

The category is part of the evidence. A lab is not presented as production work, and a private repository is not presented as a public deliverable.

---

## Confidentiality and legal boundary

This public profile contains only sanitised, high-level professional information and independent technical work.

- No proprietary employer source code, internal documentation or system architecture is published.
- No internal screenshots, tickets, credentials, personal data or confidential metrics are published.
- Employer names identify employment history only and do not imply endorsement.
- Security demonstrations use synthetic, self-generated or appropriately licensed public data.
- Technical examples are reviewed for secrets, third-party data and employer attribution before publication.

---

## Current focus

Building demonstrable capability across:

- Windows detection engineering and incident-response methodology.
- IAM lifecycle and access-governance automation.
- Endpoint and infrastructure security.
- PowerShell automation with testing and safe failure behaviour.
- Security operations grounded in real IT operational discipline.
