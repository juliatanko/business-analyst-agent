# Stakeholder Interviews and Requirements Elicitation

Use this reference when planning or conducting stakeholder interviews to understand business needs, current work, requirements, rules, constraints, and acceptance evidence. Interviews are one elicitation method; combine them with observation, document review, data analysis, or workshops when those methods provide stronger evidence.

## Prepare

1. **Set the interview objective.** Identify the decision or knowledge gap the conversation should address. Keep the scope achievable for the time available.
2. **Select participants.** Include people who perform, receive, support, govern, or decide the work. Seek perspectives from affected users and operational roles, not only sponsors or managers. Distinguish confirmed roles from people who may need to be consulted.
3. **Review available evidence.** Check relevant process documents, policies, reports, existing requirements, and prior decisions before asking participants to repeat known information. Note conflicts and gaps to validate.
4. **Prepare a short topic guide.** Choose a few high-value prompts for the interview objective, plus follow-up probes. Treat the question bank below as options, not a script or checklist.
5. **Plan the record.** Decide how notes will be captured and shared. Explain the purpose and intended use of the discussion; ask permission before recording or attributing direct quotes. Avoid collecting sensitive or identifying details that are not needed.

## Conduct the Interview

- Open with the purpose, scope, time available, and how the information will be used. Clarify that the conversation is for understanding needs, not an approval unless approval is explicitly part of the meeting.
- Start broadly, then ask for concrete examples. Ask one clear question at a time; listen to the answer and choose the next prompt based on what remains unclear.
- Use neutral wording. Avoid embedding a solution, a preferred answer, or an assumption in the question.
- Ask about recent real situations, including normal, alternate, and exception cases. Explore triggers, actors, handoffs, information used, decisions, delays, rework, and outcomes.
- Separate the underlying need from a requested feature or proposed solution. Ask what problem it solves and what outcome would demonstrate value.
- Distinguish firsthand observation, reported information, estimates, opinions, assumptions, and policy. Ask for the source or an example when a claim materially affects requirements or decisions.
- Invite disagreement and missing perspectives. A stakeholder's account is important evidence, but is not automatically representative of every user or an approved business rule.
- Close by summarizing the key points and unresolved items in plain language. Ask whether the summary is accurate, identify follow-up evidence or people, and confirm next steps.

## Question Bank

Select only prompts that serve the interview objective. Do not ask every question or present the whole bank to the stakeholder at once.

### Business Need and Outcomes

- What are you trying to accomplish?
- What problem or opportunity prompted this work?
- What happens today when the problem occurs?
- Who is affected, and what is the impact on them or the business?
- What would improve if this were addressed? How would you recognize success?
- What happens if nothing changes?

### Current Work and Process

- Could you walk me through the last time you did this, from the trigger to the outcome?
- Who is involved at each step, and what information or tools do they use?
- Where do work wait, get repeated, fail, or leave the expected process?
- What exceptions, workarounds, or handoffs should I understand?
- How often does this happen, and what evidence supports that estimate?

### Requirements and Behavior

- What do you need to be able to do?
- What should happen when [specific trigger or condition] occurs?
- What information is needed to make that decision or complete that task?
- What rules, thresholds, or approvals apply? Who owns or can confirm them?
- What should happen when information is missing, invalid, late, or conflicting?
- What must the process or system not do?

### Priorities, Constraints, and Dependencies

- Which need matters most, and what is the consequence if it is not met?
- Which parts are essential for the first release, and which could follow later?
- What policy, contractual, technical, timing, or operational constraints apply?
- Which other teams, systems, decisions, or data does this depend on?
- Who can resolve an open decision or approve a business rule?

### Acceptance and Evidence

- What would you expect to see in a realistic example if this worked correctly?
- What result would be unacceptable, even if the main flow worked?
- How could a user or tester verify the requirement was met?
- Is there a baseline, report, sample, or policy we can use to validate this?
- Who should review the synthesized requirements, and what would they need to confirm?

## Useful Follow-up Probes

Use a short probe when an answer is broad, ambiguous, or solution-led:

- "Can you give me a recent example?"
- "What happened next?"
- "How do you know that?"
- "Does that happen every time, or only under certain conditions?"
- "Who else is affected by that step?"
- "What would happen if that information were missing?"
- "Is that an approved rule, or a current practice or proposal?"
- "What outcome are you expecting that solution to provide?"

Avoid leading, compound, blame-oriented, or hypothetical-only questions when a concrete example is available. If a question contains multiple decisions, split it across turns.

## Synthesize and Validate

After the interview, organize notes into:

- **Needs and outcomes:** the problem, affected people, impact, and desired measurable result.
- **Current-state evidence:** observed or reported steps, sources, examples, frequency, and limitations.
- **Requirements candidates:** observable behavior, business rules, data needs, quality needs, and acceptance evidence.
- **Constraints and dependencies:** confirmed limits, external inputs, owners, and sequencing.
- **Uncertainty:** assumptions, conflicting accounts, unverified estimates, open decisions, and missing perspectives.

For each requirement candidate, retain its source or stakeholder, rationale, status (for example, proposed, confirmed, or unresolved), and the evidence needed for validation. Do not convert a single stakeholder's preference into a universal requirement or silently resolve conflicting accounts. Validate the synthesis with relevant stakeholders and the accountable decision-maker where approval is required.

## Lightweight Interview Notes

| Topic | Notes |
|---|---|
| Interview objective | [decision or knowledge gap] |
| Participant role | [role; avoid unnecessary personal details] |
| Needs and outcomes | [problem, impact, desired result] |
| Current process/examples | [steps, triggers, handoffs, exceptions] |
| Requirements candidates | [behavior, rules, information, acceptance evidence] |
| Evidence and sources | [documents, data, examples, confidence/limitations] |
| Open items | [uncertainty, conflict, follow-up evidence or owner if known] |
| Validation and next steps | [who reviews what, and when if known] |

Keep notes proportionate to the work. Share or retain them only according to the project's agreed information-handling practices.