# BA Workflows

Select only the workflow needed for the request. Combine related workflows when useful, and tailor depth to risk, scale, and audience. For each workflow, confirm the purpose and inputs, perform the analysis, produce an appropriate output, check quality, and surface unresolved questions. The question prompts below are examples, not mandatory questionnaires.

## 1. Business Problem and Opportunity Analysis

**Purpose:** Establish whether a meaningful need or opportunity exists before selecting a solution.

**Inputs:** Request or idea, known business context, available evidence, affected groups, constraints, and desired outcome.

**Analysis:** Clarify current state, affected users, pain points or opportunity, causes versus symptoms, frequency and impact, strategic alignment if provided, and measurable outcomes. Separate facts from hypotheses. Challenge solution-first requests and consider whether process, policy, training, or no change could address the need.

**Output:** Problem statement, evidence summary, opportunity or impact, outcome measures, scope boundaries, risks, and open questions.

**Quality checks:** Problem is not written as a solution; outcome is observable; evidence and hypotheses are distinguishable; value and impact are not overstated.

**Typical questions:** Who is affected? How does the current process work? What evidence supports the problem? What happens if nothing changes? How will success be measured and over what period?

## 2. Stakeholder Identification and Analysis

**Purpose:** Identify people who influence, perform, receive, support, govern, or are affected by the change.

**Inputs:** Problem or change scope, process, organization information supplied by the user, and known decision roles.

**Analysis:** Identify stakeholder groups and likely representatives; map interests, impacts, influence, expertise, concerns, and engagement needs. Identify decision authority and missing or underrepresented perspectives. Use a stakeholder map, RACI, or similar method only when it clarifies participation or accountability.

**Output:** Stakeholder register or concise map, engagement approach, decision roles, and gaps requiring confirmation.

**Quality checks:** Distinguish confirmed individuals/groups from candidates; include frontline, support, operational, and control perspectives where relevant; do not invent reporting lines or authority.

**Typical questions:** Who performs the work today? Who owns the outcome or decision? Who supports or governs it? Which users may be adversely affected or excluded?

## 3. Requirements Elicitation, Analysis, Prioritization, and Validation

**Purpose:** Discover and validate needs and constraints, then organize requirements for decisions and delivery.

**Inputs:** Problem framing, stakeholders, source material, current process, constraints, and decision context.

**Analysis:** Select suitable elicitation methods (interviews, observation, workshops, document review, data analysis, prototypes). Classify and decompose needs; resolve ambiguity and conflicts; identify rules, assumptions, dependencies, and acceptance evidence. Prioritize with explicit criteria. Validate with accountable stakeholders and maintain change history when needed.

**Output:** Validated, prioritized requirements with rationale, source, owner or decision role when known, acceptance evidence, dependencies, and open items.

**Quality checks:** Each requirement is necessary, specific, feasible, unambiguous, and verifiable; conflicts and priorities are visible; user and business value are traceable.

**Typical questions:** Which source is authoritative? Who resolves conflicts? What is mandatory versus preferred? What evidence will confirm the need is met?

## 4. Business Requirements Documents and Functional/Non-functional Requirements

**Purpose:** Communicate the business need, scope, requirements, constraints, and decisions in a fit-for-purpose specification.

**Inputs:** Validated problem, stakeholders, requirements, current/future state, constraints, and intended readers.

**Analysis:** Choose an appropriate level of formality. Organize business objectives, scope, actors, functional behavior, business rules, data needs, non-functional needs, dependencies, assumptions, risks, and decisions. Identify requirements that need technical or specialist review.

**Output:** BRD, requirements specification, or lean equivalent; include unique IDs and traceability when useful.

**Quality checks:** No solution detail is disguised as a business requirement; functional behavior and quality constraints are distinguishable; each requirement is testable and within scope.

**Typical questions:** Who will approve or use the document? What level of detail is needed? Which architecture, service, policy, or regulatory constraints are confirmed?

## 5. Epics, Features, User Stories, and Acceptance Criteria

**Purpose:** Express needs as a backlog structure that supports conversation, planning, implementation, and verification.

**Inputs:** Outcome, personas or user roles supported by evidence, requirements, boundaries, dependencies, and team context.

**Analysis:** Group related outcomes into epics/features; write stories describing a user need and value; split work into small, independently valuable slices where practical. Add observable acceptance criteria for normal, alternate, and exception paths. Identify dependencies and unknowns without pretending work is ready.

**Output:** Prioritized epic/feature/story set with acceptance criteria, dependencies, open questions, and agreed readiness context.

**Quality checks:** Stories are not tasks in disguise; persona and value are credible; criteria are testable; the delivery team owns estimates; do not require INVEST or a Definition of Ready universally.

**Typical questions:** Who benefits? What outcome is valuable independently? Which behaviors and exceptions matter? What team-specific information is needed before implementation?

## 6. Business Rules, Use Cases, and Scenarios

**Purpose:** Make domain decisions and interactions explicit, including alternate and exception behavior.

**Inputs:** Domain knowledge, policies or source rules, actors, system boundaries, and relevant requirements.

**Analysis:** Separate rule statements from process steps and system behavior. Record rule source, owner, effective conditions, and conflicts. For use cases, define actor goal, trigger, preconditions, main flow, alternatives, exceptions, and postconditions. Validate scenarios with domain experts.

**Output:** Business rule catalog, use cases, decision tables, or scenario set appropriate to complexity.

**Quality checks:** Rules are atomic, sourced, and not inferred from examples alone; flows identify actor/system responsibilities; exceptions and boundary cases are explicit.

**Typical questions:** Who owns or interprets the rule? What happens at boundaries? Are there exceptions, overrides, or effective dates? Which source prevails if rules conflict?

## 7. Current-state and Future-state Process Analysis

**Purpose:** Understand how work is performed and describe a proposed process without hiding handoffs or exceptions.

**Inputs:** Process participants, documents, observation/interviews, systems, policies, measures, and known pain points.

**Analysis:** Establish process boundaries, trigger, outcome, actors, activities, decisions, handoffs, inputs, outputs, wait states, controls, and exceptions. Validate current state with people who do the work. Model future state only after the problem and design constraints are understood; compare changes and assumptions.

**Output:** Current/future process map or narrative, assumptions, pain points, control points, and change summary.

**Quality checks:** Map identifies actors, activities, decisions, handoffs, inputs, outputs, and exceptions; distinguish observed current state from proposed future state; notation fits audience and purpose.

**Typical questions:** Where does the process start/end? Which paths are frequent or high risk? What informal workarounds exist? Which steps are policy-mandated?

## 8. Gap and Impact Analysis

**Purpose:** Compare current and desired states and identify what must change and who or what is affected.

**Inputs:** Validated current state, target outcomes/state, systems/processes/data/policies, and stakeholder groups.

**Analysis:** Identify capability, process, data, technology, policy, control, skill, and experience gaps. Assess affected roles, integrations, operations, accessibility, privacy, security, compliance, migration, and transition impacts. Rate impacts only using agreed scales or clearly labeled qualitative judgment.

**Output:** Gap and impact register with proposed actions, ownership when known, dependencies, risks, and unanswered decisions.

**Quality checks:** Each gap links to evidence or a target; impact ratings are defined; downstream and unintended effects are considered.

**Typical questions:** Which target-state elements are approved? What assets or groups are affected? What can be reused? Which impacts require specialist assessment?

## 9. Options Analysis, Feasibility, and Business Cases

**Purpose:** Support an accountable choice among feasible ways to address a validated need.

**Inputs:** Problem and outcomes, decision authority, evaluation criteria, constraints, evidence, and candidate options.

**Analysis:** Include a do-nothing or status quo option when useful. Define comparable options and criteria; assess strategic fit, feasibility, costs, benefits, risks, dependencies, implementation and operating impacts, and uncertainty. Separate facts from estimates. Recommend only when evidence and decision authority are sufficient.

**Output:** Options comparison, feasibility findings, business case, recommendation or explicit decision gap.

**Quality checks:** Options are meaningfully distinct and compared consistently; assumptions, time horizon, costs/benefits, risks, and confidence are visible; no false precision.

**Typical questions:** Who decides? What criteria and time horizon matter? What evidence supports costs and benefits? Which constraints eliminate options?

## 10. Data, Reporting, KPI, and Dashboard Requirements

**Purpose:** Define data and information needs so reports support decisions and are interpretable and trustworthy.

**Inputs:** Decisions or user tasks to support, current reports/data sources, metric definitions, users, refresh needs, access constraints.

**Analysis:** Identify decisions, questions, dimensions, measures, definitions, grain, filters, time periods, source and lineage, quality rules, refresh latency, access and retention, accessibility, and reconciliation needs. Define KPI formulas, owners, targets, and thresholds only when supplied or agreed.

**Output:** Report/data requirements, metric dictionary, report inventory, acceptance scenarios, and data-quality questions.

**Quality checks:** Each metric has an unambiguous definition and source or is flagged unknown; freshness, access, privacy, and reconciliation are addressed; visual preference is not confused with decision need.

**Typical questions:** What decision does the report enable? How is each measure calculated? Which source is authoritative? What refresh delay is acceptable and to whom?

## 11. Vendor or Solution Evaluation

**Purpose:** Compare candidate products or providers against validated needs and constraints.

**Inputs:** Requirements, evaluation criteria and weights if approved, vendor evidence, architecture/security constraints, cost model, and decision process.

**Analysis:** Separate mandatory constraints from scored preferences. Gather comparable evidence; assess functional fit, integration, security/privacy, accessibility, data handling, support, resilience, exit/lock-in, implementation and operating cost, and roadmap claims. Mark vendor statements versus independently verified facts.

**Output:** Evaluation matrix, evidence log, risks, clarification questions, and recommendation only if authorized and sufficiently evidenced.

**Quality checks:** Criteria map to needs; scoring method is transparent; evidence is comparable and sourced; conflicts of interest and unknowns are visible.

**Typical questions:** Which requirements are pass/fail? What evidence can be tested? What are total lifecycle costs and exit terms? Which reviewers must approve?

## 12. UAT Planning, Test Scenarios, and Defect Triage

**Purpose:** Enable business representatives to verify that delivered behavior supports agreed business outcomes.

**Inputs:** Requirements, acceptance criteria, process scenarios, test environment/data, user roles, and release scope.

**Analysis:** Define UAT objectives, participants, prerequisites, representative normal/alternate/exception scenarios, expected results, traceability, entry/exit criteria, defect severity/priority approach, and sign-off authority. Distinguish a defect from a change request or unclear requirement; avoid claiming formal sign-off without authority.

**Output:** UAT plan and scenario set, traceability links, defect triage approach, and known test limitations.

**Quality checks:** Scenarios have preconditions, actions, and expected results; coverage maps to agreed requirements; data is safe and appropriate; expected results are not circular or vague.

**Typical questions:** Who represents the business and accepts the result? What data and environment are available? How are blocking defects distinguished from enhancements?

## 13. Change Impact and Operational Readiness

**Purpose:** Prepare affected people and operations for adoption and ongoing support.

**Inputs:** Proposed change, affected roles/processes/systems, release approach, support model, and known operational controls.

**Analysis:** Assess role, skill, workload, process, policy, communication, training, documentation, support, monitoring, access, continuity, and transition impacts. Identify readiness actions, owners, dependencies, and measures. Consider accessibility and impacts on groups with different needs.

**Output:** Change impact/readiness assessment, action plan, support and communication needs, risks, and unresolved ownership.

**Quality checks:** Impacts cover people, process, technology, information, policy, and controls as relevant; actions have owners only when confirmed; adoption is not assumed from deployment.

**Typical questions:** Who needs to change behavior? Who provides support after launch? What must be ready before cutover? How will adoption or service health be observed?

## 14. Requirements Traceability and Change Control

**Purpose:** Understand why a requirement exists, what it affects, and what must be revalidated when it changes.

**Inputs:** Requirements, objectives, source/evidence, design/build/test artifacts, decisions, and change requests.

**Analysis:** Link requirements to business outcomes, sources, stakeholders, rules, stories, tests, and release scope where useful. Record status, version, rationale, owner/approver when known, and change impact. Apply a lightweight change process proportional to risk and scale.

**Output:** Traceability matrix or linked backlog, decision/change log, impact assessment, and unresolved approval paths.

**Quality checks:** Links are current and bidirectional where useful; no orphan critical requirements or tests; changes identify affected scope and revalidation; records do not imply approval that did not occur.

**Typical questions:** Which artifacts are authoritative? Who approves changes? What must be re-tested? What traceability is required by risk, audit, or delivery context?
