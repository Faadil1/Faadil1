# Faadil Boussari

**Business Analytics × AI Systems × Product Execution**  
Gatineau, Québec, Canada · French / English · MBA, Business Analytics

> I turn ambiguous business problems into measurable systems, decision-ready evidence, and working products.

I work at the intersection of **business analysis, customer insight, data, product thinking, and AI systems**. My professional background spans business performance, customer experience, reporting, process improvement, risk/compliance, ERP environments, and executive decision support. In parallel, I design and ship AI-assisted products that explore agent orchestration, human authority, deterministic safety gates, local inference, verifiable evidence, and decision receipts.

My goal is not to make AI look impressive. It is to make complex systems **useful, testable, explainable, and accountable**.

[Portfolio](https://faadil-boussari.pages.dev) · [Selected work](https://faadil-boussari.pages.dev/work) · [CV — English](https://faadil-boussari.pages.dev/cv/Faadil_Boussari_CV_EN.pdf) · [LinkedIn](https://www.linkedin.com/in/faadil-boussari-331593188/) · [Email](mailto:bfaadil@gmail.com)

---

## What I bring

| Area | What I do |
| --- | --- |
| **Business & performance analysis** | Frame ambiguous questions, identify decision-relevant signals, model scenarios, structure KPIs, and translate analysis into action. |
| **Customer insight / VoC** | Design surveys, recurring listening programs, field research, satisfaction measurement, qualitative/quantitative analysis, and executive reporting. |
| **BI & decision support** | Build dashboards, reporting systems, KPI narratives, and decision-ready outputs with Power BI, Excel, SQL, Python, SAS, and related tools. |
| **AI product & systems design** | Define product mechanisms, agent workflows, human checkpoints, deterministic guards, evidence models, and measurable success conditions. |
| **Product execution** | Move from research → problem framing → PRD → architecture → vertical slice → testing → deployment → evidence → iteration. |
| **Cross-functional communication** | Work in French and English with business, technical, operational, and management stakeholders. |

---

## Current professional focus

My current professional work is centered on **customer experience and analytics in public transit**, including:

- recurring passenger-listening and Voice of Customer programs;
- online and field survey design, distribution, analysis, and reporting;
- response, abandonment, satisfaction, effort, recommendation, and contact-center performance indicators;
- Power BI dashboards designed for management and executive decision-making;
- quantitative and qualitative customer insight;
- service-improvement recommendations;
- scenario analysis and planning support;
- translating operational data into concise, decision-ready narratives.

Alongside this work, I maintain an active build practice across **AI agents, analytics products, agent governance, decision systems, interaction design, automation, and experimental product development**.

---

# Selected public systems

These projects are the clearest representation of how I currently work: define the decision, build the smallest meaningful mechanism, preserve evidence, test negative paths, and keep claim boundaries explicit.

## CALLSHEET ZERO — concurrent multi-agent constraint repair

**Three agents can all be right locally — and still create an impossible shoot.**

[Repository](https://github.com/Faadil1/callsheet-zero) · [Live product](https://callsheet-zero.vercel.app) · [Canonical receipt](https://callsheet-zero.vercel.app/evidence/canonical-run.json)

A film-production coordination system in which Schedule, Talent, and Logistics agents react concurrently to the same disruption. Their individually reasonable decisions can collide over scarce actors, cameras, and vehicles, so a deterministic Constraint Guard refuses an impossible revision and triggers only the targeted repair required.

**Verified vertical slice:**

`disruption → 3 concurrent agents → shared-resource conflicts → COMMIT REFUSED → targeted repair → conflict-free revision → COMMIT ALLOWED`

The project separates probabilistic agent judgment from deterministic operational authority and preserves machine-readable evidence of the live run.

**Themes:** multi-agent systems · concurrency · deterministic constraints · event-driven repair · evidence receipts · Vercel · TypeScript · Mozaik · Anthropic

---

## Skeptara — independent challenge before autonomous execution

[Repository](https://github.com/Faadil1/Faadil1-skeptara-telegraph)

A pre-execution safety layer for autonomous coding agents. Before a dependency-change pull request can become execution-eligible, Skeptara applies deterministic external risk classification and obtains bounded, paid counter-evidence through Telegraph.

The proposing agent does **not** score or audit itself. Missing coverage, material counter-evidence, stale bindings, or unresolved ambiguity fail closed.

The public proof includes a challenged dependency change that was blocked with no merge call and a clean case that passed exact-head revalidation before a real bounded merge.

**Themes:** AI-agent governance · independent challenge · risk-proportional scrutiny · x402 · Telegraph · GitHub automation · fail-closed execution

---

## Spondee — agents measured by what they deliver

[Repository](https://github.com/Faadil1/Spondee)

**In development.** Spondee is a calibrated outcome marketplace for BSC agents. Instead of comparing agents through vague descriptions, users compare task-specific promises — expected outcome, confidence, downside, cost, and timing — and receive an **Outcome Receipt** comparing the promise with the observed result.

The product direction includes an **Intervention Advantage** concept: where measurable, compare agent performance against an observed no-agent/manual baseline rather than treating automation itself as proof of value.

**Themes:** agent evaluation · measurable promises · outcome receipts · BNB Agent Studio · BSC testnet · product specification · evidence-led development

---

## RELATIONAL KEY — interaction as a causal relationship

[Repository](https://github.com/Faadil1/relational-key-three-poc)

A Three.js interaction research system built around one invariant:

**The relational pair remains the product.**

Instead of treating 3D objects as decorative assets, each interaction is designed around a causal relationship:

`PAIR MEMBER → RELATION → OTHER MEMBER RESPONSE`

The program has been developed as a multi-family global interaction collection with regression gates and explicit validation across cultural and mechanical interaction families.

**Themes:** Three.js · interaction design · causal UI · design systems · accessibility · regression testing · cultural/mechanical research

---

## Matchday Pulse — autonomous fraud investigation workflow

[Repository](https://github.com/Faadil1/-matchday-pulse-data)

A multi-step investigation workflow that turns a vague anomaly signal into a traceable fraud recommendation using **synthetic transaction data**.

The system establishes a baseline, detects an anomalous zone, narrows the pattern, attributes activity to device fingerprints, isolates the time window, and produces a traceable recommendation without requiring human prompting at every investigation step.

**Stack used:** Google ADK · Gemini on Vertex AI · MongoDB MCP / Atlas · Cloud Run · React

**Evidence boundary:** the data and financial figures in the project are synthetic; the system demonstrates the investigation workflow, not a real production fraud decision.

---

## EdgeVoC — private, local customer-feedback analysis

[Repository](https://github.com/Faadil1/edgevoc-qvac)

A local edge-AI workflow that turns customer feedback into themes, pain points, risk signals, recommendations, and an executive brief **without sending the feedback to an external AI API during inference**.

A validation run processed feedback locally on a Windows laptop using a compact quantized model through the QVAC SDK.

**Themes:** local inference · privacy-preserving analysis · customer insight · structured reporting · edge AI

---

## CaseRelay — permission-gated AI workflow

[Repository](https://github.com/Faadil1/caserelay-terminal3)

A permission-gated workflow for sensitive customer cases. The system scopes access, presents an explicit human approval checkpoint, and only allows the protected action after authorization, producing a traceable receipt of the decision.

**Themes:** human-in-the-loop authority · agent permissions · sensitive workflows · authorization receipts · Terminal 3 Agent Auth SDK · Cloud Run

---

## Settlement Sentinel — verifiable data pipeline with explicit partial-proof boundaries

[Repository](https://github.com/Faadil1/settlement-sentinel)

A World Cup market-resolution cockpit that runs a disputed-stat claim through TxLINE devnet APIs and a Solana program while showing each proof stage honestly.

The project deliberately preserves a **partial-proof** state when the final Merkle proof check does not pass rather than presenting an upstream successful call as complete verification.

**Themes:** verifiable data · Solana devnet · TxLINE · proof pipelines · failure transparency · evidence boundaries

---

## More public experimentation

My public repositories also cover experiments in:

- verifiable and auditable AI workflows;
- privacy and permission systems;
- agent decision receipts;
- robotics and safety-gated execution;
- ZK / blockchain-oriented verification;
- local AI inference;
- analytics and forecasting;
- design assurance and interaction systems;
- workflow automation;
- hackathon product development under strict evidence constraints.

Browse the full set at [github.com/Faadil1](https://github.com/Faadil1).

---

# Professional case studies

My portfolio also documents professional work as anonymized case studies where confidentiality matters.

## Voice of Customer Program

[Case study](https://faadil-boussari.pages.dev/work/voice-of-customer)

Designed the analytical and operational structure for a recurring customer-listening program connecting survey findings to service improvement and planning.

My contribution included survey/program design, quantitative and qualitative analysis, field coordination, recurring reporting, recommendations, annual planning, management presentations, and translating findings into executive-ready outputs.

---

## Paratransit Customer Experience

[Case study](https://faadil-boussari.pages.dev/work/paratransit-customer-experience)

Designed a bilingual satisfaction program around key service moments while incorporating accessibility, consent, participant recruitment, and responsible data governance.

The work connected customer research design with operational service questions rather than treating accessibility as a simple translation exercise.

---

## Return-to-Office Revenue Model

[Case study](https://faadil-boussari.pages.dev/work/return-to-office-revenue)

Structured a scenario-based analysis of how changing workplace-attendance patterns could affect transit demand and revenue.

Rather than forcing a single forecast, the work compared relevant signals, modeled a range of plausible outcomes, and translated those scenarios into planning implications.

---

# Selected professional experience

## Customer Experience / Analytics — Public Transit
**Current**

- Design and analyze customer surveys and recurring listening programs.
- Build executive-facing reporting and Power BI dashboards.
- Work with customer-experience and operational KPIs, including satisfaction, effort, recommendation, response, abandonment, and contact-center measures.
- Coordinate field-research logistics and translate findings into service-improvement recommendations.
- Support planning through structured analysis and scenario thinking.

## Business Analyst — Government of Canada
**2023–2024**

- Supported analytical and reporting workflows using Power BI, SAS, and SAP-based environments.
- Conducted exploratory analysis and translated data into decision-support outputs.
- Contributed to forecasting, compliance/financial reporting, data validation, and stakeholder reporting.
- Built and improved dashboards used to surface critical metrics.

## Functional Analyst — TELUS Health
**2023**

- Performed data validation and integrity checks supporting financial and operational reporting.
- Worked with client/member needs, service requests, process improvement, and compliance-oriented workflows.
- Proposed analytical and automation-oriented improvements to recurring processes.

## Junior Business Analyst — Wedacy
**2020–2023**

- Documented business and technical processes.
- Supported ERP deployments and operational workflows.
- Worked with Dynamics 365 inventory processes.
- Presented recommendations aligned with business objectives and implementation constraints.

---

# Capabilities

### Business analysis & decision support
- problem framing and requirements analysis
- business-process analysis
- KPI design and performance measurement
- scenario modeling
- decision-support reporting
- executive synthesis and presentation
- risk, compliance, and data-integrity thinking
- ERP/process improvement

### Customer insight & analytics
- Voice of Customer programs
- survey design and research operations
- quantitative and qualitative analysis
- customer-experience measurement
- CSAT / CES / NPS-oriented analysis
- response and abandonment analysis
- service-moment mapping
- accessible/bilingual research design
- insight-to-action reporting

### BI, data & modeling
- Power BI
- Excel
- SQL
- Python
- R
- SAS
- predictive modeling
- exploratory data analysis
- dashboard design
- forecasting and scenario analysis
- data validation and reporting automation

### Product & AI systems
- product discovery and mechanism design
- living PRDs and requirement evolution
- agent workflow design
- multi-agent orchestration
- human-in-the-loop / human-on-the-loop authority
- deterministic safety and constraint gates
- agent evaluation and outcome receipts
- evidence-led product development
- local/private AI inference
- MCP-based integrations
- negative-path and failure-mode testing

### Build and deployment tools used across projects
- TypeScript / JavaScript
- React
- Astro
- Node.js
- Three.js
- Remotion
- Git / GitHub / GitHub Actions
- Vercel
- Google Cloud Run
- Google ADK
- Gemini / Vertex AI
- Anthropic Claude
- MongoDB / Atlas / MCP
- local Llama-family inference / QVAC
- Solana devnet
- BSC testnet / BNB Agent Studio
- Telegraph / x402 experimentation
- Figma

I separate **core professional expertise** from tools I use experimentally across product builds. Breadth is useful; evidence of what each tool actually did is more important.

---

# How I work

A pattern runs through both my professional analysis and my technical projects:

1. **Clarify the decision before selecting the method.**
2. **Separate observed evidence from assumptions.**
3. **Define the smallest mechanism that could prove or disprove the idea.**
4. **Write the product intent and constraints down.**
5. **Build a vertical slice before expanding the surface area.**
6. **Keep hard invariants deterministic when probabilistic judgment is inappropriate.**
7. **Test both success and failure paths.**
8. **Preserve receipts, artifacts, logs, or reproducible evidence.**
9. **Make limitations and claim boundaries explicit.**
10. **Design the final output for the person who must make a decision.**

This is why many of my repositories contain more than application code: they also contain PRDs, canonical state, evidence ledgers, test artifacts, decision records, handovers, and explicit validation gates.

---

# AI-assisted development

I use AI extensively as a production multiplier for **research, ideation, implementation, debugging, code review, documentation, testing, and iteration**.

I do not treat AI-generated output as self-validating. My role is to own the **problem definition, product mechanism, architecture choices, integration decisions, evidence standard, testing, acceptance criteria, and final judgment**.

Where relevant, I distinguish explicitly between:

- live execution;
- deterministic replay;
- simulation;
- synthetic data;
- testnet/devnet activity;
- partial proof;
- production-ready claims.

That distinction is part of the product, not an afterthought.

---

# Best-fit roles

The strongest fit is work where **business understanding, analytics, systems thinking, and AI-enabled execution** need to coexist, including:

- Business Performance Analyst
- Business / Systems Analyst
- Customer Insights / CX Analyst
- Product Analyst
- Data / BI Analyst
- Analytics Product roles
- AI Systems / AI Product Analyst
- Strategy & Operations roles with strong analytics
- Product Operations / Technical Operations
- AI workflow, evaluation, or governance-oriented roles

I am especially interested in environments where the expectation is not just to produce analysis, but to **turn evidence into a better decision, workflow, or product**.

---

# Education

### MBA — Business Analytics
**Université Laval** · Québec, Canada · completed 2024

### Bachelor's — Administrative Sciences, Finance
**Université du Québec en Outaouais** · Québec, Canada

### Selected certifications / professional training
- Python for Data Analysis and Visualization
- SAS Programming Certification
- Agile Project Management Certification
- CFI Corporate Finance Foundations Professional Certificate
- Anaconda Python for Data Science Professional Certificate

---

# Languages

- **French:** Native / fluent
- **English:** Professional fluency

---

# Contact

**Portfolio:** [faadil-boussari.pages.dev](https://faadil-boussari.pages.dev)  
**Selected work:** [faadil-boussari.pages.dev/work](https://faadil-boussari.pages.dev/work)  
**CV:** [English PDF](https://faadil-boussari.pages.dev/cv/Faadil_Boussari_CV_EN.pdf)  
**LinkedIn:** [Faadil Boussari](https://www.linkedin.com/in/faadil-boussari-331593188/)  
**GitHub:** [@Faadil1](https://github.com/Faadil1)  
**Email:** [bfaadil@gmail.com](mailto:bfaadil@gmail.com)

---

*Profile refreshed for the 2026 portfolio. The projects above intentionally distinguish shipped/live evidence, work in development, synthetic data, testnet/devnet activity, and partial proofs rather than collapsing them into a single “built” claim.*
