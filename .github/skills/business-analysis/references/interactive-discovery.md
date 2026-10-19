# Interactive Discovery and Decision Grilling

Use this workflow when the user asks to be grilled, stress-test an idea, explore a decision interactively, or when an early-stage idea cannot be usefully drafted without resolving important choices. It complements the standard BA workflow; it does not replace it.

## Ground Rules

- Keep the interview purposeful and bounded. Do not grill by default, ask every conceivable question, or delay a useful partial draft for non-blocking details.
- Start with the business problem, desired outcome, current state, and success evidence. Treat proposed solutions as options until agreed by the accountable decision-maker.
- Distinguish facts to investigate from decisions the user or stakeholders must make. Review the supplied material and relevant project documentation for discoverable facts before asking the user. If evidence is unavailable, say so rather than imply it was checked.
- Do not invent stakeholder authority, policy, measurements, or constraints. Give recommendations only when evidence and decision criteria support them; label them as recommendations, not decisions.

## Interview Loop

1. **Frame the decision space.** At the start of discovery, briefly summarize the goal and what is known. Identify unresolved decisions, dependencies between decisions, constraints, and important evidence gaps. Keep facts, assumptions, hypotheses, recommendations, and decisions distinct. Do not repeat this framing in every later turn.
2. **Choose the next question.** Ask one high-value question per turn, and only when its prerequisites are known. If an answer would change a later question's options, defer that question. Track unresolved items in working notes, but do not show the user a question queue or preview future questions.
3. **Keep it conversational.** Ask directly in natural language; do not use a “Question:” label or a rigid response template. Briefly explain why an answer matters or offer distinct options only when that helps the user respond. Include recommendations only when supported by evidence, and make clear that the user or authorized stakeholder decides.
4. **Wait and update.** Do not guess answers or silently settle choices. After the user responds, acknowledge new information or a meaningful change when useful, without recapping known context. Then ask the single most useful next question.
5. **Probe with scenarios.** Where definitions, rules, or boundaries are fuzzy, offer concrete normal, alternate, and exception scenarios. Label invented scenarios as probes, not observed facts. Check how each answer affects users, process, data, controls, operations, and requirements.
6. **Stop at useful convergence.** Stop when the decisions needed for the requested deliverable are understood well enough to proceed, or when further progress requires unavailable evidence or accountable stakeholder input. List remaining non-blocking questions; do not pursue irrelevant branches for completeness.
7. **Produce the requested artifact.** Summarize agreed facts and decisions, recommendations, assumptions, risks, dependencies, and open questions. State readiness and next steps. Do not claim agreement that was not given. Do not create or modify project records unless asked or clearly authorized by the request.

## Question Round Format

Keep each turn concise, natural, and focused on one question. Do not add a routine current-state recap, a “Question:” heading, or a preview of later questions. Add a brief rationale or options only when they make the exchange clearer. Never present a recommendation as the presumed answer or make agreement the default.

## Project Documentation and Domain Language

- When project files or source material are available and relevant, inspect them before asking questions whose answers may already be documented. Cite or link the source in the response when useful, and surface contradictions rather than resolving them silently.
- Check for an existing project glossary or domain vocabulary. Challenge inconsistent or overloaded terms respectfully and ask which meaning applies. Keep the shared BA glossary generic; do not put a user's project-specific domain definitions there.
- Update a project glossary only when the user asks for documentation changes or has authorized that work. Record concise, agreed definitions and their source where known; do not turn a glossary into a requirements or design document.
- Record a decision in an appropriate project decision log or requirements artifact only when requested or clearly in scope. Use an ADR only for a material technical decision when the project uses ADRs and the choice is hard to reverse, would otherwise surprise future maintainers, and reflects a real trade-off. Do not create durable records for tentative interview answers.

## Fit with Readiness

Interactive discovery is most useful for **Idea** and early **Discovery** work. It can help clarify the need, outcome, actors, constraints, and decision owners. It does not automatically make work ready for development: readiness still depends on the team's context, validated requirements, acceptance evidence, dependencies, and resolution of critical questions.
