# Learning Capture

Use this workflow only when the user asks to capture a lesson, or when the interaction reveals a reusable skill gap worth offering to capture. The goal is to improve future examples and guidance, not to retain conversation histories or build a profile of users.

## Capture Rules

- Do not collect every prompt or automatically save raw user messages, answers, project documents, or deliverables.
- Save only a short, generalized paraphrase of a reusable task pattern, ambiguity, helpful question, correction, or lesson. Never include names, contact details, company or project identifiers, account details, secrets, or sensitive personal, commercial, health, legal, or financial information.
- If a useful lesson cannot be separated from identifying or sensitive context, do not save it. Explain that limitation and, if helpful, offer a generic example instead.
- Do not claim that capture trains the model or changes the skill automatically. Capture creates a local candidate for later human review.
- Do not change `SKILL.md`, reference guidance, or published examples from a single capture. Curate repeated or high-value patterns separately, verify they generalize, and get user approval before editing the skill or sharing the result.

## Consent and Storage

- For a one-time capture suggested by the agent, show the proposed sanitized note and ask whether to save it. If the user explicitly asks to capture the current interaction, save only a safe, generalized note; if it cannot be sanitized without losing the lesson or retaining sensitive context, explain and do not write it.
- For ongoing workspace capture, enable it only after the user explicitly asks. Create `.github/skills/business-analysis/learning/capture-enabled`. While enabled, save only generalized, non-sensitive learning notes for genuinely reusable patterns; do not save routine interactions. The user can disable capture by deleting that file.
- Store approved notes in `.github/skills/business-analysis/learning/inbox.md`. This is local to the writable workspace, is not shared across users or sent to a service, and is excluded by the repository `.gitignore`; do not commit, push, or send notes elsewhere unless the user explicitly asks after reviewing their contents.
- If the workspace cannot be written, provide the sanitized note in the response and say it was not stored. Never imply that a note was saved when a file write did not succeed.
- Tell the user where a note was saved and how to inspect or delete it. Delete a requested note or the inbox when asked.

## Candidate Note Format

Append one entry per reusable pattern:

```markdown
### Learning candidate: [short generic title]
- **Pattern:** [generalized type of BA request; paraphrase, not a verbatim prompt]
- **Unclear or missing:** [decision-relevant information that was missing, conflicting, or misunderstood]
- **Helpful interaction:** [the clarification, checkpoint, or partial output that helped]
- **Reusable lesson:** [what future BA work should do differently or make explicit]
- **Potential skill location:** [workflow, reference, or example to review]
- **Review status:** Candidate; not yet incorporated
```

Do not add user identity, organization, project, date, or source transcript. Preserve only details needed to make the lesson useful across contexts.

## Curation for Skill Enrichment

When asked to review the inbox:

1. Read candidate notes and group repeated patterns; treat one-off preferences as local unless the user asks to generalize them.
2. Remove duplicates, unsupported conclusions, and content that could identify a person or organization.
3. Propose the smallest reusable improvement: revise an instruction, add a workflow example, or clarify an existing template.
4. Present the proposed change and its source pattern for user review. Keep candidate notes separate from normative skill guidance until approved.
5. After approval, update the relevant skill files, mark the applied note or clear the reviewed entry as the user directs, and recheck links and formatting.