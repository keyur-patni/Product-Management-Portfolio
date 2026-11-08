# Refinement Examples (Template + Realistic Scenarios)

This document provides examples of backlog refinement, demonstrating how raw, unclear stories evolve into clear, testable, INVEST aligned user stories with acceptance criteria.

🧩 1. Example: Refining a Raw Story Into a Clear Story

## Raw Story (Unrefined)

“Add a way for patients to check in.”

### Issues:

- No user type

- No value statement

- No acceptance criteria

- Too vague

- No constraints or rules

## Refined Story

As a patient, I want to check in digitally so that I can avoid waiting at the front desk.

### Acceptance Criteria:

- Given the patient is on the Check‑In screen

- When they enter valid personal information

- And tap “Check In”

- Then the system marks them as “Checked In”

- And displays the Status Timeline screen

🧩 2. Example: Refining a Technical Story

## Raw Story (Unrefined)

“System should calculate wait time.”

### Issues:

- No user value

- No context

- No rules

- No edge cases

## Refined Story

As a provider, I want the system to calculate patient wait time so that I can prioritize visits effectively.

### Acceptance Criteria:

- Wait time = current timestamp - check‑in timestamp

- If wait time exceeds 60 minutes, display “60+ mins”

- If timestamp is missing, display “N/A”

- Wait time must update every 30 seconds

🧩 3. Example: Refining a UI‑Focused Story

## Raw Story (Unrefined)

“Add a calendar to the scheduling page.”

### Issues:

- UI‑focused

- No user value

- No workflow

- No rules

## Refined Story

As a patient, I want to select a date and time for my follow‑up appointment so that I can complete my care plan.

### Acceptance Criteria:

- Calendar must display days Mon-Sun

- Selected date must be visually highlighted

- Available time slots must appear below the calendar

- “Confirm Appointment” button must remain disabled until a time is selected

🧩 4. Example: Refining a Large Story Into Smaller Stories

## Raw Epic‑Sized Story

“Build a provider dashboard with everything the doctor needs.”

### Issues:

- Too large

- Not actionable

- Not testable

- No breakdown

## Refined Stories:

- As a provider, I want to view patient vitals so that I can assess their condition.

- As a provider, I want to view lab results so that I can make informed decisions.

- As a provider, I want to update visit notes so that I can document care.

- As a provider, I want to see patient history so that I can understand past visits.

### Each story is now:

- Independent

- Valuable

- Testable

- Small enough for a sprint

🧩 5. Example: Refining a Story With Missing Edge Cases

## Raw Story (Unrefined)

“Let nurses update patient status.”

### Issues:

- No validation

- No rules

- No error handling

## Refined Story

As a triage nurse, I want to update patient status so that the care team stays informed.

### Acceptance Criteria:

- Status options: Checked In, In Triage, With Provider, Labs Pending, Complete

- Status changes must log a timestamp

- If the system cannot update status, show an error message

- Status must update instantly on all dashboards

🧩 6. Refinement Checklist (Reusable)

Use this checklist during backlog refinement sessions:

- Story follows As a / I want / So that

- Story is small enough for a sprint

- Story has clear acceptance criteria

- Story avoids UI details

- Story avoids technical implementation details

- Story includes error handling

- Story includes edge cases

- Story aligns with product goals

- Story is testable
