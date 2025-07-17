# Biograph Cybersecurity Planning Discussion

## 🌟 Vision

Enable Biograph to accelerate scientific and business innovation securely—by strengthening what works, advancing key capabilities, and protecting sensitive data with resilience and trust. This strategy builds incrementally on existing foundations, guided by real-world risks and practical execution.

## 🔁 From Conversation to Continuous Execution
This strategy framework is designed not just to diagnose gaps—but to spark momentum. By the end of this discussion, we will have identified:
* Specific risks and challenges across your security domains
* Practices that align to your culture, capabilities, and customer expectations
* Tangible actions—big or small—that can help move your program forward

We’ll take what we’ve uncovered together and shape it into a one-year security improvement plan that is:
* Domain-driven – Focused on 2–3 security domains where progress will have the highest impact
* Lens-aligned – Structured by the cross-functional realities of your organization (e.g., culture, measurement, execution)
* Actionable – Grounded in realistic next steps that reflect your current maturity and operating environment
* Measurable – Supported by simple metrics or milestones that show progress without creating noise

## 🔢 Strategic Framing: How We Approach the Security Discussion

Biograph’s cybersecurity strategy is structured around two complementary layers: **cross-functional lenses** and **core security domains**.

### 🎯 Lenses: What Drives Focus

These are the strategic dimensions we use to frame challenges and opportunities across all areas of security:

- **Risk Alignment** – Are we protecting what matters most, in ways that reflect Biograph’s customers and threats?
- **Culture** – How do behaviors, expectations, and norms influence security decisions and adoption?
- **Measurement** – How do we track progress, spot gaps, and make improvements visible?
- **Execution** – How effectively are we implementing security in practice?

These lenses help us **prioritize and focus**, ensuring that security efforts are not just technical but also aligned with real-world context—including the needs of:

- **High-net-worth individuals** who demand privacy, control, and trust
- **Research partners** who need reliable, auditable, collaborative access

### 🛠️ Domains: Where the Work Happens

The lenses are applied across seven core **security domains**, where specific improvements and initiatives take place:

- Identity & Access Management  
- Data Protection  
- Threat Detection & Response  
- Endpoint & Device Security  
- Application Security  
- Infrastructure & Network Security  
- Resilience & Continuity  

Each domain represents a distinct area of operational focus. As we review each, we use the lenses to guide discussion: What’s working? What’s risky? What’s cultural? What’s measurable? What’s executable?

### 🔍 Focus Questions

To help stakeholders engage meaningfully, we also ask:

- Where do you see the biggest opportunity for impact if we made security improvements?
- Which domain gets the most discussion or attention internally right now?
- If we made meaningful progress in one area, where would it ripple through most effectively?

### Identity & Access Management
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do our access controls reflect the expectations of high-net-worth clients for privacy and control, as well as the data-sharing needs of research partners? | How are identities managed in practice across teams and systems—and how much variation is there in how people access what they need? | Do we regularly audit access and track privilege creep? | How consistent and centralized is access control across your systems today—and how much of it depends on manual effort or tribal knowledge? |
| How mature is the process for requesting, approving, and tracking 3rd party access? |  |  |  |
| How well-defined and mature is our access control model (e.g., RBAC, ABAC, attribute inheritance)? |  |  |  |

</details>

<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Formalize criteria and workflows for assigning access based on business role, data sensitivity, and operational context | Identify access governance stakeholders | Identify audit gaps | Evaluate IAM maturity using NIST-aligned tiers |
| Centralize IAM  | Train users and admins on access hygiene and privilege minimization | Use nudges/gamification | Integrate into onboarding |
| 3rd-party penetration testing | Automate provisioning | Audit trails and provisioning error tracking<br>Visualize access flows | Translate customer expectations |
|  | Promote ownership and accountability for privileged access | Document ownership | Embed IAM in engineering conversations |
|  |  |  | Tag and audit privileged accounts |
|  |  |  | Assign ownership for provisioning integrity |
|  |  |  | Integrate metrics into reporting |


</details>

### Data Protection
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Are our practices aligned with data privacy, retention, and breach readiness standards? | Are teams aware of how to handle sensitive data in practice? | Do we know where sensitive data resides and flows? | Do we have tools for classification, DLP, and discovery? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| - Map to HIPAA/SOC2/contractual obligations<br>- Train teams using real examples<br>- Identify flows<br>- Use discovery/classification tools | - Align classification to contract data types<br>- Cheat sheets by role<br>- Classify high-risk data<br>- DLP aligned to workflows | - Flag exposure across third-party tools<br>- Normalize data minimization conversations<br>- Track near-miss incidents<br>- Build data maps with ownership tags | - Document breach readiness<br>- Flag unknown/ambiguous data use<br>- Generate heatmaps<br>- Inventory third-party access<br>- Promote ownership of data flows<br>- Tag/label sensitive cloud data |

</details>

### Threat Detection & Response
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do we meet internal and contractual expectations for detection and response timeframes? | Are IR plans tested and embraced across teams—or siloed to security? | Are alerts actionable and outcomes tracked (MTTD, MTTR)? | Do we operate SIEM/XDR or rely on MDR, and is it effective? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| - Review IR obligations<br>- Run tabletop scenarios<br>- Track alert/resolution trends<br>- Build triage playbooks | - Validate breach workflows<br>- Identify cross-functional responders<br>- Log detection-to-resolution timelines<br>- Validate tooling | - Confirm policies for regulated environments<br>- Clarify communication plans<br>- Audit missed alerts quarterly<br>- Consider MDR | - Audit logs for defensibility<br>- Assign expectations pre/during/post-incident<br>- Report IR metrics<br>- Tune detection logic<br>- Retention alignment<br>- Include IR in onboarding<br>- Distinguish noise vs. signal<br>- Assign IR ownership |

</details>

### Endpoint & Device Security
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do we meet baseline standards for EDR, encryption, and configuration in regulated environments? | Do employees and contractors understand endpoint risks and acceptable use? | Can we monitor device compliance and policy status continuously? | Can we patch and configure devices at scale across environments? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| - Align controls to classification tiers<br>- Awareness training by persona<br>- Patch lag and coverage<br>- EDR rollout by user type | - Confirm with auditors<br>- Set policy norms<br>- Detect config drift<br>- Enforce MDM/config baselines | - Track device lifecycle<br>- Assign accountability<br>- Compare EDR by team<br>- Automate patching | - Flag gaps between environments<br>- Campaigns on threats<br>- Build dashboards<br>- Inventory unmanaged devices<br>- Show endpoint threat resilience<br>- Gamify patching<br>- Address BYOD risk |

</details>

### Application Security
<details>
<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| How well does our current application security approach reflect the kinds of risks the business actually cares about? | When engineering teams move fast, how does security stay involved—if at all—across design, coding, review, and deployment? | How do you measure the effectiveness of application security today—if at all? | What parts of application security are currently automated or repeatable—and what still depends on manual effort or one-off reviews? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| - Map controls to trust/delivery needs<br>- CI/CD reviews<br>- Track pre-release findings<br>- Add SAST to CI/CD | - Tier by app/data sensitivity<br>- Security champions<br>- Time-to-fix by severity<br>- Bug bounty program | - Align threat modeling to business features<br>- Threat modeling checklists<br>- Escape rate<br>- Clarify ownership | - Show security during customer reviews<br>- Secure coding standards<br>- Tag security items in backlog<br>- Automate secrets/dependency scans<br>- Embed AppSec in product planning<br>- Secrets remediation sprint<br>- Monthly AppSec reporting<br>- Secure code review playbooks |

</details>

### Resilience & Continuity

<details>
<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do our recovery and continuity practices meet internal SLAs and any contractual or regulatory obligations? | Are continuity plans documented and rehearsed beyond just the IT team? | Are RTO/RPO metrics tracked and reported for key services? | Do we have a reliable and tested recovery process for critical systems? |

</details>
<details>

<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| - Align DR to SLAs<br>- Cross-team training<br>- Backup coverage<br>- Backup/DR inventory | - Validate vendors<br>- Simulate system loss<br>- RTO/RPO tracking<br>- Automate testing | - Include plans in due diligence<br>- Define restore ownership<br>- Dependency mapping<br>- Write top-system runbooks | - Demonstrate audit readiness<br>- Document dependencies<br>- Test logs<br>- Assign metric owners<br>- Risk exceptions flagged<br>- Include in onboarding<br>- Gap visualization<br>- Snapshot/rollback tooling |

</details>

## 🧱 IAM Tiering Model (NIST-Aligned)

| Tier | Description | IAM Characteristics |
|------|-------------|----------------------|
| **Tier 1: Partial** | Ad hoc, undocumented, reactive | - Shared admin accounts<br>- No formal provisioning<br>- Local identities unmanaged<br>- No access reviews |
| **Tier 2: Risk-Informed** | Some policies exist; inconsistent enforcement | - MFA on some systems<br>- Manual provisioning/deprovisioning<br>- Periodic reviews (when triggered)<br>- Roles defined but not consistently applied |
| **Tier 3: Repeatable** | Documented policies; consistent application | - Role-based access across most systems<br>- Joiner/mover/leaver process<br>- Quarterly access reviews<br>- Admin rights scoped and logged |
| **Tier 4: Adaptive** | Dynamic, automated, metrics-driven | - Attribute-based access (ABAC) or centralized RBAC<br>- Just-in-time admin access<br>- Automated user lifecycle with audit hooks<br>- Real-time risk-based access controls |
