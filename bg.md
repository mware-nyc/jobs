# Biograph Cybersecurity Planning Discussion

## 🌟 Vision

Enable Biograph to accelerate scientific and business innovation securely—by strengthening what works, advancing key capabilities, and protecting sensitive data with resilience and trust. This strategy builds incrementally on existing foundations, guided by real-world risks and practical execution.

## 🔢 Strategic Framing: How We Approach the Security Discussion

This strategic framework is structured around two complementary layers: **cross-functional lenses** and **core security domains**.

### 🔍 Lenses: What Drives Focus

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

<details>
  
<summary>

  ## 🔁 From Conversation to Continuous Execution

</summary>

This strategy framework is designed to provided a basis for prioritizing the continuous execution of security priorities. By the end of this discussion, we will have identified:
* Potential opportunities and challenges across your security domains
* Practices that align to your culture, capabilities, and customer expectations
* Tangible actions—big or small—that can strengthen your current program 

Vetting and refining what is discussed here with stakeholders across the organization, security planning and execution will be:
* Domain-driven – Focused on highest priority security domains where progress will have the highest impact
* Lens-aligned – Structured by the cross-functional realities of your organization (e.g., culture, measurement, execution)
* Actionable – Grounded in realistic next steps that reflect your current maturity and operating environment
* Measurable – Supported by simple metrics or milestones that show progress without creating noise

</details>

### ❔ Focus Questions

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
| Are access boundaries enforced for high-risk systems such as AI models, production automation, or sensitive datasets? | Who is expected to own access hygiene within business units—and is that expectation clear? | How long would it take to determine the blast radius of a successful employee ATO (account takeover)? | Are MFA methods standardized, logged, and regularly reviewed for strength and usability? |
| Do all high-risk systems—including admin interfaces—enforce MFA consistently across user types? | How do teams perceive the usability and burden of MFA in day-to-day access? | Do we track MFA enrollment rates and bypass events across users and systems? | Are privileged access sessions isolated, monitored, and auditable through PAM tooling or compensating controls? |
|  |  | What is the average time to deprovision access after employee termination? |  |

</details>

<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Formalize criteria and workflows for assigning access based on business role, data sensitivity, and operational context | Form GRC Leadership Team | Identify audit gaps | Evaluate IAM maturity using NIST-aligned tiers |
| Require MFA for all privileged access and sensitive data workflows | Train users and admins on access hygiene and privilege minimization | Use nudges/gamification | Integrate into onboarding |
| 3rd-party penetration testing | Promote ownership and accountability for privileged access | Audit trails and provisioning error tracking<br>Visualize access flows | Embed IAM in engineering conversations |
| Enforce just-in-time privileged access for high-risk systems | Clarify decision-making boundaries between security, IT, and business owners for access changes | Track time-to-deprovision from termination to removal | Automate provisioning and enforce least privilege |
| Maintain a credential vault or equivalent for privileged accounts | Educate teams on the importance of MFA and reduce friction in adoption | Track blast radius readiness for employee ATO scenarios | Tag and audit privileged accounts |
|  |  | Track MFA coverage by user group, application, and device type | Assign and document ownership for IAM operations (roles, provisioning, reviews) |
|  |  | Monitor failed or bypassed MFA attempts for potential abuse patterns | Integrate IAM metrics into business reporting |
|  |  |  | Adopt continuous access verification (e.g., re-auth for sensitive actions) |
|  |  |  | Consolidate MFA enforcement through identity providers or centralized SSO platforms |
|  |  |  | Regularly validate and update approved MFA methods (e.g., remove SMS if outdated) |
|  |  |  | Monitor and alert on privileged session activity via PAM tooling or log analysis |

</details>

### Data Protection
<details>

<summary> Questions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Are our data protection practices aligned with applicable privacy laws, contract terms, and risk tolerance? | Are teams aware of which types of data are subject to special handling, retention limits, or legal restrictions? | Do we know where sensitive data is stored, processed, and transmitted—across SaaS, cloud, and local systems? | Do we have effective tools and processes for classification, DLP, and discovery—and are they in active use? |
| Are legal hold obligations integrated into our data lifecycle and deletion practices? | Is there a shared understanding of what qualifies as sensitive or regulated data across teams? | Do we track data access frequency, data movement patterns, and anomaly indicators? | Can we apply and enforce legal holds across structured and unstructured systems? |
| Do we consider jurisdiction-specific privacy obligations (e.g., CCPA, GDPR) in our data handling practices? | Is there a documented escalation path for legal or compliance review of unusual or risky data handling scenarios? | Do we track response times and closure rates for data subject rights requests? | Are legal hold actions logged, auditable, and reversible if needed? |
| Are access controls on sensitive data based on business need and reviewed regularly? | Do teams understand the risks of casual overexposure, including data shared in Slack, spreadsheets, or unapproved apps? | Are sensitive data flows and access mapped by role, system, and third-party exposure? | Are breach readiness activities tested and documented—including cloud and third-party scenarios? |
| Do we minimize data collection and retention by default? | Do teams understand what kinds of data they are generating, storing, or exporting? | Do we measure our data footprint (e.g., total volume, duplication, unstructured sprawl)? | Are unstructured data stores (e.g., shared drives, collaboration tools) governed consistently? |

</details>
<details>
<summary> Actions</summary>

| Risk Alignment | Culture | Measurement | Execution |
|----------------|---------|-------------|-----------|
| Map data protection controls to HIPAA/SOC 2/contractual/privacy obligations | Align classification to contract or regulatory data types | Flag exposure across third-party SaaS platforms | Document breach readiness plans and run scenario tests |
| Identify and map sensitive data flows across environments | Create role-specific cheat sheets for data handling | Track near-miss incidents and informal disclosures | Tag and inventory unstructured data (e.g., shared folders, cloud docs) |
| Apply minimization principles to data collection, retention, and export | Reinforce ownership of sensitive data flows and lifecycle responsibilities | Build dashboards for data movement and access risk | Inventory third-party data processors and access scopes |
| Use discovery/classification tooling across structured and unstructured systems | Host data tabletop scenarios that involve legal and business risk decisions | Track volume and growth of unstructured or redundant data | Automate classification and labeling in cloud and SaaS environments |
| Align legal hold procedures with retention and deletion policies | Train teams to recognize data classification cues and apply appropriately | Monitor legal hold enforcement across systems | Automate legal hold application in collaboration and storage platforms |
| Maintain a system of record for legal data requests, exemptions, and overrides | Clarify escalation procedures for ambiguous data use cases | Monitor trends in data access and data rights request patterns | Ensure legal holds override any retention policy conflicts |
| Tag and track data subject rights requests (e.g., access, deletion) | Normalize conversations around unnecessary data collection or access | Track data inventory and ownership coverage | Enforce ownership tagging in data lakes, shared drives, and external data tools |

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
| Are unmanaged or personal devices assessed for risk based on access level or data exposure? | Do employees and contractors understand endpoint risks and acceptable use? | Can we monitor device compliance and policy status continuously? | Can we patch and configure devices at scale across environments? |
| Are detection or control gaps introduced by 3rd-party medical devices used in clinical or research workflows? | Do employees view endpoint policies as enablers of trust and productivity—or friction? | Do we track patch success/failure rates and config drift trends? | How quickly can we isolate or replace a compromised endpoint in practice? |
| Are medical devices onboarded to any asset inventory or endpoint management tooling? | Do teams understand ownership boundaries for securing 3rd-party and vendor-supplied equipment? | Do we track device visibility and compliance rates across device categories (e.g., laptops vs. medical vs. BYOD)? | Are endpoint agents deployed uniformly across hardware types, including Macs, Windows devices, and clinical laptops? |
| Are any GCP-managed endpoints or ChromeOS devices part of your asset fleet or used in support roles? |  |  | Are hardware tools (e.g., MDM, EDR, patching systems) integrated with cloud identity and access platforms? |

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

<details>
<summary>

  ## 🧭 Managing the Work That Follows

</summary>

The planning and prioritization outlined in this document will generate meaningful security work—some immediate, some iterative. Executing on these priorities requires thoughtful coordination across contributors, teams, and timeframes, especially when resources are distributed and not all stakeholders are present in initial conversations.

This section is not prescriptive in process, but offers guiding principles for how to manage the resulting work in a way that is focused, sustainable, and respectful of limited capacity.

### 🧠 Guiding Principles

Drawing from **LEAN theory**, **Theory of Constraints**, and the **Agile Manifesto**, effective security execution should emphasize:

- **Flow over load** – Minimize work-in-progress and avoid overwhelming individuals or teams.
- **Clarity over control** – Make work visible, not rigid. Align around purpose, not prescription.
- **Value over volume** – Prioritize what meaningfully reduces risk or increases resilience—not just what’s easiest to check off.
- **Iteration over perfection** – Focus on making things better over time, not getting it all right up front.
- **Collaboration over isolation** – Involve those closest to the work and downstream impact—even if they weren’t in the initial planning.

### 🛠 How Work May Be Managed

- Workstreams may span across **technical and non-technical staff**. Clear ownership and collaboration will be important.
- Small, well-scoped tasks should be preferred over large, vague projects—reducing delay, handoff friction, and overcommitment.
- Use of existing collaboration and tracking tools (e.g., tickets, sprints, Kanban boards, working groups) is encouraged, but should reflect team norms and actual capacity—not idealized throughput.
- Avoid batch planning or “big bang” initiatives. Instead, sequence improvements based on readiness, risk reduction, and learning opportunity.

### 📌 What to Expect

- Some work will begin immediately with participants of this discussion.
- Other priorities may require coordination with teams **not yet engaged**, and will benefit from socialization and validation before action.
- Leadership and cross-functional advocates are encouraged to help **remove blockers**, **protect focus**, and **reduce organizational friction** to executing the most valuable actions.

By managing work as a continuous, collaborative flow—not a fixed checklist—we improve both execution and impact while reducing waste, rework, and burnout.

</details>

<details>
<summary>

## 📊 Security Metrics & Governance Framework

</summary>


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
| Application Security            | % of apps with SAST/SCA coverage<br>Vuln time-to-fix by severity<br>Recurring flaw reintroductions |
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

</details>

<details>
<summary>

## 🧱 Security Domain Maturity Model (Inspired by Industry and NIST Tiering)

</summary>

This tiering model can be applied across all seven security domains. Each tier represents increasing levels of consistency, integration, and impact. The rightmost column illustrates how each tier might manifest in the **Identity & Access Management (IAM)** domain as an example.

| Tier | General Description | Example: IAM Characteristics |
|------|----------------------|-------------------------------|
| **Tier 1: Partial** | Ad hoc, undocumented, reactive processes. Security is inconsistent, often dependent on individual effort rather than policy or tooling. | - Shared admin accounts<br>- No formal provisioning<br>- Local identities unmanaged<br>- No access reviews |
| **Tier 2: Risk-Informed** | Some documented policies exist. Implementation is manual or inconsistent across teams. Decisions are influenced by known risks, but lack repeatability. | - MFA on some systems<br>- Manual provisioning/deprovisioning<br>- Periodic reviews (when triggered)<br>- Roles defined but not consistently applied |
| **Tier 3: Repeatable** | Security policies and processes are well-documented and enforced consistently across environments. Key controls are monitored and integrated with workflows. | - Role-based access across most systems<br>- Joiner/mover/leaver process<br>- Quarterly access reviews<br>- Admin rights scoped and logged |
| **Tier 4: Adaptive** | Security is dynamic, automated, and integrated with business context. Controls are risk-aware, continuously validated, and support rapid change. | - Attribute-based access (ABAC) or centralized RBAC<br>- Just-in-time admin access<br>- Automated user lifecycle with audit hooks<br>- Real-time risk-based access controls |

</details>
