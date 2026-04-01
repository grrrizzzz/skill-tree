# Internal Procedure: Phase 1 — Discovery & Scoping

> **Current as of:** March 2026 | ISO/IEC 42001:2023

> **Document type:** Internal Procedure — Not for client distribution

---

## 1. Purpose

This procedure defines how to execute Phase 1 of an ISO 42001 readiness engagement. Phase 1 establishes the foundation for the client's AI Management System (AIMS) by:

- Identifying all AI systems in use across the organization, including embedded AI features within existing SaaS platforms
- Mapping interested parties and their requirements per Clause 4.2
- Defining the AIMS scope boundaries per Clause 4.3
- Documenting the organization's internal and external context per Clause 4.1

A junior consultant with ISO management system experience but no prior ISO 42001 experience should be able to execute this procedure by following each step as written.

---

## 2. Scope

This procedure covers the first phase of any ISO 42001 readiness engagement for SMB clients (typically 40–200 employees) that use third-party AI systems. It begins after the Statement of Work (SOW) is signed and ends with the delivery of the Phase 1 Summary Report.

This procedure does not cover AI development, model training, or any activities where the client is acting as an AI developer or AI provider.

---

## 3. Roles

| Role | Responsibility in Phase 1 |
|---|---|
| **Lead Consultant** | Executes this procedure. Conducts all interviews, produces all deliverables, manages timeline. |
| **Client Sponsor** | Executive point of contact. Provides organizational context, authorizes access, removes blockers. Typically CEO, COO, or VP-level. |
| **Client IT Lead** | Primary technical contact. Provides SaaS inventory, data flow information, security control details. |
| **Department Heads** | Provide department-specific AI usage information. Participate in stakeholder interviews. |

---

## 4. Inputs

| Input | Source | Required? | Notes |
|---|---|---|---|
| Signed SOW | 07-business/ | **Yes** | Must be signed before discovery begins |
| Client organizational chart | Client Sponsor | **Yes** | Identifies departments and reporting lines for interview scheduling |
| IT asset inventory | Client IT Lead | Preferred | If unavailable, see Escalation Trigger E-3 |
| Vendor/SaaS contract list | Client IT Lead or Finance | Preferred | Used for embedded AI detection in Step 3 |
| Existing management system documentation | Client Sponsor | If available | ISO 27001 ISMS, ISO 9001 QMS, or similar — leverage existing infrastructure |

---

## 5. Outputs

| Output | Description | Feeds Into |
|---|---|---|
| AI System Inventory | Complete register of all AI systems/tools in use, classified by role, risk, and data sensitivity | Phase 2 Gap Analysis |
| Stakeholder Register | Completed `template-stakeholder-register.md` identifying all interested parties | Phase 2 Gap Analysis, Phase 3 Remediation |
| Draft AIMS Scope Statement | Documented scope boundaries per Clause 4.3 | Phase 2 Gap Analysis, Phase 3 Remediation |
| Phase 1 Summary Report | 1–2 page executive summary of findings, risks, and recommendations | Client Sponsor review, Phase 2 kickoff |

---

## 6. Time Estimate

| Activity | Duration | Notes |
|---|---|---|
| Pre-Discovery Preparation | Day 1 | Internal; no client time required |
| Executive Sponsor Interview | Day 2–3 | 90-minute interview + follow-up |
| IT/Technical Discovery | Day 3–5 | 2-hour interview + SaaS audit |
| Department Stakeholder Interviews | Day 5–8 | 45–60 minutes per department |
| Shadow AI Discovery | Day 5–8 | Parallel with department interviews |
| AI System Classification | Day 8–9 | Internal analysis |
| Scope Definition | Day 9–10 | 60-minute working session with Client Sponsor + IT Lead |
| Deliverable Assembly & Review | Day 10 | Internal quality check |
| **Total elapsed time** | **1–2 weeks** | Depends on client responsiveness and number of departments |

---

## 7. Step-by-Step Procedure

---

### Step 1: Pre-Discovery Preparation (Day 1)

**Objective:** Gather available information before engaging the client. Arrive at the first interview informed.

#### 1.1 Send Document Request to Client

Send the following request to the Client Sponsor within 24 hours of SOW signature. Use this exact list:

**Document Request Email — Copy/Adapt:**

> Subject: ISO 42001 Readiness — Phase 1 Document Request
>
> [Client Sponsor Name],
>
> To prepare for our discovery sessions, please provide the following at your earliest convenience:
>
> 1. Current organizational chart (or equivalent showing departments and reporting lines)
> 2. List of all SaaS platforms and cloud services in use (from IT, procurement, or finance records)
> 3. Vendor contract list or software license inventory
> 4. Any existing IT security policies, acceptable use policies, or data handling policies
> 5. Any existing management system documentation (ISO 27001, ISO 9001, SOC 2, or similar)
> 6. List of key contacts per department (one person per department who can discuss their team's technology usage)
>
> Items 1, 2, and 6 are essential for scheduling and preparing our discovery sessions. The remaining items are helpful but not blocking.
>
> I'll follow up to schedule our first session once I receive items 1 and 6.

#### 1.2 Pre-Meeting Research Checklist

Before the first client interview, complete the following research. Document findings in your working notes.

- [ ] **Company website review:** Services/products offered, company size, locations, markets served
- [ ] **LinkedIn:** Confirm organizational structure, key personnel, recent hires (particularly in IT, compliance, legal)
- [ ] **Industry context:** Identify industry-specific AI use patterns (e.g., real estate firms often use AI-driven CRMs; marketing firms use AI content tools)
- [ ] **Regulatory landscape:** Note any sector-specific AI regulations (healthcare, finance, education) that may affect scope
- [ ] **Existing certifications:** Check for ISO 27001, SOC 2, ISO 9001 badges on website or marketing materials
- [ ] **Known SaaS vendors:** Cross-reference any publicly visible technology partnerships or case studies
- [ ] **News/press:** Recent AI-related announcements, data breaches, or regulatory actions

#### 1.3 Schedule Discovery Interviews

Using the organizational chart and contact list, schedule the following sessions:

| Session | Attendees | Duration | Timing |
|---|---|---|---|
| Executive Sponsor Interview | Client Sponsor (+ COO/CTO if available) | 90 minutes | Day 2 or 3 |
| IT/Technical Discovery | Client IT Lead (+ IT staff if available) | 120 minutes | Day 3, 4, or 5 |
| Department Interviews (one per department) | Department Head or designated lead | 45–60 minutes each | Day 5–8 |
| Scope Definition Working Session | Client Sponsor + IT Lead | 60 minutes | Day 9 or 10 |

**Scheduling notes:**
- Department interviews can run back-to-back but leave 15-minute buffers
- Prioritize departments most likely to use AI: Sales, Marketing, HR, Finance, Customer Support
- If client has fewer than 5 departments, combine into 2–3 interviews by grouping related functions

---

### Step 2: Executive Sponsor Interview (Day 2–3)

**Objective:** Understand the organization's strategic context, AI awareness, risk appetite, and management system maturity. This interview maps to Clause 4.1 (Context of the Organization) and informs Clause 4.2 (Interested Parties).

**Duration:** 90 minutes

**Attendees:** Lead Consultant, Client Sponsor (plus COO/CTO if available)

#### 2.1 Interview Script

Open with a brief orientation (2–3 minutes): explain that this session establishes the big picture — strategy, goals, known AI usage, and organizational readiness. All subsequent sessions will build on what is discussed here.

**Section A: Organization & Strategy (15 minutes)**

1. "Can you give me a brief overview of your organization — what you do, who your customers are, and roughly how many employees you have?"
2. "What are your top 3 business priorities for the next 12 months?"
3. "Where does AI or automation fit into those priorities? Is it a strategic investment area, or more of an operational convenience?"
4. "What prompted the decision to pursue ISO 42001 certification specifically? Was there a trigger — a client request, regulatory concern, board directive, competitive pressure?"

**Section B: AI Awareness & Usage (20 minutes)**

5. "What AI tools or capabilities do you know your organization uses today?" *(Let them answer unprompted first — this reveals their awareness level.)*
6. "Are there AI features within your existing business software that you're aware of? For example, tools that summarize, suggest, auto-complete, or classify content?"
7. "Has anyone in the organization raised concerns about AI — privacy, accuracy, job impact, or anything else?"
8. "Has any customer, partner, or regulator asked about your AI practices or governance?"
9. "Has there been any incident involving AI — an incorrect output that affected a decision, a data exposure, or an employee misusing an AI tool?"

**Section C: Governance & Risk Appetite (20 minutes)**

10. "How would you describe your organization's appetite for risk when it comes to adopting new technology? Conservative, moderate, or aggressive?"
11. "Who currently makes decisions about adopting new software tools? Is there a formal approval process?"
12. "Do you have an existing acceptable use policy for technology, or any policies that mention AI specifically?"
13. "Are there types of data that employees are explicitly prohibited from sharing with external tools? Is that documented anywhere?"
14. "If an employee wanted to start using a new AI tool tomorrow, what would the process look like?"

**Section D: Management System Experience (15 minutes)**

15. "Does your organization currently hold any certifications — ISO 27001, ISO 9001, SOC 2, or similar?"
16. "If yes: How mature is that management system? Do you run regular internal audits, management reviews, and corrective action processes?"
17. "If no: Has your organization ever gone through a formal audit or compliance assessment of any kind?"
18. "Do you have a documented risk management process today, even informally?"

**Section E: Engagement Logistics (15 minutes)**

19. "Who should I work with as the primary IT contact for technical discovery?"
20. "Which departments or business units are most active users of AI-enabled tools?"
21. "Are there any departments, locations, or business functions you'd like to keep out of scope for this engagement, or should we start with the full organization?"
22. "What is your target timeline for achieving certification readiness?"
23. "Are there any upcoming organizational changes — restructuring, mergers, vendor migrations, office moves — that could affect this work?"

#### 2.2 Decision Tree: Existing Management System

After the interview, determine the engagement approach:

```
Does the organization have an existing certified management system (ISO 27001, ISO 9001, etc.)?
│
├── YES
│   ├── Is the existing system actively maintained (audits current, reviews happening)?
│   │   ├── YES → LEVERAGE EXISTING INFRASTRUCTURE
│   │   │   - Map existing processes (document control, internal audit, management review,
│   │   │     corrective action) to ISO 42001 requirements
│   │   │   - Identify integration points between ISMS/QMS and AIMS
│   │   │   - Expect faster Phase 3 remediation (many Clause 7–10 processes already exist)
│   │   │   - Note in Phase 1 Summary: "Integrated management system approach recommended"
│   │   │
│   │   └── NO → ASSESS BEFORE DECIDING
│   │       - Review existing documentation quality
│   │       - Determine if revitalizing existing system is faster than building fresh
│   │       - Note in Phase 1 Summary: "Existing MS requires assessment before integration decision"
│   │
│   └── What is the existing system?
│       ├── ISO 27001 (ISMS) → Highest overlap with ISO 42001. Shared Clause 4–10 structure.
│       │   Data classification, risk assessment, supplier management likely transferable.
│       ├── ISO 9001 (QMS) → Process management, document control, internal audit transferable.
│       │   Risk-based thinking foundation exists. Less technical overlap.
│       └── SOC 2 → Not an ISO management system but indicates audit maturity.
│           Vendor management and access controls may be reusable.
│
└── NO → BUILD FROM SCRATCH
    - All Clause 4–10 processes will need to be created
    - Factor additional time into Phase 3 remediation estimate
    - Client will need management system fundamentals education
    - Note in Phase 1 Summary: "Standalone AIMS build; no existing MS to integrate with"
```

#### 2.3 Post-Interview Actions

- [ ] Transcribe key points within 24 hours
- [ ] Log any AI systems mentioned (even casually) for follow-up during IT discovery
- [ ] Flag any escalation triggers (see Section 9)
- [ ] Update interview schedule if new departments or contacts were identified

---

### Step 3: IT/Technical Discovery (Day 3–5)

**Objective:** Build a comprehensive inventory of AI systems in the organization, including embedded AI features that stakeholders may not recognize as AI. This step directly produces the AI System Inventory.

**Duration:** 120 minutes

**Attendees:** Lead Consultant, Client IT Lead (plus IT staff if available)

#### 3.1 Interview Script — IT Lead

**Section A: Technology Landscape (15 minutes)**

1. "Can you walk me through the major software platforms your organization uses day-to-day? I'm looking for everything — email, CRM, ERP, HR, finance, project management, communications."
2. "How do you manage your SaaS subscriptions? Is there a central inventory, or does each department manage their own?"
3. "Do you use a SaaS management platform (Zylo, Productiv, Torii, or similar) that tracks software across the organization?"

**Section B: Known AI Tools (15 minutes)**

4. "Which tools in your environment do you know have AI or machine learning features — whether or not those features are currently turned on?"
5. "Has the organization deployed any AI-specific tools like ChatGPT Enterprise, GitHub Copilot, Jasper, or similar?"
6. "Are there any API integrations that connect to AI services — for example, applications calling OpenAI, Google Cloud AI, or AWS AI APIs?"

**Section C: Embedded AI Detection (30 minutes)**

*This is the most critical section. Most SMB clients significantly undercount their AI systems because they don't recognize embedded AI features within tools they already use.*

7. "I'm going to walk through your major platforms one by one. For each, I'll ask about specific AI features. This may surface capabilities you use without thinking of them as AI."

**Run through the Embedded AI Detection Checklist (Section 3.2 below) for each platform identified in Question 1.**

**Section D: Data Flows (20 minutes)**

8. "For the AI tools we've identified, what data flows into them? Customer data, employee data, financial data, proprietary business data?"
9. "Where are these AI tools hosted? Cloud-only, on-premises, or hybrid?"
10. "Does any data leave your organization's environment when employees use AI tools — for example, content pasted into ChatGPT or uploaded to an AI summarization tool?"
11. "Are there any data residency or sovereignty requirements your organization must meet?"

**Section E: Security & Access Controls (20 minutes)**

12. "How do you control who has access to AI tools? Is it managed through SSO, individual accounts, or department-level licenses?"
13. "Are AI tool usage logs available? Can you see who used what tool, when, and what data was involved?"
14. "Have you implemented any DLP (data loss prevention) controls that cover AI tools?"
15. "Are there any AI tools that have been explicitly blocked or restricted?"

**Section F: Shadow IT Concerns (15 minutes)**

16. "In your experience, do employees adopt SaaS tools without going through IT? How common is this?"
17. "Have you discovered any unauthorized AI tools in use — browser extensions, free-tier AI services, personal accounts used for work purposes?"
18. "If I wanted to find every cloud service employees are accessing, what tools or logs could we look at?"

#### 3.2 Embedded AI Detection Checklist

For each SaaS platform the client uses, systematically check for AI features. Do not rely on the client to identify these — walk through each platform explicitly.

**Instructions:** For each platform, ask the IT Lead: *"Does [Platform] do any of the following in your environment?"* Check Y/N/Unknown for each feature. Any "Y" or "Unknown" means the platform should be added to the AI System Inventory for further assessment.

**Microsoft 365 / Office 365:**
- [ ] Copilot enabled (Word, Excel, PowerPoint, Outlook, Teams)?
- [ ] Editor suggestions in Word (grammar, style, tone)?
- [ ] Designer suggestions in PowerPoint?
- [ ] Ideas/Analyze Data in Excel?
- [ ] Suggested replies in Outlook?
- [ ] Meeting transcription and summarization in Teams?
- [ ] Microsoft Viva Insights or Viva Topics?

**Google Workspace:**
- [ ] Gemini features enabled in Docs, Sheets, Slides, Gmail?
- [ ] Smart Compose in Gmail?
- [ ] Explore feature in Google Sheets?
- [ ] Auto-generated summaries in Google Docs?
- [ ] Meeting notes in Google Meet?

**Salesforce:**
- [ ] Einstein features enabled (Einstein GPT, Einstein Analytics, Einstein Activity Capture)?
- [ ] Lead scoring or opportunity scoring?
- [ ] Predictive forecasting?
- [ ] Automated case classification?
- [ ] Einstein Search?

**HubSpot:**
- [ ] AI content assistant (blog, email, social)?
- [ ] Predictive lead scoring?
- [ ] Conversation intelligence?
- [ ] AI-powered chatbot?
- [ ] Content recommendations?

**Zoom:**
- [ ] AI Companion (meeting summaries, smart chapters)?
- [ ] Auto-generated meeting notes?
- [ ] Real-time transcription?
- [ ] Smart recording highlights?

**Slack:**
- [ ] Slack AI (channel summaries, thread summaries, search answers)?
- [ ] AI-powered workflow suggestions?
- [ ] Third-party AI bot integrations?

**Customer Support Platforms (Zendesk, Intercom, Freshdesk):**
- [ ] AI-powered ticket routing?
- [ ] Suggested responses for agents?
- [ ] Customer-facing chatbots or virtual agents?
- [ ] Sentiment analysis?
- [ ] Auto-categorization of tickets?

**HR Platforms (BambooHR, Workday, Gusto, Rippling):**
- [ ] AI-assisted resume screening?
- [ ] Automated candidate matching?
- [ ] Employee sentiment analysis?
- [ ] Predictive attrition modeling?
- [ ] Automated performance review drafting?

**Finance/Accounting (QuickBooks, Xero, NetSuite):**
- [ ] Automated transaction categorization?
- [ ] Cash flow forecasting?
- [ ] Invoice processing with OCR/AI extraction?
- [ ] Anomaly or fraud detection?

**Marketing/Content (Canva, Adobe, Mailchimp):**
- [ ] AI-generated design suggestions (Canva Magic Design, Adobe Firefly)?
- [ ] AI copywriting or subject line generation?
- [ ] Send-time optimization?
- [ ] Audience segmentation using AI?

**Project Management (Asana, Monday, Notion, ClickUp):**
- [ ] AI task suggestions or prioritization?
- [ ] AI-generated project summaries?
- [ ] Automated status updates?
- [ ] AI writing assistance within the tool?

**Other Platforms:**
For any platform not listed above, ask these general detection questions:
- "Does this tool auto-complete, suggest, summarize, or classify anything?"
- "Does it predict outcomes, score items, or recommend next actions?"
- "Has the vendor recently added any features described as 'AI-powered,' 'smart,' or 'intelligent'?"
- "Does the tool process your data to generate new content or insights?"

#### 3.3 Post-Interview Actions

- [ ] Compile initial AI System Inventory draft
- [ ] Flag any platforms with "Unknown" AI feature status for vendor confirmation
- [ ] Note data flows for each confirmed AI system
- [ ] Identify any gaps requiring follow-up with IT Lead

---

### Step 4: Department Stakeholder Interviews (Day 5–8)

**Objective:** Understand how each department uses AI tools in practice, what decisions AI informs, and what data enters AI systems from their function. These interviews feed both the AI System Inventory and the Stakeholder Register.

**Duration:** 45–60 minutes per department

**Attendees:** Lead Consultant, Department Head or designated lead

#### 4.1 Interview Script — Department Template

Adapt the following script per department. The core questions are universal; department-specific follow-ups are listed in Section 4.2.

**Opening (2 minutes):**
"Thank you for your time. We're working with [Client Sponsor Name] on an AI governance project. I'd like to understand how your team uses technology, particularly any tools with AI or automation features. There are no wrong answers — I'm interested in how things work day-to-day."

**Section A: Daily Tools & Workflows (15 minutes)**

1. "What software tools does your team use most frequently? Walk me through a typical day."
2. "Which of these tools help your team by suggesting, auto-completing, summarizing, or predicting anything?"
3. "Are there any tools your team uses that you'd describe as 'smart' or 'automated' — tools that seem to learn or adapt over time?"
4. "Has your team adopted any new AI tools in the past 12 months?"

**Section B: AI-Informed Decisions (15 minutes)**

5. "Does your team use any tool outputs to make decisions about people — hiring, performance evaluation, customer treatment, pricing?"
6. "Are there any processes where a tool's recommendation is typically followed without further review?"
7. "When a tool makes a suggestion or recommendation, what does your team do with it? Accept it as-is, review and modify, or use it as one input among many?"
8. "Has there been a situation where an AI tool gave an incorrect or concerning output? What happened?"

**Section C: Data & Privacy (10 minutes)**

9. "What types of data does your team enter into these tools? Customer data, employee data, financial data, proprietary content?"
10. "Does anyone on your team copy-paste content into AI tools like ChatGPT, Copilot, or similar? What kind of content?"
11. "Are there types of data your team knows should not go into external AI tools?"

**Section D: Governance & Concerns (10 minutes)**

12. "Who in your team decides whether to start using a new tool? Is there an approval process?"
13. "Have any team members raised concerns about AI tools — accuracy, privacy, fairness, or job impact?"
14. "Is there anything about how AI is used in your department that you'd like to see improved or governed differently?"

#### 4.2 Department-Specific Follow-Up Questions

**HR / People Operations:**
- "Do you use AI for any part of the hiring process — resume screening, candidate matching, interview scheduling?"
- "Does your HR platform analyze employee sentiment or predict attrition?"
- "Are performance reviews assisted by any AI features?"
- *Why this matters:* AI in HR decisions directly affects individuals and triggers Annex A controls A.5.2, A.5.3 (impact assessment), A.8.2, A.8.3 (informing interested parties), and A.9.5 (human oversight).

**Finance / Accounting:**
- "Does your accounting software auto-categorize transactions or flag anomalies?"
- "Are financial forecasts or cash flow projections generated using AI features?"
- "Do any tools assist with invoice processing or expense approval?"
- *Why this matters:* AI in financial processes may affect reporting accuracy. Relevant controls: A.7.3 (data quality), A.9.4 (responsible use processes).

**Sales / Business Development:**
- "Does your CRM score leads, predict deal outcomes, or suggest next actions?"
- "Are outreach emails or proposals drafted using AI tools?"
- "Do you use any competitive intelligence or market analysis tools with AI features?"
- *Why this matters:* AI-driven sales processes affect customers. Relevant controls: A.8.2 (disclosure of AI interaction), A.6.2.10 (defined use and misuse).

**Marketing:**
- "Do you use AI for content creation — blog posts, social media, email campaigns?"
- "Are audience segments or campaign targeting decisions informed by AI?"
- "Do you use AI for image generation, video editing, or design?"
- *Why this matters:* AI-generated content and targeting raise transparency and fairness concerns. Relevant controls: A.2.3 (responsible AI in policy), A.9.3 (intended use).

**Operations / Customer Support:**
- "Are customer inquiries routed, categorized, or responded to using AI?"
- "Do you use chatbots or virtual agents for customer interactions?"
- "Does your team use AI to summarize calls, extract action items, or analyze sentiment?"
- *Why this matters:* AI in customer-facing processes requires disclosure. Relevant controls: A.8.2 (informing about AI interaction), A.9.5 (human oversight).

**Legal / Compliance:**
- "Do you use AI for contract review, legal research, or regulatory monitoring?"
- "Are any compliance screening or due diligence processes AI-assisted?"
- *Why this matters:* AI in legal processes carries high risk for consequential decisions. Relevant controls: A.5.3 (impact assessment), A.8.5 (enabling human action on AI outputs).

#### 4.3 Post-Interview Actions

- [ ] Update AI System Inventory with any newly discovered tools
- [ ] Add department representatives to Stakeholder Register
- [ ] Document decision patterns (which decisions AI informs, level of human oversight)
- [ ] Flag any high-risk AI uses for deeper assessment in Phase 2

---

### Step 5: Shadow AI Discovery (Day 5–8, Parallel with Step 4)

**Objective:** Identify AI tools in use that were not surfaced through formal interviews — unauthorized tools, personal subscriptions used for work, browser extensions, and free-tier AI services.

**Why this matters:** Shadow AI creates unmanaged risk. Data may be flowing to AI services the organization doesn't know about, creating exposure that won't be captured in the AIMS unless actively discovered.

#### 5.1 Shadow AI Discovery Methods

Execute as many of the following methods as the client's environment supports. Not all methods will be available for every client.

**Method 1: Employee Survey (always available)**

Distribute the following anonymous survey to all employees (or a representative sample in larger organizations). Keep it short — 5 questions.

> **AI Tool Usage Survey**
>
> This brief survey helps us understand how AI tools are used across the organization. Your responses are anonymous and will be used only for governance planning.
>
> 1. Which AI tools do you use for work purposes? (Select all that apply)
>    - [ ] ChatGPT (personal or business account)
>    - [ ] Microsoft Copilot
>    - [ ] Google Gemini
>    - [ ] Claude (Anthropic)
>    - [ ] Grammarly
>    - [ ] Jasper
>    - [ ] Midjourney / DALL-E / other image generators
>    - [ ] GitHub Copilot
>    - [ ] Other (please specify): ___________
>    - [ ] I don't use any AI tools for work
>
> 2. How often do you use AI tools for work tasks?
>    - [ ] Daily
>    - [ ] Weekly
>    - [ ] Monthly
>    - [ ] Rarely
>    - [ ] Never
>
> 3. What types of work tasks do you use AI tools for? (Select all that apply)
>    - [ ] Writing or editing content
>    - [ ] Summarizing documents or emails
>    - [ ] Data analysis or reporting
>    - [ ] Code development
>    - [ ] Customer communication
>    - [ ] Research
>    - [ ] Image or design creation
>    - [ ] Other: ___________
>
> 4. What types of company data have you entered into AI tools? (Select all that apply)
>    - [ ] Customer data (names, emails, account details)
>    - [ ] Employee data (HR information, performance details)
>    - [ ] Financial data (revenue, budgets, forecasts)
>    - [ ] Proprietary content (product plans, strategies, IP)
>    - [ ] General business content (meeting notes, emails)
>    - [ ] None / I'm not sure
>
> 5. Do you use a personal account (not company-provided) for any AI tools used for work?
>    - [ ] Yes
>    - [ ] No
>    - [ ] Not sure

**Method 2: Browser Extension Audit (requires IT support)**

If the organization uses managed devices:
- Request IT pull a list of installed browser extensions across managed browsers
- Search for known AI extensions: Grammarly, Monica AI, Merlin AI, Compose AI, ChatGPT extensions, Copilot sidebar, etc.
- Document which extensions are installed and on how many devices

**Method 3: SaaS Management Platform Query (if available)**

If the client uses a SaaS management platform (Zylo, Productiv, Torii, BetterCloud):
- Request a report of all discovered SaaS applications
- Filter/search for AI-related applications
- Cross-reference against the AI System Inventory from Steps 2–4

**Method 4: Network/DNS Log Review (if IT can support)**

If the client has DNS logging, web proxy logs, or firewall logs:
- Request logs for the past 30–90 days
- Search for domains associated with AI services: openai.com, anthropic.com, gemini.google.com, midjourney.com, jasper.ai, copilot.microsoft.com, etc.
- Aggregate by volume and frequency — identify regular usage patterns vs. one-off access

#### 5.2 Decision Tree: Shadow AI Found

```
Shadow AI tool discovered?
│
├── YES
│   ├── Is the tool processing sensitive data (customer PII, financial, proprietary)?
│   │   ├── YES → HIGH PRIORITY
│   │   │   - Document in AI System Inventory as "Unmanaged — High Risk"
│   │   │   - Flag for immediate discussion with Client Sponsor
│   │   │   - Recommend: Formalize or prohibit within 30 days
│   │   │   - Include in Phase 1 Summary Report as a key finding
│   │   │
│   │   └── NO → MODERATE PRIORITY
│   │       - Document in AI System Inventory as "Unmanaged — Review Required"
│   │       - Include in scope discussion (Step 7)
│   │       - Recommend: Evaluate for formal adoption or prohibition
│   │
│   └── Is the tool used by more than one person/team?
│       ├── YES → Indicates organizational need not being met by approved tools
│       │   - Note pattern in Phase 1 Summary as a governance gap
│       └── NO → Individual usage
│           - May not require organizational action but should be documented
│
└── NO → Document that shadow AI discovery was conducted with negative findings
    (This is itself an audit-useful record)
```

#### 5.3 Post-Discovery Actions

- [ ] Merge shadow AI findings into AI System Inventory
- [ ] Distinguish managed vs. unmanaged AI tools in the inventory
- [ ] Brief Client Sponsor on any high-risk shadow AI findings
- [ ] Recommend governance path (formalize, restrict, or prohibit) for each shadow AI tool

---

### Step 6: AI System Classification (Day 8–9)

**Objective:** Classify all discovered AI systems along three dimensions and map each to applicable Annex A controls. This classification drives the risk assessment in Phase 2 and the Statement of Applicability in Phase 3.

#### 6.1 Classification Framework

For each AI system in the inventory, assign one classification per dimension:

**Dimension 1: Role**

| Classification | Definition | Examples |
|---|---|---|
| **Decision Support** | AI provides information, recommendations, or analysis that a human uses to make a decision | CRM lead scoring, financial forecasting, contract review AI |
| **Automation** | AI executes a task or process with minimal or no human intervention | Auto-categorization of tickets, automated email responses, transaction classification |
| **Communication** | AI generates, translates, summarizes, or enhances communication content | Email drafting assistants, meeting summarizers, chatbots, content generators |
| **Analysis** | AI processes data to surface patterns, anomalies, or insights | Sentiment analysis, anomaly detection, predictive analytics |

**Dimension 2: Risk Level**

| Classification | Criteria | Examples |
|---|---|---|
| **High** | AI output directly affects individuals' rights, opportunities, safety, or financial standing; or AI makes/influences consequential decisions with limited human review | AI-assisted hiring decisions, credit scoring, customer eligibility determinations |
| **Medium** | AI output affects business operations or efficiency; incorrect output would cause operational disruption but not direct harm to individuals | Sales forecasting, inventory prediction, marketing audience segmentation |
| **Low** | AI provides convenience or efficiency; incorrect output would be a minor inconvenience | Grammar checking, meeting transcription, email auto-complete |

**Dimension 3: Data Sensitivity**

| Classification | Definition | Determination Criteria |
|---|---|---|
| **Confidential** | AI processes personal data (PII/PHI), financial data, or trade secrets | Customer records, employee data, proprietary algorithms, financial details |
| **Internal** | AI processes data not intended for public release but not highly sensitive | Internal reports, meeting notes, project plans, draft content |
| **Public** | AI processes only information that is publicly available or intended for public use | Marketing content, published materials, public-facing FAQs |

#### 6.2 Annex A Control Mapping

For each classified AI system, identify the applicable Annex A controls. Use the following mapping guide:

| AI System Characteristic | Applicable Annex A Controls |
|---|---|
| All AI systems in scope | A.2.2, A.2.3 (AI Policy), A.3.2 (Roles), A.4.4 (Awareness), A.6.2.9 (Documentation), A.6.2.10 (Defined Use/Misuse) |
| Third-party AI systems | A.6.2.11 (Third-Party Components), A.10.2 (Suppliers) |
| AI informing decisions about people | A.5.2, A.5.3, A.5.4 (Risk/Impact Assessment), A.8.2, A.8.3 (Informing Interested Parties), A.9.5 (Human Oversight) |
| AI processing sensitive data | A.7.3 (Data Quality), A.7.5 (Data Acquisition), A.8.4 (Access to Interaction Information) |
| AI integrated into business processes | A.6.2.5 (Deployment), A.6.2.6 (Operation and Monitoring), A.6.2.8 (Integration) |
| AI with autonomous features | A.9.4 (Responsible Use Processes), A.9.5 (Human Oversight), A.8.5 (Enabling Human Action) |

#### 6.3 AI System Inventory — Final Format

Compile the inventory using the following structure. One row per AI system.

| # | AI System/Tool | Vendor | Department(s) | Role | Risk Level | Data Sensitivity | Key Annex A Controls | Managed? | Notes |
|---|---|---|---|---|---|---|---|---|---|
| 1 | *Example: Microsoft 365 Copilot* | *Microsoft* | *All* | *Communication, Analysis* | *Medium* | *Internal* | *A.6.2.11, A.10.2, A.4.4, A.6.2.10* | *Yes* | *Licensed enterprise-wide* |
| 2 | *Example: ChatGPT (personal accounts)* | *OpenAI* | *Marketing, Sales* | *Communication* | *Medium* | *Confidential — confirmed customer data entered* | *A.6.2.11, A.10.2, A.7.3, A.8.4* | *No — Shadow AI* | *5 users identified via survey* |
| 3 | *Example: HubSpot Lead Scoring* | *HubSpot* | *Sales* | *Decision Support* | *Medium* | *Confidential* | *A.5.2, A.6.2.6, A.9.3, A.9.5* | *Yes* | *Scores reviewed by sales manager before action* |

#### 6.4 Post-Classification Actions

- [ ] Review classifications with IT Lead for accuracy
- [ ] Identify any systems requiring immediate attention (High Risk + Confidential + Unmanaged)
- [ ] Count total AI systems — if >20, see Escalation Trigger E-2

---

### Step 7: Scope Definition (Day 9–10)

**Objective:** Define the boundaries of the client's AIMS. The scope statement is a required document per Clause 4.3 and will be referenced throughout the engagement.

**Duration:** 60-minute working session with Client Sponsor and IT Lead, preceded by consultant preparation

#### 7.1 Pre-Session Preparation

Before the scope definition session, prepare the following:

- [ ] Completed AI System Inventory (from Steps 2–6)
- [ ] Draft Stakeholder Register (from Steps 2–4)
- [ ] List of organizational units / departments identified
- [ ] List of physical locations / jurisdictions
- [ ] Notes on existing management system scope (if applicable)

#### 7.2 Decision Tree: AIMS Scope Boundaries

Work through the following decisions with the Client Sponsor:

```
ORGANIZATIONAL SCOPE: Which business units are in scope?
│
├── OPTION A: Entire organization
│   - Simpler to manage, no boundary confusion
│   - Appropriate when: <200 employees, AI use is organization-wide
│   - Recommended for most SMB clients
│
├── OPTION B: Specific business units only
│   - Appropriate when: AI use is concentrated in certain units, or phased approach needed
│   - Risk: Must clearly define interfaces between in-scope and out-of-scope units
│   - Document boundary justification
│
└── OPTION C: Phased approach (start with subset, expand later)
    - Appropriate when: >20 AI systems, resource constraints, or organizational readiness varies
    - Define Phase 1 scope and expansion roadmap
    - Ensure initial scope is meaningful (not so narrow that it excludes key risks)

AI SYSTEM SCOPE: Which AI systems are in scope?
│
├── ALL identified AI systems → Recommended for most SMB clients
│   - Simplest approach, avoids boundary disputes during audit
│
├── SUBSET of AI systems → Justify exclusion criteria
│   - Example justification: "AI systems classified as Low Risk with Public data only are
│     excluded from initial scope"
│   - Auditor will ask why excluded systems were left out — prepare justification
│
└── Include unmanaged/shadow AI? → YES, ALWAYS
    - Shadow AI is within the organizational boundary
    - Not including it doesn't make the risk go away
    - Scope should include governance of all AI, whether currently approved or not

SUPPLIER SCOPE: Are third-party AI providers in scope for supplier management?
│
├── YES → Required for any third-party AI in scope
│   - Clause 4.3 requires addressing external interfaces
│   - Annex A.10.2 (Suppliers) and A.6.2.11 (Third-Party Components) apply
│   - Does NOT mean auditing the vendor — means managing the vendor relationship
│
└── Only if AI system is in scope → The supplier management requirement follows the
    AI system. If the system is in scope, its provider is in scope for supplier management.

GEOGRAPHIC/LEGAL SCOPE: Are there jurisdiction-specific considerations?
│
├── Single jurisdiction → Note the jurisdiction in the scope statement
│
├── Multiple jurisdictions → Document each and note applicable AI regulations per jurisdiction
│   - EU: AI Act obligations may apply if serving EU customers
│   - US: State-level AI laws (Colorado, Illinois BIPA, NYC Local Law 144)
│   - Canada: AIDA (if enacted)
│
└── Remote/distributed workforce → Scope typically follows the organization, not the
    employee location, but note any data residency implications
```

#### 7.3 Draft AIMS Scope Statement Template

Complete the following during the working session. This becomes a formal AIMS document.

---

**AI Management System — Scope Statement**

**Organization:** [Legal entity name]

**Scope of the AI Management System:**

[Organization name]'s AI Management System covers the responsible use of AI systems across [all operations / specified business units] in support of [brief description of business activities].

**Organizational boundaries:**
- Business units in scope: [List]
- Locations in scope: [List]
- Employees in scope: [Approximate number]

**AI systems in scope:**
[Reference the AI System Inventory. List system names or state "All AI systems identified in the AI System Inventory dated [date]."]

**External interfaces:**
- Third-party AI providers subject to supplier management: [List key providers]
- Regulatory obligations considered: [List applicable frameworks — ISO 42001, EU AI Act, etc.]

**Exclusions and justifications:**
[List any exclusions with justification. If none: "No exclusions."]

**Applicable ISO/IEC 42001:2023 clauses and controls:**
All clauses (4–10) apply. Annex A control applicability is documented in the Statement of Applicability.

**Approved by:** [Client Sponsor name and role]
**Date:** [Date]

---

#### 7.4 Clause 4.3 Requirements Checklist

Verify the scope statement addresses all Clause 4.3 requirements:

- [ ] External and internal issues relevant to the AIMS purpose are considered (Clause 4.1)
- [ ] Requirements of interested parties are considered (Clause 4.2)
- [ ] Interfaces and dependencies between AIMS activities and other organizational activities are addressed
- [ ] The scope is available as documented information
- [ ] The scope covers all AI systems within the defined boundaries
- [ ] Exclusions are justified (if any)

#### 7.5 Post-Session Actions

- [ ] Finalize Draft AIMS Scope Statement
- [ ] Circulate to Client Sponsor for review and approval signature
- [ ] Note any scope decisions requiring further discussion or board approval

---

### Step 8: Phase 1 Deliverable Assembly & Review (Day 10)

**Objective:** Assemble all Phase 1 deliverables, perform internal quality review, prepare the Phase 1 Summary Report, and hand off to Phase 2.

#### 8.1 Quality Checklist

Before delivering any Phase 1 output to the client, verify:

**AI System Inventory:**
- [ ] Every AI system discovered in Steps 2–6 is included
- [ ] Each entry has all fields completed (vendor, department, role, risk level, data sensitivity, Annex A controls, managed status)
- [ ] Shadow AI findings are clearly marked
- [ ] Classifications are consistent (no High Risk system marked as Public data without explanation)
- [ ] No duplicate entries

**Stakeholder Register:**
- [ ] All interested parties identified in Steps 2–4 are included
- [ ] Both internal and external stakeholders are represented
- [ ] Requirements column references specific ISO 42001 clauses or Annex A controls
- [ ] Priority assignments are justified
- [ ] Register follows the `template-stakeholder-register.md` format

**Draft AIMS Scope Statement:**
- [ ] All Clause 4.3 requirements are addressed (use checklist from Step 7.4)
- [ ] Scope boundaries are unambiguous — an auditor could read this and know exactly what's in and out
- [ ] AI systems referenced in scope match the AI System Inventory
- [ ] Exclusions are justified
- [ ] Client Sponsor has reviewed (or review is scheduled)

**Cross-Deliverable Consistency:**
- [ ] AI systems in the inventory match those referenced in the scope statement
- [ ] Stakeholders in the register align with interested parties referenced in the scope statement
- [ ] Terminology matches the controlled vocabulary (glossary.md) — use "AI system" in formal documents, "AI tool" in working contexts
- [ ] All Annex A control IDs reference the numbering in annex-a-reference.md (A.2–A.10 scheme)

#### 8.2 Phase 1 Summary Report Template

Prepare a 1–2 page executive summary for the Client Sponsor. This report is the primary Phase 1 deliverable and sets expectations for Phase 2.

---

**Phase 1 Summary Report: Discovery & Scoping**

**Client:** [Organization name]
**Date:** [Date]
**Prepared by:** [Consultant name]

**1. Engagement Overview**
[2–3 sentences: what was done, when, who participated]

**2. Key Findings**

*AI System Landscape:*
- Total AI systems identified: [#]
- Managed (formally adopted): [#]
- Unmanaged (shadow AI): [#]
- High-risk systems requiring priority attention: [#]

*Organizational Readiness:*
- Existing management system: [Yes/No — which standard, maturity level]
- AI governance awareness: [High / Moderate / Low]
- Key gaps identified: [2–3 bullet points]

**3. AIMS Scope**
[Summary of agreed scope — 2–3 sentences]

**4. Stakeholder Summary**
- Internal stakeholder groups identified: [#]
- External stakeholder groups identified: [#]
- Key interested parties requiring priority engagement: [List top 3–5]

**5. Risks & Recommendations**
[Bullet-point list of key risks discovered and recommended actions]

**6. Next Steps**
- Phase 2 (Gap Analysis) target start date: [Date]
- Key actions before Phase 2: [List any prerequisites]
- Estimated Phase 2 duration: [Timeframe]

---

#### 8.3 Internal Review Criteria

Before delivering to the client, the Lead Consultant should verify:

- [ ] All deliverables are complete and internally consistent
- [ ] No internal-only language appears in client-facing documents (no references to "our procedure," fee discussions, or internal escalation notes)
- [ ] Sensitive findings (shadow AI, security concerns) are presented factually, not alarmingly
- [ ] Report tone is advisory, not prescriptive — the client owns their AIMS
- [ ] Legal disclaimer is included on client-facing documents

#### 8.4 Handoff to Phase 2

Prepare the following for Phase 2 kickoff:

- [ ] All Phase 1 deliverables finalized and stored in engagement folder
- [ ] AI System Inventory ready for gap analysis assessment
- [ ] Stakeholder Register ready for Clause 4.2 evidence
- [ ] Draft AIMS Scope Statement ready for Clause 4.3 evidence
- [ ] Phase 1 Summary Report delivered to Client Sponsor
- [ ] Phase 2 kickoff meeting scheduled
- [ ] Any open items or blockers documented and assigned

---

## 8. Referenced Documents

| Document | Location | Usage |
|---|---|---|
| Controlled Vocabulary | `00-foundation/glossary.md` | Term definitions used throughout this procedure |
| Annex A Control Reference | `00-foundation/annex-a-reference.md` | Control IDs and applicability ratings referenced in Step 6 |
| Stakeholder Register Template | `01-discovery/template-stakeholder-register.md` | Completed during Steps 2–4, finalized in Step 8 |
| Traceability Matrix | `00-foundation/traceability-matrix.md` | Maps Phase 1 outputs to ISO 42001 clause requirements |

---

## 9. Escalation Triggers

Monitor for the following conditions throughout Phase 1. When triggered, take the specified action.

| ID | Trigger Condition | Action |
|---|---|---|
| **E-1** | Client Sponsor and IT Lead cannot identify any AI systems | Do not accept at face value. This almost always means embedded AI is unrecognized. Return to Step 3.2 (Embedded AI Detection Checklist) and walk through every SaaS platform systematically. If still zero after the checklist, escalate to senior consultant for review. |
| **E-2** | More than 20 AI systems discovered | Assess whether a phased AIMS scope is needed. Discuss with Client Sponsor whether all systems should be in initial scope or if a risk-based subset is appropriate. Adjust Phase 2 and Phase 3 time estimates upward. Document scope limitation rationale. |
| **E-3** | Client has no IT asset inventory or SaaS list | Additional discovery effort required. Allocate 2–3 extra days. Use Method 3 (SaaS management platform) or Method 4 (network log review) from Step 5 if available. If neither is available, the Embedded AI Detection Checklist (Step 3.2) and employee survey (Step 5.1) become the primary discovery methods. |
| **E-4** | Key stakeholders unavailable during Phase 1 window | Notify Client Sponsor immediately. Request executive intervention to secure availability. If stakeholder interviews cannot be completed, document the gap and note which sections of the AI System Inventory and Stakeholder Register are incomplete. Adjust Phase 1 timeline or proceed with caveat in Phase 1 Summary Report. |
| **E-5** | Client is fine-tuning models or building on top of foundation models | Role may not be purely "AI user." Some Annex A controls marked NOT APPLICABLE (A.6.2.2, A.6.2.3) may need reclassification to PARTIALLY APPLICABLE. Flag for scope discussion and SoA adjustment. See glossary entry on "fine-tuning." |
| **E-6** | Client embeds AI outputs in services delivered to their customers | Annex A.10.4 (Provision of AI System to Third Parties) reclassifies from NOT APPLICABLE to FULLY APPLICABLE. Update scope and Annex A control mapping accordingly. |
| **E-7** | Significant shadow AI with sensitive data exposure discovered | Brief Client Sponsor immediately (same day). Recommend interim controls (usage guidance, data handling rules) before formal AIMS policies are in place. Document as high-priority finding in Phase 1 Summary Report. |

---

## 10. Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | March 2026 | [Author] | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 01-Discovery | Internal Use*
