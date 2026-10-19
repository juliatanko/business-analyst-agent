# Business Analysis Agent

An interactive, evidence-grounded business analysis skill for clarifying business needs, exploring decisions, and producing useful BA deliverables. It helps users make informed decisions without treating assumptions, proposed solutions, or recommendations as agreed facts.

The Copilot skill is defined in [.github/skills/business-analysis/SKILL.md](.github/skills/business-analysis/SKILL.md). Supporting workflows, examples, templates, and guidance are in its `references` folder.

## What It Supports

- Business problem and opportunity framing, including outcomes, evidence, impact, scope, and success measures.
- Stakeholder identification, elicitation, requirements analysis, prioritization, and validation.
- Business and functional requirements, epics, features, user stories, acceptance criteria, business rules, and scenarios.
- Current- and future-state process analysis, gap analysis, and change impact.
- Options analysis, feasibility, business cases, costs, benefits, risks, dependencies, and trade-offs.
- Data, reporting, KPI, dashboard, and vendor evaluation requirements.
- UAT planning, scenario design, defect triage, operational readiness, and requirements traceability.

The skill selects only the workflow needed for the request and adapts the depth to the decision, risk, and audience. It can produce a useful partial draft while making unresolved items visible, rather than forcing a complete questionnaire first.

## How It Works

- Starts with the business problem, desired outcome, current state, and available evidence before proposing a future state.
- Uses information already provided and relevant project material; it does not ask users to repeat known context.
- In interactive discovery, asks one high-value question per turn in natural language. It does not use a rigid `Question:` label, preview a queue of future questions, or repeat the known current state in every turn.
- Distinguishes evidence, user-provided information, assumptions, hypotheses, constraints, risks, dependencies, decisions, recommendations, and open questions.
- Challenges ambiguity, conflicting needs, solution-led requests, and requirements without a clear business rationale.
- Uses recommendations only when evidence and decision criteria support them, and identifies who must make the decision.
- Considers relevant impacts across people, process, data, technology, policy, controls, and change.

## Deliverable Standards

- Requirements are necessary, feasible, unambiguous, and verifiable. Rationale, source, priority, and dependencies are included when useful.
- Stories communicate a credible user need and value. Acceptance criteria cover relevant normal, alternate, and exception paths and can be tested.
- Process descriptions identify actors, activities, decisions, handoffs, inputs, outputs, and exceptions without implying a model is exhaustive.
- Options and business cases show assumptions, evaluation criteria, estimated costs and benefits, risks, dependencies, uncertainty, and trade-offs. Estimates are not presented with false precision.
- UAT scenarios connect to requirements and specify preconditions, actions, and expected results.
- Methods such as MoSCoW, INVEST, Given/When/Then, BPMN, RACI, and traceability matrices are used when they solve a real problem, not as mandatory checklists.

## Boundaries

The skill supports analysis and drafting. It does not approve business decisions, certify legal or regulatory compliance, or replace accountable business owners and subject matter experts. It flags when review is needed from users, technical specialists, security, privacy, legal, compliance, or operations. It does not invent organizational facts, stakeholder authority, policies, measurements, or requirements.

Before delivery, it checks alignment to the business problem and outcome, separation of facts from assumptions and decisions, ambiguity and missing scenarios, testability and traceability where useful, relevant operational and control impacts, unsupported claims, and ownership of open decisions when known.

## Reference Library

- [BA workflows](.github/skills/business-analysis/references/workflows.md): workflow purposes, analysis steps, outputs, quality checks, and typical prompts.
- [Interactive discovery](.github/skills/business-analysis/references/interactive-discovery.md): dependency-aware, one-question-at-a-time interviews and decision exploration.
- [Discovery and requirements](.github/skills/business-analysis/references/discovery-and-requirements.md): problem framing, stakeholder discovery, requirements, and uncertainty.
- [Agile delivery and readiness](.github/skills/business-analysis/references/agile-delivery-and-readiness.md): iterative delivery, backlog refinement, and readiness.
- [Risks, options, testing, and handoff](.github/skills/business-analysis/references/risk-options-testing-handoff.md): alternatives, delivery risks, validation, documentation, and implementation handoffs.
- [Deliverable templates](.github/skills/business-analysis/references/deliverable-templates.md): adaptable BA document structures.
- [Examples](.github/skills/business-analysis/references/examples.md): illustrative requirements, stories, acceptance criteria, and process analysis.
- [Glossary](.github/skills/business-analysis/references/glossary.md): consistent, plain-language BA terminology.

## Use in Another Repository

Copy `.github/skills/business-analysis/` into the target repository's `.github/skills/` directory. Copilot can then discover the skill using its metadata in `SKILL.md`.
