# Enterprise and Government AI Deployment Guides and Tools

This is a curated, annotated guide to enterprise and government AI deployment. It brings together practical resources for AI strategy, readiness, governance, procurement, security, evaluation, implementation, operations, and workforce adoption. Use it to move from an AI idea to a defensible deployment plan.

This guide favors material that helps a team make a decision or produce evidence—not AI news, generic product lists, or claims without a usable method behind them. It is maintained by [Decision Terrain](https://decisionterrain.com/) and includes clearly labeled Decision Terrain resources.

**Catalog last reviewed:** September 28, 2026

## Contents

- [Start here](#start-here)
- [From Decision Terrain](#from-decision-terrain)
- [Guides and playbooks](#guides-and-playbooks)
- [Planning and assessment tools](#planning-and-assessment-tools)
- [Templates and checklists](#templates-and-checklists)
- [Frameworks, standards, and policy](#frameworks-standards-and-policy)
- [Technical tools](#technical-tools)
- [Procurement and vendor resources](#procurement-and-vendor-resources)
- [Training and workforce](#training-and-workforce)
- [Case studies and reference implementations](#case-studies-and-reference-implementations)
- [Communities and continuing research](#communities-and-continuing-research)
- [Contributing, curation, and disclosures](#contributing-curation-and-disclosures)
- [License](#license)

## Start here

You do not need to begin with a model or vendor. Begin with the mission or business outcome, the people affected, the information and systems involved, the consequence of error, and the evidence that would justify the next commitment.

### Choose a starting point

- **Planning your first AI initiative:** begin with [Guides and playbooks](#guides-and-playbooks), then use the [Planning and assessment tools](#planning-and-assessment-tools).
- **Establishing AI governance:** compare the [Frameworks, standards, and policy](#frameworks-standards-and-policy), then adapt the [Templates and checklists](#templates-and-checklists).
- **Evaluating AI products or vendors:** use the [Procurement and vendor resources](#procurement-and-vendor-resources) alongside the [Technical tools](#technical-tools).
- **Preparing an AI system for deployment:** review the [Technical tools](#technical-tools) and relevant [Case studies and reference implementations](#case-studies-and-reference-implementations).
- **Building organizational capability:** start with [Training and workforce](#training-and-workforce), then assess readiness with the [Planning and assessment tools](#planning-and-assessment-tools).

Tags make the catalog easier to scan:

- **Audience:** `Government`, `Enterprise`
- **Topic:** `Strategy`, `Governance`, `Security`, `Procurement`, `Evaluation`, `Operations`, `Workforce`
- **Access:** `Free`, `Paid`, `Open Source`
- **Affiliation:** `Decision Terrain`

### Editor's picks

- **[NIST AI Risk Management Framework and Playbook](https://airc.nist.gov/)** — A strong common language for governing, mapping, measuring, and managing AI risk, with suggested actions that teams can adapt to their context. Start here when several functions need a shared risk structure.
  `Government` `Enterprise` `Governance` `Free`

- **[AI Playbook for the UK Government](https://www.gov.uk/government/publications/ai-playbook-for-the-uk-government/artificial-intelligence-playbook-for-the-uk-government-html)** — An unusually readable end-to-end guide covering AI limitations, secure and responsible use, commercial involvement, lifecycle management, human control, and assurance.
  `Government` `Strategy` `Governance` `Free`

- **[AI Guide for Government](https://coe.gsa.gov/coe/ai-guide-for-government/)** — A U.S. General Services Administration guide for leaders considering AI investment, organizational capability, project delivery, and responsible implementation.
  `Government` `Strategy` `Operations` `Free`

- **[People + AI Guidebook](https://pair.withgoogle.com/guidebook-v2/)** — Google PAIR's vendor-authored but product-agnostic methods for defining user needs, setting success criteria, explaining AI behavior, designing feedback, and planning for failure.
  `Enterprise` `Strategy` `Evaluation` `Free`

- **[Guidelines for Secure AI System Development](https://www.ncsc.gov.uk/collection/guidelines-secure-ai-system-development)** — Lifecycle guidance from the UK National Cyber Security Centre and international partners covering secure design, development, deployment, operation, and maintenance.
  `Government` `Enterprise` `Security` `Operations` `Free`

## From Decision Terrain

> **Disclosure:** Decision Terrain maintains this repository and offers AI software and consulting. Resources in this section are featured because of that affiliation, and every DT entry elsewhere in the guide carries the `Decision Terrain` tag. Third-party Editor's Picks are not paid placements.

- **[Free AI Checklists and Planning Tools](https://decisionterrain.com/tools)** — Browser-based tools for AI readiness, technology comparison, prototype planning, NIST AI RMF review, generative AI risk review, and LLM security review. The tools require no account; follow each tool's warning about sensitive inputs and local browser storage.
  `Government` `Enterprise` `Strategy` `Governance` `Evaluation` `Security` `Free` `Decision Terrain`

- **[Decision Terrain Resource Center](https://decisionterrain.com/resources)** — Practical guides on AI readiness, vendor evaluation, prototyping, air-gapped architectures, controlled model updates, and forward-deployed implementation.
  `Government` `Enterprise` `Strategy` `Evaluation` `Operations` `Free` `Decision Terrain`

- **[AI Strategy and Readiness](https://decisionterrain.com/ai-strategy-readiness)** — A paid Decision Terrain service for defense and national-security teams that need to prioritize opportunities, identify readiness gaps, and turn uncertainty into an evidence-driven roadmap.
  `Government` `Strategy` `Paid` `Decision Terrain`

- **[Rapid AI Prototyping](https://decisionterrain.com/rapid-ai-prototyping)** — A paid Decision Terrain service for testing one consequential technical or workflow assumption before a program commits to a broader pilot or deployment.
  `Government` `Enterprise` `Evaluation` `Paid` `Decision Terrain`

## Guides and playbooks

- **[NIST AI RMF Playbook](https://airc.nist.gov/airmf-resources/playbook/)** — Suggested actions and documentation practices organized around every NIST AI RMF subcategory. It is a menu of adaptable practices, not a universal checklist.
  `Government` `Enterprise` `Governance` `Free`

- **[AI Playbook for the UK Government](https://www.gov.uk/government/publications/ai-playbook-for-the-uk-government/artificial-intelligence-playbook-for-the-uk-government-html)** — Practical lifecycle guidance for public organizations, including secure use, meaningful human control, commercial engagement, skills, and assurance.
  `Government` `Strategy` `Governance` `Free`

- **[AI Guide for Government](https://coe.gsa.gov/coe/ai-guide-for-government/)** — A living U.S. federal guide addressing investment, organization, project implementation, accountability, and capability maturity.
  `Government` `Strategy` `Operations` `Free`

- **[People + AI Guidebook](https://pair.withgoogle.com/guidebook-v2/)** — Google PAIR's vendor-authored design patterns, worksheets, and case studies for human-centered AI products and services.
  `Enterprise` `Strategy` `Evaluation` `Free`

- **[Guidelines for Secure AI System Development](https://www.ncsc.gov.uk/collection/guidelines-secure-ai-system-development)** — International secure-by-design guidance for teams building systems with internally hosted models or third-party AI APIs.
  `Government` `Enterprise` `Security` `Operations` `Free`

- **[What AI Readiness Means for a Defense Program](https://decisionterrain.com/resources/what-ai-readiness-means-for-defense-programs)** — A Decision Terrain guide connecting mission value, data, integration, governance, evaluation, and adoption to a concrete next decision.
  `Government` `Strategy` `Free` `Decision Terrain`

- **[Air-Gapped Agentic AI Architecture](https://decisionterrain.com/resources/air-gapped-agentic-ai-architecture)** — A Decision Terrain reference for separating identity, orchestration, inference, tools, data, observability, evaluation, and controlled updates inside an isolated environment.
  `Government` `Security` `Operations` `Free` `Decision Terrain`

## Planning and assessment tools

- **[Mission AI Readiness Worksheet](https://decisionterrain.com/resources/mission-ai-readiness-worksheet)** — A short Decision Terrain worksheet for examining mission ownership, data, integration, governance, evaluation, and adoption before planning a test.
  `Government` `Enterprise` `Strategy` `Free` `Decision Terrain`

- **[AI Technology Evaluation Scorecard](https://decisionterrain.com/resources/ai-technology-evaluation-scorecard)** — A Decision Terrain worksheet for comparing two options against weighted mission, technical, security, integration, lifecycle, and evidence criteria.
  `Government` `Enterprise` `Evaluation` `Free` `Decision Terrain`

- **[AI in Government Suitability Canvas](https://oecd-opsi.org/toolkits/ai-in-government-suitability-canvas/)** — An OECD canvas that asks teams to define the problem, compare non-AI alternatives, and test whether AI adds enough public value to justify its costs and risks.
  `Government` `Strategy` `Free`

- **[Algorithmic Impact Assessment](https://open.canada.ca/aia-eia-js/)** — The Government of Canada's browser-based questionnaire for assessing the impacts of an automated decision system; answers remain on the user's computer unless exported.
  `Government` `Governance` `Free` `Open Source`

- **[Pathway to AI Readiness](https://www.ai.mil/Initiatives/About/Resources/Pathway-to-AI-Readiness/)** — The U.S. Department of Defense CDAO's adaptable set of readiness dimensions, questions, knowledge, and tools for organizations adopting data, analytics, and AI.
  `Government` `Strategy` `Free`

- **[AI Maturity Model for Government Agencies](https://www.cna.org/analyses/2025/05/artificial-intelligence-maturity-model)** — A detailed CNA model for assessing current and target capabilities across governance, resources, impact, trustworthiness, safety, and security.
  `Government` `Strategy` `Governance` `Free`

## Templates and checklists

- **[Algorithmic Transparency Recording Standard Hub](https://www.gov.uk/government/collections/algorithmic-transparency-recording-standard-hub)** — The UK Government's template, completion guidance, scope policy, and published records for documenting how public bodies use algorithmic tools.
  `Government` `Governance` `Free`

- **[AI Impact Assessment Guide and Template](https://www.microsoft.com/ai/responsible-ai-resources)** — Microsoft's vendor-authored internal assessment method, released publicly to help teams identify intended uses, affected stakeholders, benefits, limitations, and potential harms.
  `Government` `Enterprise` `Governance` `Free`

- **[AI and Data Protection Risk Toolkit](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/ai-and-data-protection-risk-toolkit/)** — A downloadable spreadsheet from the UK Information Commissioner's Office for identifying and reducing data-protection risks. The ICO currently marks the guidance as under review, so confirm applicable law before relying on it.
  `Government` `Enterprise` `Governance` `Free`

- **[GovAI Coalition Templates and Resources](https://www.sanjoseca.gov/your-government/departments-offices/information-technology/artificial-intelligence-inventory/govai-coalition/templates-resources)** — Reusable state and local government materials including policy templates, an algorithmic impact assessment, a buyer's guide, performance-measure guidance, and leadership questions.
  `Government` `Governance` `Procurement` `Free`

- **[AI Prototype Test-Plan Builder](https://decisionterrain.com/resources/ai-prototype-test-plan)** — A Decision Terrain worksheet that turns one uncertainty into a printable test plan with measures, evidence needs, failure conditions, and a decision gate.
  `Government` `Enterprise` `Evaluation` `Free` `Decision Terrain`

## Frameworks, standards, and policy

- **[NIST AI Risk Management Framework](https://airc.nist.gov/airmf-resources/airmf/)** — A voluntary, cross-sector framework for managing risks and incorporating trustworthiness into the design, development, use, and evaluation of AI systems.
  `Government` `Enterprise` `Governance` `Free`

- **[NIST Generative AI Profile](https://airc.nist.gov/technical-reports/)** — The NIST AI RMF companion profile for risks and risk-management actions that are distinctive to or intensified by generative AI.
  `Government` `Enterprise` `Governance` `Security` `Free`

- **[U.S. OMB Memoranda](https://www.whitehouse.gov/omb/information-resources/guidance/memoranda/)** — The authoritative index for current federal memoranda, including AI use, governance, acquisition, and LLM procurement requirements. Federal teams should check this index for newer or superseding guidance.
  `Government` `Governance` `Procurement` `Free`

- **[ISO/IEC 42001:2023](https://www.iso.org/standard/42001)** — Requirements for establishing, operating, maintaining, and continually improving an AI management system. The overview is free; the complete standard is sold by ISO and national standards bodies.
  `Government` `Enterprise` `Governance` `Paid`

- **[OECD AI Principles](https://oecd.ai/en/ai-principles)** — Intergovernmental principles for innovative and trustworthy AI, with recommendations for policy and a lifecycle-oriented risk-management expectation.
  `Government` `Enterprise` `Governance` `Free`

- **[EU Artificial Intelligence Act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng)** — The official EUR-Lex text of Regulation (EU) 2024/1689. Use the consolidated/current version and qualified legal advice when determining obligations.
  `Government` `Enterprise` `Governance` `Free`

- **[OWASP Top 10 for LLM and Generative AI](https://genai.owasp.org/initiative/owasp-top-10-for-llm-and-genai/)** — A community-maintained security risk reference for applications built with language models, generative AI, and increasingly agentic components.
  `Government` `Enterprise` `Security` `Free` `Open Source`

## Technical tools

- **[Inspect](https://inspect.aisi.org.uk/)** — An open-source framework from the UK AI Security Institute and Meridian Labs for writing and running reproducible model and agent evaluations with datasets, tools, solvers, and scorers.
  `Government` `Enterprise` `Evaluation` `Free` `Open Source`

- **[Dioptra](https://github.com/usnistgov/dioptra)** — NIST's test platform for designing, executing, and tracking reproducible experiments that assess trustworthy characteristics of AI technologies.
  `Government` `Enterprise` `Evaluation` `Free` `Open Source`

- **[PyRIT](https://github.com/microsoft/pyrit)** — Microsoft's open-source Python Risk Identification Tool for automating and scaling security and safety red-team workflows against generative AI systems.
  `Government` `Enterprise` `Security` `Evaluation` `Free` `Open Source`

- **[garak](https://github.com/NVIDIA/garak)** — NVIDIA's open-source LLM vulnerability scanner for probing prompt injection, data leakage, hallucination, jailbreak, toxicity, and other failure classes across multiple model interfaces.
  `Government` `Enterprise` `Security` `Evaluation` `Free` `Open Source`

- **[MLflow](https://mlflow.org/docs/latest/)** — A Linux Foundation open-source platform for experiment tracking, model lifecycle management, generative AI evaluation, tracing, prompt management, and production observability.
  `Government` `Enterprise` `Evaluation` `Operations` `Free` `Open Source`

- **[MITRE ATLAS](https://atlas.mitre.org/)** — A living knowledge base of adversary tactics, techniques, mitigations, and case studies for predictive, generative, and agentic AI systems.
  `Government` `Enterprise` `Security` `Free`

- **[NIST AI Metrology Center](https://airc.nist.gov/metrology/)** — A catalog connecting metrics, measurement methods, and tools to NIST AI RMF characteristics and lifecycle stages; inclusion is not a NIST endorsement of a tool.
  `Government` `Enterprise` `Evaluation` `Free`

## Procurement and vendor resources

- **[Buy AI](https://www.gsa.gov/artificial-intelligence/buy-ai)** — Current GSA procurement routes and practical acquisition guidance for U.S. federal teams, including scoping, data protection, stakeholder involvement, authorization, and cost control.
  `Government` `Procurement` `Free`

- **[OMB M-25-22: Driving Efficient Acquisition of AI in Government](https://www.whitehouse.gov/wp-content/uploads/2025/02/M-25-22-Driving-Efficient-Acquisition-of-Artificial-Intelligence-in-Government.pdf)** — The official OMB memorandum for federal AI acquisition policy; check the OMB memoranda index for subsequent or superseding requirements.
  `Government` `Procurement` `Governance` `Free`

- **[Guidelines for AI Procurement](https://www.gov.uk/government/publications/guidelines-for-ai-procurement/guidelines-for-ai-procurement)** — UK public-sector guidance covering preparation, market engagement, requirements, supplier evaluation, contracting, data, transparency, and ongoing management.
  `Government` `Procurement` `Governance` `Free`

- **[AI Procurement in a Box](https://www.weforum.org/publications/ai-procurement-in-a-box/project-overview/)** — A World Economic Forum package with government procurement principles, a risk assessment, specification and evaluation tools, and implementation case studies. It predates recent generative AI policy, so pair it with current rules.
  `Government` `Procurement` `Free`

- **[GovAI Coalition Buyer's Guide and Contract Resources](https://www.sanjoseca.gov/your-government/departments-offices/information-technology/artificial-intelligence-inventory/govai-coalition/templates-resources)** — Practitioner-created questions, templates, and shared materials for state and local agencies evaluating enterprise generative AI products and contracts.
  `Government` `Procurement` `Free`

- **[How to Evaluate an AI Vendor Beyond the Demonstration](https://decisionterrain.com/resources/evaluate-ai-vendor-beyond-demo)** — A Decision Terrain guide for testing vendor claims against the intended workflow, operating environment, lifecycle obligations, and evidence required for a decision.
  `Government` `Enterprise` `Procurement` `Evaluation` `Free` `Decision Terrain`

## Training and workforce

- **[InnovateUS Self-Paced Courses](https://innovate-us.org/course)** — Free role-aware courses for public professionals on responsible AI use, organizational implementation, legal work, human-centered design, and public-sector problem solving.
  `Government` `Workforce` `Free`

- **[Elements of AI](https://www.helsinki.fi/en/admissions-and-education/open-university/multidisciplinary-themed-modules/artificial-intelligence-collection)** — Free University of Helsinki courses for non-specialists and practitioners covering AI fundamentals, building AI, societal impacts, and ethics.
  `Government` `Enterprise` `Workforce` `Free`

- **[Artificial Intelligence Skills for All](https://www.gov.uk/guidance/artificial-intelligence-skills-for-all)** — A UK Government collection of free awareness, working-level, practitioner, and product-specific courses assembled for civil servants.
  `Government` `Workforce` `Free`

- **[Building an AI-Ready Public Workforce](https://www.oecd.org/en/publications/building-an-ai-ready-public-workforce_b89244c7-en/full-report.html)** — OECD guidance for defining distinct capability needs for general employees, leaders, and digital or data professionals rather than treating AI literacy as one universal course.
  `Government` `Strategy` `Workforce` `Free`

- **[U.S. Department of Labor AI Literacy Framework](https://www.dol.gov/agencies/eta/advisories/ten-07-25)** — A competency framework for designing AI literacy programs across workforce systems, education providers, and public organizations.
  `Government` `Enterprise` `Workforce` `Free`

## Case studies and reference implementations

- **[UK Algorithmic Transparency Records](https://www.gov.uk/algorithmic-transparency-records)** — Searchable records showing how UK public organizations describe deployed algorithmic tools, intended uses, data, oversight, risks, and mitigations.
  `Government` `Governance` `Operations` `Free`

- **[GSA AI Resources and Use Cases](https://www.gsa.gov/artificial-intelligence/resources)** — A current U.S. agency example combining public use-case inventories, governance material, compliance planning, and workforce resources.
  `Government` `Governance` `Operations` `Free`

- **[Governing with Artificial Intelligence](https://www.oecd.org/en/publications/governing-with-artificial-intelligence_795de142-en/full-report/trends-and-early-lessons-from-the-use-of-ai-across-functions-of-government_c4968cb1.html)** — OECD analysis of 200 public-sector AI use cases across 11 government functions, including recurring enablers, risks, and evidence gaps.
  `Government` `Strategy` `Governance` `Free`

- **[OECD Observatory of Public Sector Innovation](https://oecd-opsi.org/)** — A searchable library of government innovation case studies and toolkits, including applied AI examples from multiple jurisdictions.
  `Government` `Strategy` `Free`

- **[AI Incident Database](https://incidentdatabase.ai/)** — A community-maintained collection of reported real-world AI harms and near harms. Use it to develop failure scenarios, not as a complete or independently verified measure of incident prevalence.
  `Government` `Enterprise` `Governance` `Security` `Free` `Open Source`

## Communities and continuing research

- **[NIST AI Resource Center](https://airc.nist.gov/)** — NIST's operational home for the AI RMF, profiles, playbook, technical reports, metrics, tools, crosswalks, and community contributions.
  `Government` `Enterprise` `Governance` `Evaluation` `Free`

- **[OECD.AI Policy Observatory](https://oecd.ai/en/)** — International policy initiatives, indicators, tools, research, and an incidents monitor for comparing how jurisdictions govern and adopt AI.
  `Government` `Enterprise` `Strategy` `Governance` `Free`

- **[GSA AI Community of Practice](https://www.gsa.gov/artificial-intelligence/ai-community-of-practice)** — A cross-agency U.S. community with meetings, training, showcases, and collaboration opportunities for eligible government employees, mission-supporting contractors, and academic participants.
  `Government` `Workforce` `Free`

- **[GovAI Coalition](https://www.sanjoseca.gov/your-government/departments-offices/information-technology/artificial-intelligence-inventory/govai-coalition)** — A state and local government practitioner network sharing policies, templates, procurement material, events, and lessons from implementation.
  `Government` `Governance` `Procurement` `Workforce` `Free`

- **[Stanford AI Index](https://hai.stanford.edu/ai-index)** — An annual, globally sourced report tracking AI capabilities, adoption, economics, policy, public opinion, workforce effects, and responsible-AI indicators.
  `Government` `Enterprise` `Strategy` `Workforce` `Free`

- **[OECD AI Incidents and Hazards Monitor](https://oecd.ai/en/incidents)** — A beta monitor of media-reported AI incidents and hazards with published definitions and methodology; useful for horizon scanning when its source limitations are kept in view.
  `Government` `Enterprise` `Governance` `Security` `Free`

## Contributing, curation, and disclosures

Suggestions and corrections are welcome through [GitHub issues](https://github.com/decisionterrain/ai-guides-and-tools/issues) or pull requests.

For a new resource, include:

- its title, canonical URL, publisher, and publication or update date;
- the audience, topic, and access tags that apply;
- one or two sentences explaining who it helps and what decision or deliverable it supports; and
- any employment, financial, vendor, affiliate, or other relationship you have with the resource.

### What belongs here

- Resources that materially help someone plan, approve, acquire, evaluate, deploy, operate, or govern AI.
- Actionable and maintained material from credible authors with clear provenance.
- Tools whose purpose, operator, access model, and important limitations can be described plainly.
- Commercial resources when they offer distinct practical value and are labeled accurately.

### What does not

- Bare links, generic AI news, SEO roundups, undifferentiated product directories, or uncheckable claims.
- Affiliate links, undisclosed paid placement, or payment for ranking.
- Resources whose main value is hype, lead capture, or an implied certification they cannot provide.
- Sensitive, classified, proprietary, or export-controlled information.

Maintainers may edit annotations and tags for consistency, decline additions, or remove resources that become stale, inaccessible, misleading, or superseded. Inclusion does not constitute certification or endorsement, and this guide is not legal, security, acquisition, or compliance advice.

## License

Except where otherwise noted, original written content in this repository is © 2026 Decision Terrain, Inc. and licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). See [LICENSE](LICENSE) for the complete terms.

Third-party content, linked resources, names, logos, and trademarks remain the property of their respective owners and are not covered by this license. The Decision Terrain name and branding are not licensed for reuse. Use of this guide does not imply endorsement by Decision Terrain or by the owners of any linked resource.
