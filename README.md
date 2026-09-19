# Marcus de Paula

**Security & Infrastructure Engineer**
IAM · Endpoint Security · PowerShell Automation · Security Operations · Ireland

> Hi, I'm Marcus — I secure identities, endpoints and infrastructure.

Extensive IT experience spanning technical support, infrastructure, enterprise operations,
identity, endpoint security and automation, with hands-on development of security automation,
IAM and incident-response capability.

Irish and Italian citizen with unrestricted right to work in Ireland.
Available for Ireland-based and remote opportunities.

[LinkedIn](https://www.linkedin.com/in/marcuspaula/) · [GitHub](https://github.com/marcuspaula-seceng)

---

## What I work on

| | |
|---|---|
| **Identity & access** | Joiner/mover/leaver automation, access review, privileged-account audit, group-membership change detection, least privilege |
| **Endpoint & remote access** | Endpoint configuration and deployment, VPN and remote access troubleshooting, Windows, macOS and Linux server estates |
| **Incident response** | Triage, systems-level root-cause analysis, evidence handling, containment, structured escalation |
| **Automation** | PowerShell with strict mode, parameter validation, `ShouldProcess` on destructive paths, Pester, GitHub Actions |
| **Detection engineering** | Windows event analysis, detection logic, true and false positive reasoning, schema validation |

---

## Featured projects

**[Active Directory Security Automation](https://github.com/marcuspaula-seceng/active-directory-automation)**
Identity lifecycle suite in PowerShell: joiner, mover and leaver flows, access review with
stale-account flagging, privileged-account audit, password-policy audit and group-membership
delta reporting. Directory logic is isolated so it can be tested deterministically with Pester 5,
with CI running under read-only workflow permissions.
*Laboratory build. Not executed against a production directory.*

**[Windows Incident Triage](https://github.com/marcuspaula-seceng/dfir-playbook)**
Incident-response playbook and live-triage tooling for Windows and Linux: collection ordered by
volatility, chain-of-custody templates, containment and remediation runbooks, following PICERL.
*Independent project using synthetic data and fictional scenarios.*

**[IAM Access Review Lab](https://github.com/marcuspaula-seceng/iam-zero-trust-architecture)**
Access architecture and review tooling across PowerShell, Bash and Python: identity lifecycle,
access governance, Zero Trust principles and operational controls.
*Independent project. Not connected to a production identity provider.*

**[Security Engineering Case Studies](https://github.com/marcuspaula-seceng/windows-detection-engineering-lab)**
Detection rules authored from real Windows event data, with fixtures, a declared true and false
positive matrix, and validation against an upstream JSON schema pinned by commit and hash.
*Hands-on lab. Public-domain source data with recorded checksums.*

The central hub is
**[marcuspaula-security-portfolio](https://github.com/marcuspaula-seceng/marcuspaula-security-portfolio)**.

---

## Technical timeline

**Phase 1 — Security baseline**
Windows infrastructure, endpoints, connectivity and account access, keeping a site running
without in-house IT. Later, enterprise operations across EMEA: incidents, escalation and the
documentation that makes an operation repeatable.

**Phase 2 — Investigation**
Becoming the escalation point for problems that had already failed elsewhere. Root-cause
analysis across identity, network, endpoint and server layers, and identifying the process gaps
that let an issue reach a user in the first place.

**Phase 3 — Automation and validation**
Rebuilding recurring work as PowerShell with tests and CI. Isolating dependencies so logic can
be verified without touching a live directory. Treating a green test suite as a claim to be
checked rather than a result to be trusted.

**Phase 4 — Outcome and lessons learned**
A publication gate that caught nine of eleven scripts failing to parse after I had read them and
judged them fine. A field truncation that kept an entire suite green while the rule never fired.
A validator that was itself the defect. Each one became a standing rule, and most of the controls
I build now exist to turn a silent success into a loud failure.

---

## How work is classified here

| Label | Meaning |
|---|---|
| **Professional Experience** | Paid work performed in role |
| **Independent Project** | Built on my own initiative |
| **Hands-on Lab** | Controlled exercise in a self-built environment |
| **Study Notes** | Being learned; not yet demonstrable |
| **In Progress** | Under active development |

Nothing moves category to look stronger. Where something has not been proven, it says so.

## Current focus

Windows detection engineering, incident-response methodology, and extending the PowerShell
automation suite with validation that fails loudly.

Microsoft security tooling — Defender for Endpoint, KQL, Sentinel and Entra ID governance — is
listed as **study**, not experience, and stays there until there is something to show.
