# Reusable BA Deliverable Templates

Adapt these structures to the audience, scale, and risk. Remove sections that add no value; mark unknowns instead of filling them with invented content. Use IDs and traceability when they help manage change or verification.

## 1. Problem and Opportunity Brief

- **Title / ID:** [short name / optional ID]
- **Request and source:** [who raised it, when, source material]
- **Problem or opportunity:** [need, not proposed solution]
- **Affected users/groups:** [confirmed / to validate]
- **Current state and evidence:** [process, data, examples, source]
- **Impact of current state:** [measured / reported / hypothesis]
- **Desired outcome:** [observable outcome]
- **Success measures:** [metric, baseline, target, period, owner; mark unknowns]
- **Constraints and dependencies:** [confirmed items]
- **Scope / out of scope:** [boundaries]
- **Assumptions, risks, open questions:** [label and owner/status if known]

## 2. Stakeholder Register

| ID | Stakeholder/group | Role or interest | Impact | Influence/decision role | Engagement or input needed | Status/source |
|---|---|---|---|---|---|---|
| STK-01 | [group] | [interest] | [high/medium/low or description] | [confirmed/unknown] | [when/how] | [confirmed/candidate + source] |

Use RACI only when responsibility boundaries need clarification. Confirm decision rights rather than infer them from job titles.

## 3. Requirements Specification / Catalog

- **Context and objective:** [link to problem/outcome]
- **Scope and boundaries:** [in/out]
- **Constraints and assumptions:** [labeled]

| ID | Type | Requirement | Rationale/source | Priority | Acceptance evidence | Dependencies/status |
|---|---|---|---|---|---|---|
| REQ-001 | [business/functional/data/NFR/rule] | [one necessary, specific, feasible, unambiguous, verifiable statement] | [why/source] | [criteria] | [observable result] | [items/status] |

- **Open decisions/questions:** [question, impact, owner if known, due point if known]
- **Change history:** [ID, change, rationale, impact, decision/status]

## 4. Epic, Feature, Story, and Acceptance Criteria

- **Epic:** [outcome group]
- **Feature:** [capability]
- **Story ID:** [US-###]
- **Story:** As a [supported persona], I want [capability], so that [business/user value].
- **Rationale/source:** [need or requirement]
- **Acceptance criteria:**
  - Given [precondition], when [action/event], then [observable expected result].
  - [Add alternate and exception paths as relevant.]
- **Dependencies and constraints:** [items]
- **Open questions:** [items]
- **Readiness notes:** [team-specific information still needed]

Given/When/Then is useful for behavior with meaningful context/action/outcome; use concise bullets or another form if clearer. Do not write implementation tasks as user stories unless that work has a user-facing or enabling outcome worth describing.

## 5. Business Rule and Use Case

**Business rule**

- **Rule ID / statement:** [one clear rule]
- **Source and authority:** [policy, owner, evidence; unknown if unverified]
- **Applies when:** [conditions]
- **Outcome / exception:** [result]
- **Effective date/version:** [if relevant]
- **Related requirements/tests:** [IDs]

**Use case / scenario**

- **ID / name:** [goal]
- **Primary actor and supporting systems:** [roles]
- **Trigger:** [event]
- **Preconditions:** [what must already be true]
- **Main flow:** [numbered actor/system interactions]
- **Alternate and exception flows:** [conditions and outcomes]
- **Postconditions:** [result and data state]
- **Related rules/requirements:** [IDs]

## 6. Process Analysis

- **Process name, owner, version/status:** [details / proposed vs observed]
- **Purpose, trigger, start/end:** [boundaries]
- **Actors/roles:** [people and systems]
- **Inputs and outputs:** [information, artifacts, decisions]
- **Current-state evidence:** [observation, interviews, source, date]
- **Flow:** [actor] receives [input] -> performs [activity] -> [decision and branches] -> hands off [output] to [actor].
- **Exceptions, rework, wait states, controls:** [paths and handling]
- **Measures and pain points:** [baseline/source or unknown]
- **Future-state changes and assumptions:** [proposed changes, clearly marked]
- **Impacts/dependencies/open questions:** [items]

A diagram may supplement this structure. BPMN is useful when participants need precise process semantics; use a simpler map or narrative when that better serves the audience. Ensure actors, activities, decisions, handoffs, inputs, outputs, and exceptions are represented.

## 7. Gap and Impact Register

| ID | Current state/evidence | Desired state | Gap | Impacted people/process/data/technology/policy/controls | Risk/severity basis | Action/dependency | Owner/status |
|---|---|---|---|---|---|---|---|
| GAP-01 | [observed/source] | [approved or target] | [difference] | [areas/groups] | [defined basis or qualitative note] | [action] | [known/unknown] |

## 8. Options Analysis / Business Case

- **Decision to make / decision authority:** [confirmed or unknown]
- **Problem and desired outcomes:** [evidence and measures]
- **Evaluation criteria:** [definition, relative importance/weights if agreed]
- **Assumptions, constraints, evidence quality:** [labeled]

| Option (include status quo where useful) | Fit to criteria | Costs/benefits | Feasibility/dependencies | Risks | Confidence/unknowns |
|---|---|---|---|---|---|
| A | [evidence] | [estimate, basis, time horizon] | [items] | [items] | [basis] |

- **Trade-offs:** [what is gained/lost]
- **Recommendation:** [only if evidence and authority support one; otherwise say why not]
- **Sensitivity / next evidence needed:** [what could change the conclusion]

## 9. Data, KPI, and Report Requirement

- **Decision/user task supported:** [question and audience]
- **Metric ID/name:** [optional]
- **Definition/formula and grain:** [precise meaning]
- **Dimensions/filters/time period:** [needed views]
- **Source, lineage, and owner:** [confirmed or unknown]
- **Quality/reconciliation rules:** [checks]
- **Refresh/freshness expectation:** [need and tolerance]
- **Access, privacy, retention, accessibility:** [relevant constraints]
- **Target/threshold:** [approved source or unknown]
- **Acceptance scenarios:** [expected results]

## 10. Vendor or Solution Evaluation

- **Need, scope, and must-have constraints:** [items]
- **Candidate set and evidence sources:** [vendors/options, source/date]
- **Criteria and method:** [pass/fail vs scored; weights only if agreed]

| Criterion | Why it matters / requirement link | Method/evidence | Candidate A | Candidate B | Unknowns |
|---|---|---|---|---|---|
| [criterion] | [rationale] | [demo/test/document] | [result/source] | [result/source] | [items] |

- **Lifecycle cost and assumptions:** [implementation, operation, exit; time horizon]
- **Security/privacy/accessibility/architecture review:** [status, not certification]
- **Risks, lock-in, support, exit considerations:** [items]
- **Recommendation or decision gap:** [evidence-based]

## 11. UAT Plan and Scenario

- **Objective, scope, release/build:** [details]
- **Business participants and acceptance authority:** [confirmed/unknown]
- **Environment and safe test data:** [details]
- **Entry/exit criteria:** [agreed conditions]

| Test ID | Requirement/story link | Scenario | Preconditions/data | Steps | Expected result | Result/defect |
|---|---|---|---|---|---|---|
| UAT-001 | [REQ/US] | [normal/alternate/exception] | [state] | [actions] | [observable outcome] | [status] |

- **Defect triage:** [severity/priority definitions, roles, escalation; confirm locally]
- **Known limitations and sign-off status:** [items; do not imply approval]

## 12. Change Impact and Operational Readiness

| Area/group | Change/impact | Readiness action | Owner | Due/dependency | Evidence/status |
|---|---|---|---|---|---|
| [people/process/data/technology/policy/controls/support] | [impact] | [action] | [known/unknown] | [item] | [evidence] |

Include communication, training, documentation, support model, access, monitoring, continuity, cutover, rollback, and adoption measures where relevant. Do not assume deployment alone creates adoption or readiness.

## 13. Traceability and Change Log

| Requirement ID | Business outcome/source | Related rule/story/design | Test/UAT ID | Release/status | Change impact |
|---|---|---|---|---|---|
| REQ-001 | [OBJ/source] | [IDs] | [IDs] | [status] | [affected artifacts] |

| Change ID/date | Requested change | Rationale/source | Impact assessed | Decision/authority/status | Follow-up |
|---|---|---|---|---|---|
| CHG-001 | [change] | [source] | [scope/tests/dependencies] | [not assumed] | [items] |
