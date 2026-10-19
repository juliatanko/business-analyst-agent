# BA Examples

These examples are fictional and illustrative only. They do not describe any real organization, policy, baseline, or universal requirement. Values and process details are made up to demonstrate clear analysis; replace them with validated local evidence before using in real decisions.

## Example Context: Appointment Reminder

A fictional service desk reports that some customers miss scheduled appointments. A request proposes adding automated reminders. No measured baseline, customer research, consent policy, delivery channel, or approved target has been supplied. The example below labels those gaps rather than treating them as known.

### Problem Framing

- **Reported problem:** Service desk staff report missed appointments. This is stakeholder-provided information, not yet supported by a measured rate.
- **Current state:** Unknown. The booking, reminder, and cancellation process needs confirmation.
- **Potential impact:** Customer inconvenience and staff time may be affected; the scale is unmeasured.
- **Desired outcome:** Reduce avoidable missed appointments without increasing customer confusion or exposing personal information.
- **Success measure:** Baseline, target, measurement period, and accountable owner are unknown. Confirm these before making a quantified benefit claim.
- **Solution proposal:** Automated reminders are one possible approach, not yet a requirement or approved decision.

### Example Requirements

- **REQ-001 (functional, illustrative):** For an appointment that meets the service's confirmed reminder eligibility rules, the service shall make the approved reminder information available to the customer through the channel selected under the confirmed communication preferences.
- **REQ-002 (data, illustrative):** A reminder record shall be associated with the appointment identifier and retain the minimum event details required for agreed operational support and measurement.
- **REQ-003 (non-functional, unresolved):** The acceptable delivery window, service availability, retention period, and privacy controls must be defined by accountable business and technical owners before implementation.

These requirements intentionally surface decisions instead of guessing a lead time, channel, schedule, retention period, or policy.

### Example User Story and Criteria

**Story (illustrative):** As a customer with an eligible appointment, I want to receive the agreed appointment details through my confirmed communication channel, so that I can prepare for or manage the appointment.

**Acceptance criteria:**

- Given an appointment is eligible under the confirmed rules and has a valid customer communication preference, when the agreed reminder event occurs, then the system records an attempt and uses the selected channel.
- Given an appointment is canceled before the agreed reminder event, when the reminder process evaluates it, then no reminder is sent and the cancellation outcome is recorded.
- Given the selected channel is unavailable, when delivery is attempted, then the system follows the agreed retry or failure-handling rule and makes the outcome available to authorized support staff.
- Given an appointment lacks a valid communication preference, when eligibility is evaluated, then the system follows an approved fallback or exception rule rather than selecting a channel by assumption.

The lead time, retry policy, fallback behavior, support access, and record retention remain open decisions. The criteria cannot be finalized until owners confirm those rules.

### Example Process Analysis

**Illustrative current-state narrative (not yet validated):**

1. Customer and service desk agree an appointment time.
2. Booking details are recorded in an unspecified system.
3. The process for confirming details, sending reminders, handling changes, and recording missed appointments is unknown.

**Actors:** Customer, service desk staff, booking system (system name and ownership unknown).

**Known process gaps:** Trigger, inputs, handoffs, cancellation path, exception handling, current reminder behavior, and outcome recording need discovery. Do not draw a definitive current-state process map from this incomplete account.

**Potential future-state path (proposal, not decision):**

1. Booking system evaluates eligibility against approved rules.
2. System checks current appointment status and communication preference.
3. System sends through the approved channel or routes the case to the agreed exception path.
4. System records an outcome for authorized operational review.

**Decisions/open questions:** Who defines eligibility and reminder timing? Which communication channels and consent rules apply? How are changes, cancellations, invalid contact details, outages, and duplicate events handled? Which data may be retained, by whom, and for how long? What baseline and target would demonstrate business value?

## Example Quality Notes

- The proposal is not mistaken for a confirmed solution.
- Fictional details are explicitly labeled; missing policy, data, and ownership are not invented.
- Requirements describe observable behavior while highlighting decisions needed for testability.
- The process distinguishes a sparse reported current state from a proposed future state.
- The examples are not a compliance, privacy, or security assessment; accountable specialists must review applicable controls.

## Interactive Example 1: A CRM Migration Plan with an Unclear Target

This fictional exchange demonstrates how to keep discovery moving while preventing a provisional idea from becoming a false implementation commitment.

**User:** "We need a CRM migration plan for next quarter. Can you draft the project plan?"

**Agent:** "What problem with the current CRM should the migration solve?"

**User:** "Support agents spend too long fixing duplicate customer records. We estimate about 12 hours a week, but that number is from the support lead, not a report."

**Agent:** "What outcome would make a change worthwhile: fewer duplicate records, less cleanup time, or both?"

**User:** "Both. Sales wants to keep the existing CRM; support wants to move to a new platform. Leadership asked us to look at both."

**Agent:** "The platform choice changes data mapping, integrations, licensing, training, and cutover. Who will make that decision?"

**User:** "The COO decides after a short evaluation. We can interview support and sales and check the data quality next month."

**Agent checkpoint:**

- **Known:** reducing duplicate records and cleanup time is the desired outcome; duplicate records are a reported problem; support estimates 12 hours per week of cleanup; the COO will select the platform after evaluation.
- **Still unclear:** actual duplicate rate and cleanup effort; target CRM; migration scope; integration and data-quality constraints.
- **Why it matters:** these could change the platform recommendation, migration effort, cost, sequence, and expected benefit.
- **Status:** **Proceed with conditions** on a discovery/evaluation plan. Do not baseline migration dates or costs yet.
- **Next step:** validate the support estimate and data quality, confirm evaluation criteria with the COO, then compare the existing platform with alternatives before planning migration.

The agent can now draft a discovery plan with next-month activities and a decision milestone. It should not describe the selected platform or migration implementation as approved.

**Safe next-step plan (illustrative):**

| Phase | Work / output | Dependency or condition |
|---|---|---|
| Validate current state | Confirm duplicate rate, cleanup effort, affected workflows, and source systems | Treat the 12-hour estimate as reported until checked |
| Evaluate options | Agree criteria with the COO; compare retaining the current CRM with candidate platforms | Platform decision remains open; identify integration and data-quality evidence |
| Decide direction | Present evidence, trade-offs, costs, and unresolved risks to the COO | Decision authority is known; decision date and criteria still need confirmation |
| Plan selected approach | Define migration scope, sequence, estimates, controls, testing, and rollout | Start after the platform choice and key data/integration findings |

This plan uses the supplied "next month" horizon but does not invent dates, effort, or owners. It plans the decision and defers the execution baseline until the target is selected.

## Interactive Example 2: Refund Automation with a Policy Conflict

This fictional exchange demonstrates how to isolate the one unresolved rule that blocks implementation while continuing unaffected analysis.

**User:** "Write stories to automate refunds. Refunds under $50 should be automatic."

**Agent:** "I can draft the flow. Before I make the $50 threshold an acceptance rule, is that an approved policy, or a proposed starting point?"

**User:** "It's in an old operations guide, but finance says the limit may have changed."

**Agent:** "The threshold is unverified and affects who can authorize a refund. Which owner can confirm the current limit and any exceptions?"

**User:** "Finance owns the policy. They can confirm it next week. The flow today is that support submits a refund request, a supervisor approves it, and finance processes it."

**Agent:** "I can document the current flow and draft stories around request intake, status visibility, and audit history. I'll leave automatic approval behavior as a placeholder until Finance confirms the rule. The threshold and exception rules block implementation of the approval decision, but they don't block analysis of the existing handoffs. Should I include the proposed automation as an option in the draft, clearly marked as pending policy confirmation?"

**User:** "Yes. Also, finance needs an audit trail."

**Agent checkpoint:**

- **Known:** support submits requests, supervisors approve, and finance processes refunds; Finance owns the policy; an audit trail is needed.
- **Still unclear:** current threshold, exception cases, and whether automation may approve or only route requests.
- **Why it matters:** the rule determines authorization, user stories, controls, and acceptance tests.
- **Status:** **Proceed with conditions** on current-state documentation and non-policy-dependent stories. **Wait on this decision** before specifying or implementing automated approval.
- **Next step:** obtain Finance's approved threshold and exceptions, then update the decision rule, stories, and tests.

This checkpoint avoids stopping all work while making the implementation boundary explicit. The agent must not invent a new threshold or imply Finance has approved automation.

**Safe partial story (illustrative):** As a support agent, I want to submit a refund request and see its status, so that I can tell the customer what is happening. Keep approval thresholds, exception behavior, and automated authorization as unresolved policy-dependent criteria; they are not ready to implement.
