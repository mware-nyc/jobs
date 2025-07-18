# Biograph Cybersecurity Planning Discussion

## 🌟 Vision

Enable Biograph to accelerate scientific and business innovation securely—by strengthening what works, advancing key capabilities, and protecting sensitive data with resilience and trust. This strategy builds incrementally on existing foundations, guided by real-world risks and practical execution.

## 🔁 From Conversation to Continuous Execution
This strategy framework is designed to provided a basis for prioritizing the contiunous execution of security priorities. By the end of this discussion, we will have identified:
* Potention opportunities and challenges across your security domains
* Practices that align to your culture, capabilities, and customer expectations
* Tangible actions—big or small—that can strengthen your current program 

Vetting and refining what is discussed here with stakeholders across the organization, security planning and execution will be:
* Domain-driven – Focused on highest priority security domains where progress will have the highest impact
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

Each domain represents a distinct area of operational focus. Applying the lenses we'll uncover: What’s working? What’s risky? What’s cultural? What’s measurable? What’s executable?

### 🔍 Focus Questions

To start, some questions to consider against the above domains:

- Where do you see the biggest opportunity for impact if we made security improvements?
- Which domain gets the most discussion or attention internally right now?
- If we made meaningful progress in one area, where would it ripple through most effectively?

### Identity & Access Management
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do our access controls reflect the expectations of high-net-worth clients for privacy and control, as well as the data-sharing needs of research partners? | How are identities managed in practice across teams and systems—and how much variation is there in how people access what they need? | Do we regularly audit access and track privilege creep? | How consistent and centralized is access control across your systems today—and how much of it depends on manual effort or tribal knowledge? |
| How mature is the process for requesting, approving, and tracking 3rd party access? | What is our risk appetite for malicious employee activity? | Is there a central location tracking all roles and access? | What is our confidence that former employees do not have access to any system? |
| How well-defined and mature is our access control model (e.g., RBAC, ABAC, attribute inheritance)? |  | How long would it take to determine the blast radius of a successful employee ATO (account takeover)? |  |


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
| Map to HIPAA/SOC2/contractual obligations | Align classification to contract data types | Flag exposure across third-party tools | Document breach readiness |
| Train teams using real examples | Cheat sheets by role | Normalize data minimization conversations | Flag unknown/ambiguous data use |
| Identify flows | Classify high-risk data | Track near-miss incidents | Generate heatmaps |
| Use discovery/classification tools | DLP aligned to workflows | Build data maps with ownership tags | Inventory third-party access |
|  |  |  | Promote ownership of data flows |
|  |  |  | Tag/label sensitive cloud data |


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
| Review IR obligations | Validate breach workflows | Confirm policies for regulated environments | Audit logs for defensibility |
| Run tabletop scenarios | Identify cross-functional responders | Clarify communication plans | Assign expectations pre/during/post-incident |
| Track alert/resolution trends | Log detection-to-resolution timelines | Audit missed alerts quarterly | Report IR metrics |
| Build triage playbooks | Validate tooling | Consider MDR | Tune detection logic |
|  |  |  | Retention alignment |
|  |  |  | Include IR in onboarding |
|  |  |  | Distinguish noise vs. signal |
|  |  |  | Assign IR ownership |

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
| Align controls to classification tiers | Confirm with auditors | Track device lifecycle | Flag gaps between environments |
| Awareness training by persona | Set policy norms | Assign accountability | Campaigns on threats |
| Patch lag and coverage | Detect config drift | Compare EDR by team | Build dashboards |
| EDR rollout by user type | Enforce MDM/config baselines | Automate patching | Inventory unmanaged devices |
|  |  |  | Show endpoint threat resilience |
|  |  |  | Gamify patching |
|  |  |  | Address BYOD risk |

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
| Map controls to trust/delivery needs | Tier by app/data sensitivity | Align threat modeling to business features | Show security during customer reviews |
| CI/CD reviews | Security champions | Threat modeling checklists | Secure coding standards |
| Track pre-release findings | Time-to-fix by severity | Escape rate | Tag security items in backlog |
| Add SAST to CI/CD | Bug bounty program | Clarify ownership | Automate secrets/dependency scans |
|  |  |  | Embed AppSec in product planning |
|  |  |  | Secrets remediation sprint |
|  |  |  | Monthly AppSec reporting |
|  |  |  | Secure code review playbooks |


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
| Align DR to SLAs | Validate vendors | Include plans in due diligence | Demonstrate audit readiness |
| Cross-team training | Simulate system loss | Define restore ownership | Document dependencies |
| Backup coverage | RTO/RPO tracking | Dependency mapping | Test logs |
| Backup/DR inventory | Automate testing | Write top-system runbooks | Assign metric owners |
|  |  |  | Risk exceptions flagged |
|  |  |  | Include in onboarding |
|  |  |  | Gap visualization |
|  |  |  | Snapshot/rollback tooling |


</details>

## 🧱 IAM Tiering Model (NIST-Aligned)

| Tier | Description | IAM Characteristics |
|------|-------------|----------------------|
| **Tier 1: Partial** | Ad hoc, undocumented, reactive | - Shared admin accounts<br>- No formal provisioning<br>- Local identities unmanaged<br>- No access reviews |
| **Tier 2: Risk-Informed** | Some policies exist; inconsistent enforcement | - MFA on some systems<br>- Manual provisioning/deprovisioning<br>- Periodic reviews (when triggered)<br>- Roles defined but not consistently applied |
| **Tier 3: Repeatable** | Documented policies; consistent application | - Role-based access across most systems<br>- Joiner/mover/leaver process<br>- Quarterly access reviews<br>- Admin rights scoped and logged |
| **Tier 4: Adaptive** | Dynamic, automated, metrics-driven | - Attribute-based access (ABAC) or centralized RBAC<br>- Just-in-time admin access<br>- Automated user lifecycle with audit hooks<br>- Real-time risk-based access controls |
