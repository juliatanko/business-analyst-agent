# Risks, Options, Testing, and Handoff

Use this reference when evaluating solution approaches, identifying delivery risks, planning validation, or preparing a developer handoff.

## Edge Cases and Risk Analysis

Screen for the areas below and address those relevant to the process, product, and risk. Call out a material unknown or inapplicable area when it affects the decision; do not reproduce the whole checklist in every answer.

- Failure scenarios and recovery behavior
- Invalid, missing, or boundary inputs
- Permissions and access control
- Upgrade scenarios and migration impacts
- Data integrity and consistency
- Multi-region behavior
- Localization impacts
- Backward compatibility

Do not silently omit a relevant category. Surface risks and consequences without presenting speculative outcomes as confirmed facts.

## Dependencies

Identify technical and organizational dependencies, external systems, data sources, APIs, ownership, and sequencing. Include documentation, training, and operational impacts. Flag unknown owners or timing dependencies.

## Solution Alternatives

When solution analysis is requested, compare the viable approaches needed to support the decision. Include the status quo when useful. Do not invent options to reach a fixed count. Compare them against stated or clearly labeled criteria, including value, cost, feasibility, risk, dependencies, and change effort where relevant. Give estimates only when there is a defensible basis, and state the basis and uncertainty. Recommend an option only when the evidence and decision criteria support it; otherwise state what evidence or decision is missing.

## Testing Perspective

Derive a proportionate set of scenarios from confirmed requirements and material risks. Consider, where relevant:

- Positive behavior
- Negative behavior and failure handling
- Integration with relevant systems
- Performance, including missing thresholds or test data
- User acceptance against the intended outcomes

Flag any untestable requirement or missing test condition.

## Documentation Impact

Assess whether product documentation, localization, release notes, training materials, or migration guidance are needed. Mark each as yes, no, or unknown and give a short reason.

## Implementation Brief

When the user requests an implementation handoff, or a full analysis clearly needs one, include a concise **Implementation Brief** with the relevant items from this list:

- Problem Statement
- Business Objective
- Scope
- Out of Scope
- Risks
- Dependencies
- User Stories
- Open Questions

Do not append this brief to narrow answers or duplicate information already presented. Do not turn unresolved questions into requirements. Keep any handoff traceable to confirmed facts, agreed recommendations, and clearly labeled unknowns.
