# Biograph Cybersecurity Planning Discussion

## 🌟 Vision

Enable Biograph to accelerate scientific and business innovation securely—by strengthening what works, advancing key capabilities, and protecting sensitive data with resilience and trust. This strategy builds incrementally on existing foundations, guided by real-world risks and practical execution.

## 🔁 From Conversation to Continuous Execution
This strategy framework is designed to provide a basis for prioritizing the continuous execution of security priorities. By the end of this discussion, we will have identified:
* Potential opportunities and challenges across your security domains
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
| Are access boundaries enforced for high-risk systems such as AI models, production automation, or sensitive datasets? | Who is expected to own access hygiene within business units—and is that expectation clear? | How long would it take to determine the blast radius of a successful employee ATO (account takeover)? |  |
|  |  | What is the average time to deprovision access after employee termination? |  |

</details>

<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Formalize criteria and workflows for assigning access based on business role, data sensitivity, and operational context | Form GRC Leadership Team | Identify audit gaps | Evaluate IAM maturity using NIST-aligned tiers |
| Centralize IAM | Train users and admins on access hygiene and privilege minimization | Use nudges/gamification | Integrate into onboarding |
| 3rd-party penetration testing | Promote ownership and accountability for privileged access | Audit trails and provisioning error tracking<br>Visualize access flows | Embed IAM in engineering conversations |
|  | Clarify decision-making boundaries between security, IT, and business owners for access changes | Track time-to-deprovision from termination to removal | Automate provisioning and enforce least privilege |
|  |  | Track blast radius readiness for employee ATO scenarios | Tag and audit privileged accounts |
|  |  |  | Assign and document ownership for IAM operations (roles, provisioning, reviews) |
|  |  |  | Integrate IAM metrics into business reporting |
|  |  |  | Adopt continuous access verification (e.g., re-auth for sensitive actions) |

</details>


### Data Protection
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Are our practices aligned with data privacy, retention, and breach readiness standards? | Are teams aware of how to handle sensitive data in practice? | Do we know where sensitive data resides and flows? | Do we have effective tools and processes for classification, DLP, and data discovery—and are they in active use? |
| Are legal hold obligations integrated into our data lifecycle and deletion practices? | Is there a shared understanding of what qualifies as sensitive or regulated data across teams? | Do we measure data access frequency, movement, and anomalies? | Can we apply and enforce legal holds across structured and unstructured systems? |
|  |  |  | Are legal hold actions logged, auditable, and reversible if needed? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Map to HIPAA/SOC2/contractual obligations | Align classification to contract data types | Flag exposure across third-party tools | Document breach readiness |
| Train teams using real examples | Cheat sheets by role | Normalize data minimization conversations | Flag unknown/ambiguous data use |
| Identify flows | Promote ownership of data flows | Track near-miss incidents | Generate heatmaps |
| Use discovery/classification tools | Host data handling ‘tabletop’ scenarios to reinforce practices and surface gray areas | Build data maps with ownership tags | Inventory third-party access |
| Align legal hold procedures with data retention and destruction policies | Reinforce awareness of legal hold requirements with business and legal teams | Monitor legal hold enforcement across systems | Automate legal hold application in email, storage, and SaaS platforms |
|  |  |  | Ensure legal holds override conflicting data retention/deletion automation |

</details>


### Threat Detection & Response
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do we meet internal and contractual expectations for detection and response timeframes? | Are IR plans tested and embraced across teams—or siloed to security? | Are alerts actionable and outcomes tracked (MTTD, MTTR)? | Do we operate SIEM/XDR or rely on MDR, and is it effective? |
| Are detection priorities mapped to the highest-impact threats for our environment? | Do responders feel empowered and clear on their roles during incidents? | Are we measuring detection fidelity and false positive rates? | Do we test and simulate our response process across critical systems regularly? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Review IR obligations | Validate breach workflows | Confirm policies for regulated environments | Audit logs for defensibility |
| Map detection coverage to threat modeling results | Run tabletop scenarios | Track alert/resolution trends | Tune detection logic |
| Identify regulatory gaps in response capabilities | Identify cross-functional responders | Log detection-to-resolution timelines | Assign expectations pre/during/post-incident |
| Build triage playbooks | Clarify IR ownership and expectations for non-security teams | Audit missed alerts quarterly | Report IR metrics |
|  | Include IR in onboarding | Measure and reduce false positive rates | Retention alignment |
|  |  | Monitor responder workload and resolution bottlenecks | Distinguish noise vs. signal |
|  |  |  | Assign IR ownership |
|  |  |  | Validate MDR contract scope and SLA performance |

</details>

### Endpoint & Device Security
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do we meet baseline standards for EDR, encryption, and configuration in regulated environments? | Do employees and contractors understand endpoint risks and acceptable use? | Can we monitor device compliance and policy status continuously? | Can we patch and configure devices at scale across environments? |
| Are unmanaged or personal devices assessed for risk based on access level or data exposure? | Do employees view endpoint policies as enablers of trust and productivity—or friction? | Do we track patch success/failure rates and config drift trends? | How quickly can we isolate or replace a compromised endpoint in practice? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Align controls to classification tiers | Confirm with auditors | Track device lifecycle | Flag gaps between environments |
| Awareness training by persona | Set policy norms | Assign accountability | Build dashboards |
| Patch lag and coverage | Run recurring awareness campaigns on phishing, malware, and device risks | Compare EDR by team | Inventory unmanaged devices |
| EDR rollout by user type | Gamify patching | Monitor patch success rates and failure causes by device group | Automate patching |
| Evaluate unmanaged and BYOD risk zones | Reinforce secure endpoint behavior during onboarding | Detect config drift | Show endpoint threat resilience |
|  |  |  | Establish rapid isolation/quarantine procedures for compromised devices |
|  |  |  | Address BYOD risk |

</details>

### Infrastructure & Network Security
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Are our network and infrastructure controls aligned with the sensitivity of hosted data and services? | Do infrastructure and DevOps teams view network and infra hardening as part of their delivery responsibilities? | Do we track exposure metrics (e.g., open ports, unused services, misconfigurations)? | How quickly can we detect, respond to, and remediate unauthorized changes in infrastructure or network configuration? |
| Are segmentation, zoning, and boundary controls in place for high-risk environments (e.g., production, regulated data)? | Is there consistent use of infrastructure-as-code and policy-as-code to support secure-by-default deployments? | Do we monitor baseline posture across cloud and on-prem infrastructure? | Are changes to infrastructure and network configurations logged, reviewed, and auditable? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Apply least privilege principles to network flows and service accounts | Promote infrastructure ownership of security posture | Track external exposure (ports, endpoints, unused services) | Implement network segmentation and tiered access models |
| Align security groups, firewalls, and routing to data classification | Integrate security into infrastructure-as-code and CI/CD workflows | Monitor drift from known-good configurations | Enforce change control for network and infrastructure updates |
| Evaluate risks from hybrid cloud/on-prem interconnectivity | Normalize security expectations in SRE and platform teams | Measure success of patching and remediation SLAs for infrastructure | Automate alerts for anomalous infra/network behavior |
| Implement baseline controls across all environments (cloud, on-prem, hybrid) | Reinforce secure deployment patterns in engineering onboarding | Audit unused services and misconfigured components regularly | Use policy-as-code to enforce configuration standards |
|  |  | Track time-to-remediate misconfigurations | Tag critical infrastructure components for prioritized protection |

</details>


### Application Security
<details>
<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| How well does our current application security approach reflect the kinds of risks the business actually cares about? | When engineering teams move fast, how does security stay involved—if at all—across design, coding, review, and deployment? | How do you measure the effectiveness of application security today—if at all? | What parts of application security are currently automated or repeatable—and what still depends on manual effort or one-off reviews? |
| Are legacy and modern applications assessed differently based on architecture and exposure? | Do developers see security as a shared responsibility or as a compliance checkbox? | Do we track security regression trends or repeat vulnerabilities over time? | Are secure-by-default patterns embedded in reusable code, templates, or libraries? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Map controls to trust/delivery needs | Tier by app/data sensitivity | Align threat modeling to business features | Show security during customer reviews |
| Align security controls to SLA/impact tiers | Security champions | Threat modeling checklists | Embed security reviews into CI/CD pipelines with risk-based gates |
| Define AppSec gates by risk profile | Promote developer-led security improvements and success stories | Track pre-release findings | Secure coding standards |
| Evaluate risk exposure of legacy vs. cloud-native apps | Bug bounty program | Time-to-fix by severity | Automate secrets/dependency scans |
| Include AppSec in customer assurance and legal conversations | Normalize developer ownership of security | Escape rate | Embed AppSec in product planning |
|  |  | Clarify ownership | Tag security items in backlog |
|  |  | Track recurrence of previously remediated vulnerabilities | Secrets remediation sprint |
|  |  |  | Monthly AppSec reporting |
|  |  |  | Secure code review playbooks |
|  |  |  | Build secure-by-default libraries and infrastructure templates |
|  |  |  | Provide self-service tooling for dependency scanning and secrets detection |

</details>

### Resilience & Continuity

<details>
<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Do our recovery and continuity practices meet internal SLAs and any contractual or regulatory obligations? | Are continuity plans documented and rehearsed beyond just the IT team? | Are RTO/RPO metrics tracked and reported for key services? | Do we have a reliable and tested recovery process for critical systems? |
| Do continuity strategies account for supply chain or third-party service disruptions? | Do business leaders understand their role in resilience planning and recovery decision-making? | Do we measure time-to-detect and time-to-initiate failover or recovery operations? | Are continuity procedures tested under realistic, high-pressure scenarios? |

</details>
<details>

<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Align DR to SLAs | Validate vendors | Include plans in due diligence | Demonstrate audit readiness |
| Assess critical third-party dependencies and incorporate them into DR planning | Cross-team training | Define restore ownership | Document dependencies |
| Backup coverage | Simulate system loss | RTO/RPO tracking | Test logs |
| Backup/DR inventory | Establish executive and business-unit continuity playbooks and expectations | Dependency mapping | Assign metric owners |
|  |  | Track time-to-initiate failover or recovery in exercises and real events | Risk exceptions flagged |
|  |  |  | Include in onboarding |
|  |  |  | Gap visualization |
|  |  |  | Snapshot/rollback tooling |
|  |  |  | Conduct chaos engineering or stress testing for critical systems |
|  |  |  | Validate cross-region/cloud failover scenarios (if applicable) |

</details>

## 📊 Security Metrics & Governance Framework

To translate strategy into sustained progress, Biograph will establish a simple, actionable metrics and governance model. This ensures that security improvements are visible, measurable, and continuously aligned with risk and business priorities.

### 🎯 Purpose

- Make security progress transparent across domains and teams
- Provide early signals of improvement, drift, or emerging gaps
- Support prioritization and resource allocation with data
- Align technical execution with leadership expectations

### 📐 Metrics by Domain (Sample)

| Domain                          | Sample Metrics                                                              |
|---------------------------------|------------------------------------------------------------------------------|
| Identity & Access Management    | % of users with least privilege access<br>Time to deprovision<br>Quarterly access review completion |
| Data Protection                 | % of sensitive data classified and tagged<br>Unmapped third-party data flows<br>DLP incidents per month |
| Threat Detection & Response     | MTTD/MTTR (Mean Time to Detect/Respond)<br>% of alerts triaged within SLA<br>Tabletop exercise participation rate |
| Endpoint & Device Security      | Patch success rate<br>EDR coverage by device type<br>BYOD device compliance rate |
| Application Security            | % of apps with SAST/SCA coverage<br>Vulnerability time-to-fix by severity<br>Recurring flaw reintroductions |
| Infrastructure & Network Security | % of systems covered by IaC with policy-as-code<br>Unpatched exposed services<br>Drift from baseline configuration |
| Resilience & Continuity        | RTO/RPO adherence<br>Backup test pass rate<br>Time to initiate failover |

### 📅 Governance & Review Cadence

| Level          | Audience           | Frequency     | Focus Areas                                |
|----------------|--------------------|---------------|---------------------------------------------|
| Operational    | Domain leads, SecOps | Monthly        | Metric trends, blockers, ownership updates  |
| Cross-Functional | GRC, IT, Engineering | Quarterly      | Heatmap of domain maturity, shared initiatives |
| Executive      | Security & Business Leaders | Biannually     | Risk posture, investment needs, progress summary |

### 🗺️ Maturity & Progress Visualization

Teams can use a **color-coded heatmap or scorecard** to visualize progress against maturity tiers across domains.

| Domain                        | Current Tier | Target Tier | Status     |
|-------------------------------|--------------|-------------|------------|
| Identity & Access Management  | Tier 2       | Tier 3      | 🟡 In Progress |
| Application Security          | Tier 1       | Tier 3      | 🔴 Needs Focus |
| Resilience & Continuity       | Tier 3       | Tier 4      | 🟢 On Track |

This structured governance layer ensures that security efforts stay aligned, accountable, and outcome-driven.


## 🧱 Security Domain Maturity Model (NIST-Aligned)

This tiering model can be applied across all seven security domains. Each tier represents increasing levels of consistency, integration, and impact. The rightmost column illustrates how each tier might manifest in the **Identity & Access Management (IAM)** domain as an example.

| Tier | General Description | Example: IAM Characteristics |
|------|----------------------|-------------------------------|
| **Tier 1: Partial** | Ad hoc, undocumented, reactive processes. Security is inconsistent, often dependent on individual effort rather than policy or tooling. | - Shared admin accounts<br>- No formal provisioning<br>- Local identities unmanaged<br>- No access reviews |
| **Tier 2: Risk-Informed** | Some documented policies exist. Implementation is manual or inconsistent across teams. Decisions are influenced by known risks, but lack repeatability. | - MFA on some systems<br>- Manual provisioning/deprovisioning<br>- Periodic reviews (when triggered)<br>- Roles defined but not consistently applied |
| **Tier 3: Repeatable** | Security policies and processes are well-documented and enforced consistently across environments. Key controls are monitored and integrated with workflows. | - Role-based access across most systems<br>- Joiner/mover/leaver process<br>- Quarterly access reviews<br>- Admin rights scoped and logged |
| **Tier 4: Adaptive** | Security is dynamic, automated, and integrated with business context. Controls are risk-aware, continuously validated, and support rapid change. | - Attribute-based access (ABAC) or centralized RBAC<br>- Just-in-time admin access<br>- Automated user lifecycle with audit hooks<br>- Real-time risk-based access controls |

