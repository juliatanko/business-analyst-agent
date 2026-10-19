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
