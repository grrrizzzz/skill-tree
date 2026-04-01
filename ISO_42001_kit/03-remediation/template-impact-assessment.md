# AI System Impact Assessment

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689)

---

> **Legal Disclaimer:** This template does not constitute legal advice. References to the EU AI Act are for context only; consult qualified legal counsel for your organization's specific regulatory obligations, including EU AI Act classification, deployer duties, and fundamental rights impact assessment requirements.

---

## HOW TO CUSTOMIZE THIS TEMPLATE

> **⚠️ INTERNAL CONSULTANT USE — REMOVE THIS SECTION BEFORE DELIVERING TO CLIENT**

### What This Template Is For

This template produces a completed **AI System Impact Assessment** for a single AI system (or a closely related group of AI systems with identical use cases, data flows, and affected populations). It satisfies ISO/IEC 42001:2023 Annex A controls **A.5.3** (AI System Impact Assessment) and **A.5.4** (Impact of AI System Documentation), and supports Clauses **6.1.4** (AI system impact assessment process), **6.1.5** (impact treatment options), and **8.4** (AI system impact assessment — operational implementation).

**This is not a risk assessment.** The AI System Risk Assessment (template AIMS-RA-001) asks: *what could go wrong with this AI system?* This template asks a different, more human-centered question: ***what could this AI system do to people?***

### When to Complete This Assessment

Complete one assessment per in-scope AI system. Prioritize in this order:

1. **High Risk AI systems first** — especially any system that influences decisions about people (hiring, credit, access to services, performance management, customer eligibility)
2. **Medium Risk systems second** — systems that process personal data or interact directly with customers or employees
3. **Low Risk systems last** — internal productivity tools with minimal personal data processing and no decision-making role

For clients with many AI systems, group systems with identical use cases, identical affected populations, and identical data flows into a single assessment. Document the grouping rationale in Section 1.

### Who Should Be Involved

| Role | Contribution |
|---|---|
| **AI System Owner** | Provides operational details; confirms intended use and actual use; signs off |
| **HR / People Lead** | Essential for any system affecting employees or job applicants |
| **Legal / Compliance** | Reviews for regulatory exposure; required for High Risk systems |
| **Data Protection Officer (if applicable)** | Coordinates with DPIA obligations; flags personal data processing concerns |
| **Department Head(s)** | Confirms how the system is actually used day-to-day |
| **ISO 42001 Consultant** | Guides the assessment process; validates completeness; ensures audit readiness |

### How to Use the Findings

- **Acceptable residual impact** → Document and file. Schedule next review per Section 7.
- **Acceptable with conditions** → Implement conditions before or alongside deployment. Track in Section 5.
- **Not acceptable** → Escalate to senior management immediately. Do not deploy (or suspend if already deployed) until mitigations reduce impact to acceptable level.
- **High Risk AI systems** → Senior management sign-off is required regardless of acceptability determination (Section 8).

### Completing the Example Content

This template includes example content in *italics* for an AI-assisted resume screening tool (HR use case). This example shows how a High Risk AI system affecting hiring decisions would be assessed. **Delete all example content before delivering to the client.** Example content is clearly marked with *[EXAMPLE]* labels.

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-IA-[system]-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **AI System Name** | [Name of the AI system being assessed] |
| **AI System ID** | [System ID from AI System Inventory, e.g., AI-SYS-007] |
| **Organization** | [Organization Name] |
| **Prepared By** | [Name, Role] |
| **Reviewed By** | [Name, Role] |
| **Approved By** | [Name, Role — Senior Management required for High Risk systems] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Date, or earlier per Section 7] |

---

## Clause and Control Traceability

| Reference | Description |
|---|---|
| **ISO 42001 Clause 6.1.4** | AI system impact assessment — planning requirement |
| **ISO 42001 Clause 6.1.5** | AI system impact treatment options |
| **ISO 42001 Clause 8.4** | AI system impact assessment — operational implementation |
| **Annex A Control A.5.3** | AI System Impact Assessment — evaluate impacts on individuals and groups |
| **Annex A Control A.5.4** | Impact of AI System Documentation — document results, mitigations, residual impacts |

---

## Section 1: AI System Overview

*Provide a factual description of the AI system being assessed. This section establishes the scope and context for all subsequent impact analysis. If this assessment covers a group of similar systems, list all systems in the group and document the grouping rationale.*

### 1.1 System Identification

| Field | Value |
|---|---|
| **AI System Name** | [Full name of the AI system or product] |
| **Vendor / Provider** | [Vendor name] |
| **Product Version / Model** | [Version number, model name, or API version] |
| **AI System ID (Inventory)** | [Cross-reference to AI System Inventory entry, e.g., AI-SYS-007] |
| **Risk Classification** | [High / Medium / Low — from AI System Inventory] |
| **Assessment Scope** | ☐ Single system  ☐ Group of similar systems (list below) |

*[EXAMPLE] AI System Name: HireIQ Resume Screening Platform | Vendor: HireIQ Technologies | Product Version: v4.2 (cloud-hosted SaaS) | AI System ID: AI-SYS-007 | Risk Classification: High | Assessment Scope: Single system*

**If group assessment, list all systems covered:**

| System Name | System ID | Vendor | Version |
|---|---|---|---|
| [System 1] | [ID] | [Vendor] | [Version] |
| [System 2] | [ID] | [Vendor] | [Version] |

### 1.2 Intended Use

**Intended use within the organization:**

[Describe what the organization uses this AI system to do. Be specific about the business process it supports, the decisions it informs or makes, and the operational context in which it operates.]

*[EXAMPLE] HireIQ is used by the HR department to screen incoming job applications. The system analyzes uploaded resumes and cover letters, scores each applicant against a job description, and produces a ranked shortlist of candidates recommended for human review. Hiring managers use the shortlist to determine which candidates to invite for interviews. The system is used for all open positions across the organization.*

**Organizational units using this system:**

| Organizational Unit | Primary Use | Approximate Number of Users |
|---|---|---|
| [Unit name] | [How they use it] | [Number] |

*[EXAMPLE] HR Department | Resume screening and candidate shortlisting | 4 users (2 HR coordinators, 1 HR manager, 1 Talent Acquisition Lead)*

### 1.3 Data Flows

**Data inputs — what data enters the AI system:**

| Data Type | Source | Contains Personal Data? | Sensitive Category? |
|---|---|---|---|
| [Data type] | [Where it comes from] | Yes / No | Yes / No |

*[EXAMPLE]*
| *Data Type* | *Source* | *Contains Personal Data?* | *Sensitive Category?* |
|---|---|---|---|
| *Resume / CV (PDF or Word)* | *Applicant upload via careers portal* | *Yes* | *Potentially (name, address, employment history)* |
| *Cover letter* | *Applicant upload via careers portal* | *Yes* | *Potentially (personal narrative, may reveal protected characteristics)* |
| *Job description* | *HR team input* | *No* | *No* |
| *Historical hiring decisions (used for model calibration)* | *HRIS export* | *Yes* | *Yes (past employee data)* |

**Data outputs — what the AI system produces:**

| Output Type | Format | Who Receives It | Used For |
|---|---|---|---|
| [Output type] | [Format] | [Recipients] | [Purpose] |

*[EXAMPLE]*
| *Output Type* | *Format* | *Who Receives It* | *Used For* |
|---|---|---|---|
| *Candidate score (0–100)* | *Numeric score in dashboard* | *HR coordinators, hiring managers* | *Ranking applicants; determining interview shortlist* |
| *Ranked candidate list* | *Dashboard view and CSV export* | *HR coordinators* | *Shortlist generation* |
| *Match rationale (top factors)* | *Text summary per candidate* | *HR coordinators* | *Explaining score to hiring managers* |

### 1.4 Decision Types

**What decisions does this AI system influence or make?**

| Decision Type | AI Role | Human Role | Automation Level |
|---|---|---|---|
| [Decision] | [What AI does] | [What human does] | Fully automated / AI-assisted / Human-in-the-loop |

*[EXAMPLE]*
| *Decision Type* | *AI Role* | *Human Role* | *Automation Level* |
|---|---|---|---|
| *Candidate shortlisting* | *Scores and ranks all applicants; generates shortlist* | *HR coordinator reviews shortlist; may add or remove candidates* | *AI-assisted (human reviews AI output)* |
| *Interview invitation* | *No direct role* | *Hiring manager decides based on shortlist* | *Human decision* |
| *Rejection (pre-shortlist)* | *Candidates below threshold are excluded from shortlist* | *HR coordinator may review borderline cases* | *Effectively automated for candidates below threshold* |

---

## Section 2: Affected Populations

*Identify all groups of people who interact with or are affected by this AI system. This section is the foundation for the impact analysis in Sections 3 and 4. Be thorough — overlooked affected groups are a common audit finding.*

### 2.1 Direct Users

People who operate or interact directly with the AI system interface:

| User Group | Role | Approximate Number | Location |
|---|---|---|---|
| [User group] | [Their role with the system] | [Number] | [Location/region] |

*[EXAMPLE]*
| *User Group* | *Role* | *Approximate Number* | *Location* |
|---|---|---|---|
| *HR coordinators* | *Upload job descriptions; review AI-generated shortlists* | *2* | *[City, Country]* |
| *HR manager* | *Oversees screening process; approves shortlists* | *1* | *[City, Country]* |
| *Hiring managers* | *Receive shortlists; make interview decisions* | *~15 (varies by open roles)* | *[City, Country]* |

### 2.2 Affected Subjects

People who are affected by AI outputs or decisions but may not interact with the system directly:

| Subject Group | How They Are Affected | Approximate Number Annually |
|---|---|---|
| [Subject group] | [Nature of impact] | [Number] |

*[EXAMPLE]*
| *Subject Group* | *How They Are Affected* | *Approximate Number Annually* |
|---|---|---|
| *Job applicants* | *AI score determines whether they are shortlisted for interview; rejection may occur without human review of their application* | *~800 applicants per year across all open roles* |
| *Internal transfer candidates* | *Same screening process applied to internal applicants* | *~50 per year* |

### 2.3 Vulnerable Groups

*Identify groups that may be disproportionately affected or face heightened risk from this AI system's outputs. Consider: age, disability, race/ethnicity, gender, pregnancy/maternity, religion, sexual orientation, socioeconomic status, language/literacy, immigration status.*

| Vulnerable Group | Potential Heightened Risk | Basis for Concern |
|---|---|---|
| [Group] | [Nature of heightened risk] | [Why this group may be more affected] |

*[EXAMPLE]*
| *Vulnerable Group* | *Potential Heightened Risk* | *Basis for Concern* |
|---|---|---|
| *Applicants with non-linear career histories* | *Lower AI scores due to employment gaps or career changes* | *AI trained on historical hires may penalize non-traditional career paths disproportionately affecting women, caregivers, and people with disabilities* |
| *Applicants from underrepresented ethnic backgrounds* | *Name-based or language-pattern bias in resume parsing* | *Research shows AI resume tools can exhibit bias against names associated with minority groups* |
| *Older applicants (50+)* | *Graduation year inference; penalization of older experience* | *AI may infer age from graduation dates and downweight older candidates* |
| *Applicants with disabilities* | *Non-standard resume formats may parse poorly* | *Applicants using assistive technology may produce resumes that AI parsers misread* |
| *Applicants for whom English is a second language* | *Lower language-match scores* | *AI language models may score non-native English writing patterns lower* |

### 2.4 Geographic Scope

| Scope Element | Detail |
|---|---|
| **Countries/regions where AI system operates** | [List countries or regions] |
| **Countries/regions where affected subjects are located** | [List countries or regions] |
| **Applicable data protection regimes** | [e.g., GDPR, UK GDPR, CCPA, etc.] |

*[EXAMPLE] Countries where system operates: [Country]. Countries where applicants are located: [Country] (remote applicants may be located elsewhere). Applicable data protection regimes: GDPR (if EU-based); consult DPO.*

### 2.5 Scale of Impact

| Metric | Estimate |
|---|---|
| **Estimated individuals affected annually** | [Number] |
| **Estimated individuals in vulnerable groups affected annually** | [Number] |
| **Frequency of AI-influenced decisions** | [e.g., Daily / Weekly / Per hiring cycle] |

*[EXAMPLE] Estimated individuals affected annually: ~850 applicants. Estimated vulnerable group members affected: ~200–300 (estimated based on demographic assumptions). Frequency: Continuous — system processes applications as received.*

---

## Section 3: Individual Impact Assessment

*For each impact dimension below, assess the potential impact of this AI system on individual people. Complete the assessment table for each dimension. Use the rating scales defined below.*

### Rating Scales

**Likelihood:**
- **High** — Impact is likely to occur in normal operation; has occurred or is expected to occur regularly
- **Medium** — Impact could plausibly occur; may have occurred; requires specific conditions
- **Low** — Impact is unlikely but possible; would require unusual circumstances

**Severity:**
- **Critical** — Severe, potentially irreversible harm; significant legal, financial, or physical consequences for the individual
- **High** — Significant harm; material consequences for the individual's opportunities, rights, or wellbeing
- **Medium** — Moderate harm; noticeable negative effect but recoverable
- **Low** — Minor harm; limited or temporary negative effect

**Residual Risk (after mitigations):**
- **Acceptable** — Residual impact is within the organization's tolerance; no further action required
- **Acceptable with conditions** — Residual impact is tolerable only if specified conditions are maintained
- **Not acceptable** — Residual impact exceeds tolerance; escalation required

---

### 3.1 Privacy

*Does the AI system process personal data? Could it expose, misuse, or inappropriately retain personal information about individuals?*

| Element | Assessment |
|---|---|
| **Impact Type** | Privacy — unauthorized processing, exposure, or misuse of personal data |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe the specific privacy risks. Consider: what personal data is processed, what could go wrong, whether the AI vendor has access to personal data, data retention practices, and whether individuals have been informed of AI processing.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Privacy — personal data (resumes, cover letters) processed by third-party AI vendor |*
*| Likelihood | High — all applicants' personal data is processed by HireIQ's cloud platform |*
*| Severity | High — resumes contain sensitive personal information; vendor data handling practices are partially opaque |*
*| Affected Group(s) | All job applicants (~850/year) |*
*| Current Mitigations | Data Processing Agreement (DPA) in place with HireIQ; applicants informed of AI screening in job postings; data retention limited to 12 months per DPA |*
*| Residual Risk | Acceptable with conditions — DPA must remain current; applicant disclosure must be maintained |*

*[EXAMPLE] Detailed assessment: HireIQ processes applicant resumes and cover letters on its cloud infrastructure. All applicants' personal data — including names, addresses, employment history, and potentially sensitive information disclosed in cover letters — is transmitted to and processed by a third-party vendor. The DPA with HireIQ addresses data processing obligations, but the organization has limited visibility into HireIQ's subprocessor chain. Applicants are currently informed of AI screening via a disclosure in the job posting footer. A DPIA should be conducted or reviewed in conjunction with this assessment.*

---

### 3.2 Discrimination and Fairness

*Could AI outputs disadvantage individuals based on protected characteristics such as age, gender, race, ethnicity, disability, religion, pregnancy, or sexual orientation?*

| Element | Assessment |
|---|---|
| **Impact Type** | Discrimination — AI outputs that disadvantage individuals based on protected characteristics |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe the specific discrimination risks. Consider: what protected characteristics could be inferred or correlated with AI inputs, whether the AI has been tested for bias, whether historical training data reflects past discriminatory practices, and what the consequences of biased outputs are for affected individuals.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Discrimination — AI scoring may disadvantage applicants based on gender, race, age, or disability |*
*| Likelihood | High — documented in academic literature and regulatory enforcement actions against AI hiring tools |*
*| Severity | Critical — discriminatory hiring decisions constitute unlawful discrimination; affected individuals lose employment opportunities |*
*| Affected Group(s) | Applicants from underrepresented ethnic backgrounds; older applicants; applicants with disabilities; applicants with non-linear career histories (disproportionately women) |*
*| Current Mitigations | HireIQ vendor bias audit report reviewed annually; HR manager reviews shortlist for demographic balance; borderline candidates (scores 40–60) reviewed manually by HR coordinator |*
*| Residual Risk | Acceptable with conditions — requires annual bias audit, manual review of borderline cases, and HR training on bias recognition |*

*[EXAMPLE] Detailed assessment: AI resume screening tools have been the subject of significant regulatory scrutiny and academic research demonstrating bias against protected groups. HireIQ's model was trained on historical hiring data that may reflect past discriminatory patterns. The system may infer protected characteristics indirectly (e.g., inferring gender from name, age from graduation year, ethnicity from name patterns). The organization has requested HireIQ's bias testing documentation but has not yet received a current audit report. This is the highest-severity individual impact identified in this assessment.*

---

### 3.3 Autonomy

*Does the AI system limit individuals' ability to make their own decisions? Is there meaningful human oversight of AI-influenced decisions? Are individuals aware that AI is involved?*

| Element | Assessment |
|---|---|
| **Impact Type** | Autonomy — AI limits individual self-determination or removes meaningful human oversight |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe how the AI system affects individual autonomy. Consider: whether individuals can opt out of AI processing, whether human oversight is genuine or nominal, whether the AI's role is disclosed, and whether individuals have any ability to influence the AI's assessment of them.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Autonomy — applicants cannot opt out of AI screening; pre-shortlist rejections are effectively automated |*
*| Likelihood | High — all applicants are screened by AI; those below threshold are not reviewed by humans |*
*| Severity | High — applicants have no ability to present their case to a human reviewer if AI scores them below threshold |*
*| Affected Group(s) | All applicants, particularly those scoring below the shortlist threshold |*
*| Current Mitigations | Disclosure in job postings; HR coordinator reviews borderline cases (scores 40–60); applicants may contact HR to request manual review |*
*| Residual Risk | Acceptable with conditions — manual review option must be actively communicated; threshold must be reviewed quarterly |*

---

### 3.4 Safety

*Could incorrect or unreliable AI outputs cause physical, psychological, or financial harm to individuals?*

| Element | Assessment |
|---|---|
| **Impact Type** | Safety — AI errors cause harm to individuals |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe safety risks from AI errors. Consider: what happens when the AI produces incorrect outputs, whether errors are detectable before they cause harm, and what the consequences are for affected individuals.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Safety — financial harm from wrongful exclusion from employment opportunities |*
*| Likelihood | Medium — AI errors (false negatives) will occur at some rate; exact error rate not disclosed by vendor |*
*| Severity | High — wrongful exclusion from employment has significant financial and psychological consequences for affected individuals |*
*| Affected Group(s) | Applicants incorrectly scored below shortlist threshold |*
*| Current Mitigations | Human review of borderline cases; hiring managers may request full applicant pool review for senior roles; HR manager spot-checks AI shortlists quarterly |*
*| Residual Risk | Acceptable with conditions — spot-check process must be documented and maintained; vendor must provide error rate data |*

---

### 3.5 Dignity

*Does the AI system treat individuals with respect? Could AI outputs be demeaning, dehumanizing, or disrespectful to individuals?*

| Element | Assessment |
|---|---|
| **Impact Type** | Dignity — AI outputs that demean or dehumanize individuals |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe dignity risks. Consider: whether AI outputs could be perceived as disrespectful, whether the AI's characterization of individuals is fair and accurate, and whether individuals are treated as data points rather than people.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Dignity — applicants reduced to a numeric score without opportunity to present their full qualifications |*
*| Likelihood | Medium — inherent in AI screening; mitigated by human review layer |*
*| Severity | Medium — applicants may feel their application was not genuinely considered; reputational risk to organization as employer |*
*| Affected Group(s) | All applicants, particularly those rejected pre-shortlist |*
*| Current Mitigations | Personalized rejection communications (not AI-generated); applicants informed of AI role in screening; manual review available on request |*
*| Residual Risk | Acceptable — current communication practices adequately address dignity concerns |*

---

### 3.6 Access to Services and Opportunities

*Could AI decisions deny individuals access to services, employment, financial products, or other opportunities they would otherwise be entitled to?*

| Element | Assessment |
|---|---|
| **Impact Type** | Access — AI decisions deny individuals access to opportunities or services |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe access risks. Consider: what opportunities or services could be denied, whether denial is reversible, and whether individuals have alternative pathways.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Access — AI screening denies employment opportunities to qualified applicants |*
*| Likelihood | High — by design, AI screening excludes the majority of applicants from human review |*
*| Severity | High — employment is a fundamental economic opportunity; wrongful exclusion has lasting consequences |*
*| Affected Group(s) | All applicants below shortlist threshold; disproportionate impact on vulnerable groups identified in Section 2.3 |*
*| Current Mitigations | Manual review of borderline cases; applicants may request human review; HR manager reviews shortlist composition |*
*| Residual Risk | Acceptable with conditions — requires maintained human review processes and documented appeal pathway |*

---

### 3.7 Transparency

*Are individuals informed when AI is used to make or influence decisions about them? Do they understand the AI's role?*

| Element | Assessment |
|---|---|
| **Impact Type** | Transparency — individuals unaware of AI's role in decisions affecting them |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe transparency risks. Consider: whether individuals are informed of AI use, whether the disclosure is meaningful and accessible, and whether individuals understand what the AI does and does not do.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Transparency — applicants may not notice or understand AI screening disclosure |*
*| Likelihood | Medium — disclosure exists but is in job posting footer; may not be prominent enough |*
*| Severity | Medium — individuals have a right to know when AI influences decisions about them; inadequate disclosure undermines trust and may create legal exposure |*
*| Affected Group(s) | All applicants |*
*| Current Mitigations | Disclosure in job posting footer; privacy notice updated to reference AI screening; HR team trained to explain AI role if asked |*
*| Residual Risk | Acceptable with conditions — disclosure must be reviewed for prominence and clarity; consider adding to application confirmation email |*

---

### 3.8 Redress

*Can individuals challenge AI-influenced decisions? Is there a meaningful appeal mechanism? Can errors be corrected?*

| Element | Assessment |
|---|---|
| **Impact Type** | Redress — individuals cannot challenge or correct AI-influenced decisions |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Group(s)** | [Which individuals are at risk] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

**Detailed assessment:**

[Describe redress risks. Consider: whether individuals know they can appeal, whether the appeal process is accessible and effective, and whether appeals result in genuine human review.]

*[EXAMPLE]*
*| Element | Assessment |*
*|---|---|*
*| Impact Type | Redress — applicants may not know they can request manual review; appeal process not formally documented |*
*| Likelihood | Medium — appeal option exists but is not proactively communicated to rejected applicants |*
*| Severity | High — without effective redress, AI errors cannot be corrected; individuals bear the full cost of AI mistakes |*
*| Affected Group(s) | Applicants rejected pre-shortlist |*
*| Current Mitigations | HR team will conduct manual review on request; rejection emails include HR contact details |*
*| Residual Risk | Acceptable with conditions — formal appeal procedure must be documented and communicated in rejection communications; appeals must result in genuine human review, not AI re-scoring |*

---

### 3.9 Individual Impact Summary

| Impact Dimension | Likelihood | Severity | Residual Risk |
|---|---|---|---|
| 3.1 Privacy | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.2 Discrimination/Fairness | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.3 Autonomy | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.4 Safety | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.5 Dignity | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.6 Access to Services/Opportunities | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.7 Transparency | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 3.8 Redress | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |

*Key: H = High, M = Medium, L = Low, C = Critical, A = Acceptable, AwC = Acceptable with conditions, NA = Not acceptable*

*[EXAMPLE Summary]*
*| Impact Dimension | Likelihood | Severity | Residual Risk |*
*|---|---|---|---|*
*| 3.1 Privacy | H | H | AwC |*
*| 3.2 Discrimination/Fairness | H | C | AwC |*
*| 3.3 Autonomy | H | H | AwC |*
*| 3.4 Safety | M | H | AwC |*
*| 3.5 Dignity | M | M | A |*
*| 3.6 Access to Services/Opportunities | H | H | AwC |*
*| 3.7 Transparency | M | M | AwC |*
*| 3.8 Redress | M | H | AwC |*

---

## Section 4: Societal Impact Assessment

*Assess the potential impacts of this AI system on groups, communities, and society at large. Societal impacts are often less visible than individual impacts but can be significant at scale. Consider both direct effects and second-order consequences of widespread use.*

### 4.1 Fairness at Scale

*Could widespread use of this AI system create or amplify societal inequalities? Consider: if many organizations use similar AI systems, what are the cumulative effects on disadvantaged groups?*

| Element | Assessment |
|---|---|
| **Impact** | [Describe the societal fairness concern] |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Communities** | [Which groups or communities are affected] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

*[EXAMPLE] Impact: AI resume screening tools are widely used across the labor market. If these tools systematically disadvantage applicants from underrepresented groups, the cumulative effect across many employers could entrench and amplify existing labor market inequalities — reducing economic mobility for already-disadvantaged communities. Likelihood: High (documented in labor market research). Severity: Critical (systemic labor market exclusion). Affected Communities: Ethnic minorities, women in male-dominated fields, people with disabilities, older workers. Current Mitigations: Organization's bias monitoring and manual review processes reduce (but do not eliminate) contribution to this systemic effect. Residual Risk: Acceptable with conditions — organization must actively monitor for disparate impact and be prepared to suspend AI screening if bias is confirmed.*

---

### 4.2 Labor Market Effects

*Does this AI system automate tasks previously performed by humans? What are the workforce implications — within the organization and in the broader labor market?*

| Element | Assessment |
|---|---|
| **Impact** | [Describe the labor market concern] |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Communities** | [Which workers or communities are affected] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

*[EXAMPLE] Impact: HireIQ automates the initial resume review task previously performed by HR coordinators. Within the organization, this has reduced the time HR coordinators spend on initial screening by approximately 60%. No roles have been eliminated, but the nature of HR coordinator work has changed. In the broader labor market, widespread adoption of AI screening tools reduces demand for human recruiters and HR screening staff. Likelihood: High (already occurring). Severity: Medium (within organization — role change, not elimination; broader market — moderate displacement risk). Affected Communities: HR and recruitment professionals. Current Mitigations: HR coordinators have been retrained to focus on candidate engagement and assessment quality; no redundancies planned. Residual Risk: Acceptable — organization is managing internal workforce transition responsibly.*

---

### 4.3 Environmental Impact

*What is the energy and resource footprint of this AI system? Does the organization understand and account for the environmental cost of AI use?*

| Element | Assessment |
|---|---|
| **Impact** | [Describe the environmental concern] |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Communities** | [Which communities bear environmental costs] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

*[EXAMPLE] Impact: HireIQ is a cloud-hosted SaaS platform. The organization does not have visibility into the energy consumption of HireIQ's infrastructure. AI inference workloads consume electricity; at the scale of ~850 applications per year, the direct environmental impact of this specific system is likely low. However, the organization has not requested environmental impact data from HireIQ. Likelihood: Low (impact exists but is likely minimal at this scale). Severity: Low. Affected Communities: Communities near data center locations. Current Mitigations: None specific to this system. Residual Risk: Acceptable — impact is likely minimal; request environmental data from HireIQ at next vendor review.*

---

### 4.4 Information Integrity

*Could this AI system generate, amplify, or be used to spread misinformation? Could AI outputs be mistaken for authoritative human judgments?*

| Element | Assessment |
|---|---|
| **Impact** | [Describe the information integrity concern] |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Communities** | [Which groups are affected] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

*[EXAMPLE] Impact: HireIQ produces AI-generated "match rationale" text explaining why a candidate was scored as they were. If hiring managers treat this rationale as authoritative human judgment rather than AI-generated explanation, they may make decisions based on AI-generated text without appropriate critical evaluation. Likelihood: Medium — hiring managers may not always distinguish AI-generated rationale from human assessment. Severity: Medium — could lead to poor hiring decisions and reinforce AI bias. Affected Communities: Job applicants; the organization's workforce quality. Current Mitigations: HR training includes module on interpreting AI outputs critically; match rationale is labeled as "AI-generated" in the interface. Residual Risk: Acceptable with conditions — training must be refreshed annually; AI labeling must be maintained in any interface updates.*

---

### 4.5 Power Concentration and Vendor Dependency

*Does reliance on this AI vendor create problematic dependencies? Could vendor lock-in, vendor failure, or vendor policy changes create risks for the organization or the people it serves?*

| Element | Assessment |
|---|---|
| **Impact** | [Describe the dependency concern] |
| **Likelihood** | [High / Medium / Low] |
| **Severity** | [Critical / High / Medium / Low] |
| **Affected Communities** | [Which groups are affected] |
| **Current Mitigations** | [Controls already in place] |
| **Residual Risk** | [Acceptable / Acceptable with conditions / Not acceptable] |

*[EXAMPLE] Impact: The organization's hiring process is now dependent on HireIQ's platform. If HireIQ changes its pricing, discontinues the product, or alters its model in ways that introduce new bias, the organization has limited ability to respond quickly. HireIQ controls the model; the organization cannot audit or modify it. Likelihood: Medium — vendor changes are common in the SaaS market. Severity: Medium — hiring process disruption; potential for undetected model changes to introduce new bias. Affected Communities: Job applicants; the organization's ability to hire effectively. Current Mitigations: Contract includes 90-day notice of material model changes; organization maintains manual screening capability as fallback; annual vendor review. Residual Risk: Acceptable with conditions — contract protections must be maintained; fallback capability must be tested annually.*

---

### 4.6 Societal Impact Summary

| Societal Impact Dimension | Likelihood | Severity | Residual Risk |
|---|---|---|---|
| 4.1 Fairness at Scale | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 4.2 Labor Market Effects | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 4.3 Environmental Impact | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 4.4 Information Integrity | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |
| 4.5 Power Concentration/Vendor Dependency | [H/M/L] | [C/H/M/L] | [A / AwC / NA] |

---

## Section 5: Impact Mitigation Measures

*List all mitigation measures identified in Sections 3 and 4. For each mitigation, document implementation status, ownership, and how effectiveness will be verified. This section is the primary evidence record for Annex A control A.5.4.*

| # | Impact Addressed | Mitigation Measure | Implementation Status | Owner | Target Date | Verification Method |
|---|---|---|---|---|---|---|
| M-01 | [Impact dimension] | [Description of mitigation] | Implemented / In Progress / Planned | [Name, Role] | [YYYY-MM-DD] | [How will you confirm this works?] |
| M-02 | | | | | | |
| M-03 | | | | | | |

*[EXAMPLE]*

| *#* | *Impact Addressed* | *Mitigation Measure* | *Implementation Status* | *Owner* | *Target Date* | *Verification Method* |
|---|---|---|---|---|---|---|
| *M-01* | *3.1 Privacy* | *Maintain current Data Processing Agreement with HireIQ; review annually* | *Implemented* | *[Legal/DPO]* | *Annual — [Month YYYY]* | *DPA review documented in vendor file; DPO sign-off* |
| *M-02* | *3.2 Discrimination* | *Obtain and review HireIQ annual bias audit report* | *In Progress* | *[HR Manager]* | *[YYYY-MM-DD]* | *Bias audit report filed; findings reviewed and documented* |
| *M-03* | *3.2 Discrimination* | *HR coordinator manual review of all borderline candidates (scores 40–60)* | *Implemented* | *[HR Coordinator]* | *Ongoing* | *Quarterly spot-check by HR Manager; review log maintained* |
| *M-04* | *3.2 Discrimination / 4.1 Fairness* | *Quarterly shortlist demographic composition review* | *Planned* | *[HR Manager]* | *[YYYY-MM-DD]* | *Quarterly review report; escalation if significant disparity detected* |
| *M-05* | *3.3 Autonomy* | *Applicant disclosure in job postings and application confirmation email* | *In Progress* | *[HR Manager]* | *[YYYY-MM-DD]* | *Disclosure text reviewed; confirmation email template updated* |
| *M-06* | *3.8 Redress* | *Formal appeal procedure documented and communicated in rejection emails* | *Planned* | *[HR Manager]* | *[YYYY-MM-DD]* | *Procedure document created; rejection email template updated; appeals log maintained* |
| *M-07* | *3.4 Safety* | *HR Manager quarterly spot-check of AI shortlists against full applicant pool* | *Planned* | *[HR Manager]* | *[YYYY-MM-DD]* | *Spot-check log; findings documented* |
| *M-08* | *4.4 Information Integrity* | *Annual HR training refresh on interpreting AI outputs critically* | *Planned* | *[HR Manager / L&D]* | *Annual — [Month YYYY]* | *Training completion records* |
| *M-09* | *4.5 Vendor Dependency* | *Annual vendor review including model change assessment* | *Implemented* | *[HR Manager]* | *Annual — [Month YYYY]* | *Vendor review report; contract terms verified* |

---

## Section 6: Residual Impact Assessment

### 6.1 Summary of Residual Impacts

*After all mitigations in Section 5 are implemented, summarize the residual impacts that remain. Be honest — mitigations reduce but rarely eliminate impact.*

[Provide a narrative summary of the residual impacts. Identify the most significant remaining concerns and explain why they are acceptable (or not).]

*[EXAMPLE] After implementation of all mitigations listed in Section 5, the following residual impacts remain:*

*The most significant residual impact is the risk of discriminatory outcomes (3.2). Even with bias audit review and manual review of borderline cases, the AI model may produce biased scores that disadvantage applicants from protected groups. This risk cannot be fully eliminated without replacing the AI system or fundamentally changing how it is used. The organization accepts this residual risk on the condition that: (1) HireIQ's annual bias audit confirms no statistically significant disparate impact; (2) the quarterly demographic review does not reveal systematic exclusion of protected groups; and (3) the manual review and appeal processes remain operational.*

*Privacy (3.1), autonomy (3.3), access (3.6), transparency (3.7), and redress (3.8) risks are all rated "Acceptable with conditions" — the conditions are the mitigation measures in Section 5. These risks are manageable with the controls in place.*

*No impacts are rated "Not acceptable" after mitigations.*

### 6.2 Acceptability Determination

| Determination | ☐ Acceptable | ☐ Acceptable with conditions | ☐ Not acceptable |
|---|---|---|---|

**Selected determination:** [Acceptable / Acceptable with conditions / Not acceptable]

**Rationale:**

[Explain the basis for this determination. Reference the most significant residual impacts and why they are (or are not) within the organization's tolerance.]

*[EXAMPLE] Acceptable with conditions. The AI system may continue to be used for resume screening provided all conditions in Section 6.3 are maintained. The discrimination risk is the primary basis for the "with conditions" determination — this risk requires active, ongoing monitoring and must be escalated immediately if evidence of disparate impact emerges.*

### 6.3 Conditions for Acceptability

*Complete this section only if the determination is "Acceptable with conditions."*

| # | Condition | Owner | Monitoring Frequency |
|---|---|---|---|
| C-01 | [Condition that must be maintained] | [Owner] | [How often monitored] |
| C-02 | | | |

*[EXAMPLE]*
| *#* | *Condition* | *Owner* | *Monitoring Frequency* |
|---|---|---|---|
| *C-01* | *HireIQ annual bias audit report reviewed and no statistically significant disparate impact confirmed* | *HR Manager* | *Annual* |
| *C-02* | *Manual review of all borderline candidates (scores 40–60) maintained* | *HR Coordinator* | *Ongoing; quarterly spot-check* |
| *C-03* | *Quarterly demographic composition review of shortlists conducted* | *HR Manager* | *Quarterly* |
| *C-04* | *Formal appeal procedure communicated in all rejection emails* | *HR Manager* | *Ongoing; reviewed at each template update* |
| *C-05* | *Data Processing Agreement with HireIQ current and reviewed annually* | *Legal/DPO* | *Annual* |

### 6.4 Escalation

**Escalation required?** ☐ Yes — Not Acceptable determination; escalate to senior management immediately  ☐ No

*If "Not Acceptable": Describe the escalation action required and the timeline for resolution. The AI system must not be deployed (or must be suspended if already deployed) until the impact is reduced to an acceptable level.*

---

> **EU AI Act — High-Risk AI Systems**
>
> If this AI system is classified as "high-risk" under the EU AI Act (Regulation 2024/1689), Annex III, **deployers** face additional obligations beyond ISO 42001 compliance. These include:
>
> - Conducting a **Fundamental Rights Impact Assessment (FRIA)** before deploying the system (Article 27)
> - Registering the system in the EU AI Act database (where applicable)
> - Implementing human oversight measures as specified in the provider's instructions for use
> - Maintaining logs of system operation for the period specified in the Act
>
> AI-assisted hiring and recruitment tools are explicitly listed in EU AI Act Annex III (Category 4: Employment, workers management, and access to self-employment) and are presumed high-risk.
>
> **This template does not constitute a Fundamental Rights Impact Assessment under the EU AI Act. Consult qualified legal counsel for EU AI Act compliance obligations.**

---

## Section 7: Monitoring and Review

### 7.1 Ongoing Monitoring

*How will the impacts identified in this assessment be monitored on an ongoing basis? Monitoring should be proportionate to the risk level — High Risk systems require more frequent and rigorous monitoring.*

| Monitoring Activity | Frequency | Responsible Party | Output/Record |
|---|---|---|---|
| [Activity] | [Frequency] | [Owner] | [What is produced] |

*[EXAMPLE]*
| *Monitoring Activity* | *Frequency* | *Responsible Party* | *Output/Record* |
|---|---|---|---|
| *Review HireIQ bias audit report* | *Annual* | *HR Manager* | *Bias audit review memo filed in vendor file* |
| *Demographic composition review of AI shortlists* | *Quarterly* | *HR Manager* | *Quarterly review report; escalation if disparity detected* |
| *Manual review of borderline candidates* | *Per hiring cycle* | *HR Coordinator* | *Review log maintained in HRIS* |
| *Appeal log review* | *Quarterly* | *HR Manager* | *Appeals log; trend analysis* |
| *Vendor contract and DPA review* | *Annual* | *Legal/DPO* | *Vendor review report* |
| *HR team training on AI output interpretation* | *Annual* | *HR Manager / L&D* | *Training completion records* |
| *Full impact assessment review* | *Annual (or per trigger below)* | *HR Manager + Consultant* | *Updated impact assessment document* |

### 7.2 Trigger Events for Reassessment

*The following events require an immediate reassessment of this impact assessment, regardless of the scheduled review date:*

| Trigger Event | Action Required |
|---|---|
| Significant model update by vendor (new version, retraining) | Full reassessment of Sections 3 and 4; request updated bias audit from vendor |
| New use case or expansion of AI system scope | Full reassessment before new use case goes live |
| AI-related incident or near-miss involving this system | Immediate review of relevant impact dimensions; update mitigations |
| Regulatory change (EU AI Act implementation, new employment law) | Legal review; update assessment for new requirements |
| Evidence of disparate impact in demographic monitoring | Immediate escalation; suspend AI screening pending investigation |
| Vendor acquisition, merger, or significant change in vendor status | Vendor reassessment; review DPA and contractual protections |
| Organizational change affecting use of this system | Review scope and affected populations |

### 7.3 Next Scheduled Review

| Field | Value |
|---|---|
| **Next Scheduled Review Date** | [YYYY-MM-DD — no later than 12 months from assessment date] |
| **Review Owner** | [Name, Role] |
| **Review Scope** | ☐ Full reassessment  ☐ Targeted review of specific sections |

---

## Section 8: Approval and Sign-off

*All sign-offs must be obtained before this assessment is considered complete. For High Risk AI systems, Senior Management approval is required. Electronic signatures or documented email approvals are acceptable.*

### 8.1 Assessor Sign-off

*The assessor confirms that this impact assessment has been conducted in good faith, that all identified impacts have been documented, and that the mitigation measures described are accurate to the best of their knowledge.*

| Field | Value |
|---|---|
| **Name** | [Name] |
| **Role** | [Role] |
| **Signature** | _________________________ |
| **Date** | [YYYY-MM-DD] |

### 8.2 AI System Owner Sign-off

*The AI System Owner confirms that the system description in Section 1 is accurate, that the affected populations in Section 2 are complete, and that the mitigation measures in Section 5 are operationally feasible and will be implemented.*

| Field | Value |
|---|---|
| **Name** | [Name] |
| **Role** | [Role — AI System Owner] |
| **Signature** | _________________________ |
| **Date** | [YYYY-MM-DD] |

### 8.3 Senior Management Approval

*Required for all High Risk AI systems. Senior management confirms that the residual impact determination in Section 6 is accepted, that the conditions for acceptability will be resourced and enforced, and that the monitoring program in Section 7 will be maintained.*

| Field | Value |
|---|---|
| **Name** | [Name] |
| **Role** | [Role — Senior Management] |
| **Signature** | _________________________ |
| **Date** | [YYYY-MM-DD] |
| **Applicable?** | ☐ Required (High Risk system)  ☐ Not required (Medium/Low Risk system — optional) |

### 8.4 Legal / DPO Review (if applicable)

*Recommended for High Risk systems and any system processing special category personal data. Legal/DPO confirms that the privacy and regulatory dimensions of this assessment have been reviewed.*

| Field | Value |
|---|---|
| **Name** | [Name] |
| **Role** | [Role — Legal Counsel / Data Protection Officer] |
| **Signature** | _________________________ |
| **Date** | [YYYY-MM-DD] |
| **Applicable?** | ☐ Yes  ☐ No — document reason |

---

## Version History

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Author] | Initial assessment |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
