# Acceptance Criteria (Template + Examples)

This file provides reusable acceptance criteria formats that can be applied across any product feature. It demonstrates clarity, testability, and alignment with the INVEST framework.

🧩 1. Gherkin Format (Given / When / Then)
Use this format when behavior depends on conditions or sequences.

## Example:

User Story: As a patient, I want to check in digitally so I can avoid waiting at the front desk.

## Acceptance Criteria:

- Given the patient is on the Check‑In screen

- When they enter valid personal information

- And tap “Check In”

- Then the system should mark them as “Checked In”

- And display the Status Timeline screen

🧩 2. Rule‑Based Acceptance Criteria
Use this when the feature has clear rules or constraints.

## Example:

User Story: As a nurse, I want to see patient priority levels so I can triage effectively.

## Acceptance Criteria:

- The dashboard must display priority as High, Medium, or Low

- Priority must be calculated based on symptoms entered

- High‑priority patients must appear at the top of the list

- The dashboard must refresh every 30 seconds

🧩 3. Functional Acceptance Criteria
Use this for straightforward UI or workflow requirements.

## Example:

User Story: As a provider, I want to view lab results so I can make informed decisions.

## Acceptance Criteria:

- The Lab Results screen must show test name, status, and result

- Completed tests must display a timestamp

- Pending tests must show “In Progress”

- The provider must be able to scroll through all results

🧩 4. Negative Scenario Acceptance Criteria
Use this to show error handling and validation.

## Example:

User Story: As a patient, I want to enter my information accurately.

## Acceptance Criteria:

- If required fields are empty, the “Check In” button must remain disabled

- If the phone number format is invalid, an error message must appear

- If the date of birth is in the future, the system must reject the input

- Errors must be displayed in red text below the field

🧩 5. Edge Case Acceptance Criteria
Use this to show robustness.

## Example:

User Story: As a provider, I want to see accurate wait times.

## Acceptance Criteria:

- If wait time exceeds 60 minutes, display “60+ mins”

- If the patient has just checked in, display “0 mins”

- If system time is unavailable, show “N/A”

- If patient status changes, wait time must update instantly

🧩 6. Acceptance Criteria Checklist (Reusable)
Use this checklist to ensure AC meets quality standards.

- AC is testable

- AC is clear and unambiguous

- AC covers happy path

- AC includes error handling

- AC includes edge cases

- AC aligns with the user story

- AC does not describe implementation details

🧩 7. INVEST Alignment
Acceptance criteria should support user stories that follow INVEST:

- Independent

- Negotiable

- Valuable

- Estimable

- Small

- Testable
