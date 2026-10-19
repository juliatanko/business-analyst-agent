# Discovery and Requirements

Use this reference when clarifying the business need, stakeholders, requirements, assumptions, or unknowns.

## Understand the Problem

Determine:

- What business problem are we solving?
- Who experiences it, and in what context?
- Why is it important, and what is the impact today?
- What measurable outcome would indicate success?

Challenge statements that prescribe a solution. Reframe them as the underlying need without presenting unverified details as facts.

## Stakeholders

Identify affected users and customers, plus relevant internal stakeholders such as product, engineering, support, documentation, localization, operations, and compliance or legal teams. Distinguish confirmed stakeholders from potential stakeholders and call out missing perspectives.

## Functional Requirements

Describe observable system behavior in terms that can be verified. Avoid prescribing implementation details unless they are a confirmed constraint or the user asks for technical design.

## Non-functional Requirements

Consider performance, security, reliability, accessibility, scalability, localization, observability, and maintainability. Mark categories as specified, unspecified, unresolved, or not applicable; do not silently omit them.

## Evidence Quality and Conflicting Information

- For evidence that materially affects a conclusion, record its source, date or period, collection method, and coverage when known. Distinguish direct observation or system data from estimates, recollection, opinion, and hypothesis.
- Check that metrics use a clear definition, population, time window, and baseline. Do not turn a reported estimate into a measured fact or project it into a benefit without a defensible basis.
- When sources conflict, preserve both accounts, identify what decision the conflict affects, and state what evidence or authority could resolve it. Do not silently average, select, or reconcile conflicting claims.
- Calibrate conclusions to evidence quality. State confidence and important limitations in plain language; avoid numerical confidence scores unless the method is defined and useful.

## Assumptions and Open Questions

Separate confirmed facts, assumptions, recommendations, and unknowns. Never turn an assumption into a requirement. List open questions and rank each as:

- **Critical**: affects user value, scope, architecture, safety or compliance, data integrity, or a major delivery decision.
- **Important**: affects design or planning but does not currently block the next decision.
- **Nice to know**: useful context that is not needed for near-term decisions.

Explain why critical questions matter, and ask the highest-impact follow-ups when key information is missing. Provide preliminary analysis only where grounded in supplied information, clearly marking its limits.

## Clarity Checkpoint Before Planning or Implementation

Before recommending a project plan, a next phase, or implementation, check whether unresolved items could change the objective, scope, option choice, sequence, cost, risk, acceptance, or decision authority. Summarize only the material items:

| Item | What is known | What is unclear or conflicting | Why it matters / consequence if unresolved | How or by whom it can be resolved | Needed by |
|---|---|---|---|---|---|
| [topic] | [evidence or source] | [question or conflict] | [decision or plan affected] | [validation, analysis, or owner if known] | [decision / phase] |

Then state the appropriate status in plain language:

- **Proceed:** remaining unknowns do not change the next decision or can be safely handled in the next phase.
- **Proceed with conditions:** a useful plan or draft is possible, but label assumptions, confidence, dependencies, and the decision point that must be met before affected work starts.
- **Wait on this decision:** a critical unknown makes the requested conclusion unreliable or could cause material rework, harm, or an unauthorized commitment. Explain the minimum evidence or decision needed to continue.

These are analysis statuses, not formal project approvals. A high-level plan can often proceed with a range, assumption, or discovery milestone even when an execution schedule cannot. Do not imply that all uncertainty must be eliminated before work begins.
