# Walter Lewis

Security leader and hands-on engineer. CISSP. 25+ years across healthcare SaaS, global retail, genomics research and U.S. Air Force offensive and defensive cyber operations.

I build security programs from the ground up: security operations and MDR, detection and threat hunting, vulnerability management, data protection, incident response and third-party risk, mostly across Microsoft 365, Azure and AWS. I use automation and AI (Claude skills and agents) to take the manual work out of security reviews.

## Projects

| Repo | What it is |
|---|---|
| [sentinel-detections](https://github.com/jasaan/sentinel-detections) | 79 Microsoft Sentinel detections and 16 threat hunts across Entra ID, Microsoft 365, Azure, AWS, Defender for Endpoint and Active Directory, mapped to 84 ATT&CK techniques. Every rule ships with sample logs, a self-checking KQL test (95/95 pass) and tuning and triage steps; one-click ARM deployment. |
| [packed-binary-triage](https://github.com/jasaan/packed-binary-triage) | Explainable static triage of Windows executables for packers, crypters and protectors (MITRE T1027.002): eight structural checks with a reason for every point, matching YARA rules, and a Defender for Endpoint hunt to find candidates. Tested on inert synthetic samples. |
| [purview-autolabel-workbench](https://github.com/jasaan/purview-autolabel-workbench) | Measures whether a Microsoft Purview auto-labeling policy is accurate *before* you turn it on: data owners review their own files without Purview roles, and the report gives precision, go/no-go, recall against a truth set and tuning commands. |
| [claude-security-skills](https://github.com/jasaan/claude-security-skills) | Claude skills and an agent for first-pass vendor security reviews (SOC 2, questionnaires, risk tiering, NIST and ISO mapping), with a built-in skeptic that challenges the evidence. Evals included. |
| [m365-azure-posture-check](https://github.com/jasaan/m365-azure-posture-check) | Read-only Microsoft 365 and Entra ID posture check over Microsoft Graph: MFA, legacy auth, admin sprawl, app consent, guests. Findings come with evidence, fixes and CIS/NIST/ISO references. |
| [aws-security-baseline](https://github.com/jasaan/aws-security-baseline) | Terraform modules for a secure AWS account baseline: log archive, CloudTrail, GuardDuty, Security Hub, Config, guardrails and alerts. Mapped to CIS v3.0, NIST CSF 2.0 and ISO 27001; Checkov in CI. |

Each repo runs its tests in CI on fictional sample data. Nothing here comes from an employer.

## Focus areas

Security operations · Microsoft Sentinel and KQL · detection engineering · malware triage and YARA · Defender XDR · Entra ID and Zero Trust · Microsoft Purview (labels, DLP, auto-labeling) · AWS and Azure security · vulnerability management · third-party risk · HIPAA, SOC 2, HITRUST, NIST, ISO 27001 · Python, PowerShell, Terraform · Claude skills and agents

Built with Claude; designed, reviewed and tested by me.
