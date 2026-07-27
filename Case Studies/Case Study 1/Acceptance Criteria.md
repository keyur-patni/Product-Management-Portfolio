# Acceptance Criteria 🔍

Acceptance criteria define the conditions a user story must meet to be considered complete. They make requirements testable, reduce ambiguity, and help align product, design, and engineering teams.

Below are acceptance criteria for key user stories across the major epics of the Patient Flow Management System.

## Epic 1: Digital Check‑In & Intake

User Story:
As a patient, I want to check in digitally so that I don’t have to wait in line at the front desk.

**Acceptance Criteria**

- Patient can initiate check‑in via mobile, kiosk, or QR code.

- System verifies identity using name + DOB or phone number.

- Successful check‑in updates patient status to “Checked In.”

- Front desk dashboard displays the new check‑in within 5 seconds.

- Errors (e.g., unmatched identity) show clear, actionable messages.

User Story:
As a front desk staff, I want to receive alerts for incomplete forms so that I can follow up quickly.

**Acceptance Criteria**

- System flags incomplete or missing intake forms.

- Front desk dashboard displays a visible “Incomplete Forms” indicator.

- Staff receives a notification within 5 seconds of detection.

- Patient cannot proceed to triage until required fields are complete.

- Staff can resend form links to the patient.

## Epic 2: Real‑Time Patient Status Tracking

User Story:
As a patient, I want to see where I am in the visit process so that I know what to expect next.

**Acceptance Criteria**

- Patient view shows current stage (e.g., Check‑In, Triage, Provider).

- Each stage displays a timestamp.

- Next step is clearly labeled.

- Estimated wait time is visible and updates automatically.

- Delays trigger a notification to the patient.

User Story:
As a nurse, I want to see which patients are ready for triage so that I can prioritize efficiently.

**Acceptance Criteria**

- Nurse dashboard lists all patients with “Ready for Triage” status.

- Patients are sorted by check‑in time or urgency.

- Dashboard refreshes automatically every 5 seconds.

- Nurse can mark triage as “In Progress” or “Complete.”

- Status changes update across all staff dashboards instantly.

## Epic 3: Smart Triage & Rooming

User Story:
As a nurse, I want alerts when rooms become available so that I can room patients faster.

**Acceptance Criteria**

- System detects room availability based on provider status.

- Nurse receives an alert within 3 seconds of room becoming free.

- Alert includes room number and provider assignment.

- Nurse can assign a patient to the room directly from the alert.

- Room status updates to “Occupied” once patient is assigned.

## Epic 4: Provider Workflow Optimization

User Story:
As a provider, I want a dashboard of ready‑to‑see patients so that I can plan my workflow.

**Acceptance Criteria**

- Provider dashboard lists all patients with “Ready for Provider” status.

- Each patient card shows intake summary, vitals, and reason for visit.

- Provider can mark visit as “In Progress” or “Complete.”

- Dashboard updates in real time across all staff roles.

- Provider receives alerts for urgent or priority cases.

## Epic 5: Lab & Diagnostic Coordination

User Story:
As a lab technician, I want to see pending lab orders so that I can manage my workload.

**Acceptance Criteria**

- Lab dashboard displays all pending lab orders.

- Each order includes patient name, provider, and test type.

- Technician can mark orders as “In Progress” or “Complete.”

- Providers receive notifications when results are ready.

- Completed labs automatically update patient status.

## Epic 6: Billing & Checkout

User Story:
As a patient, I want to see a billing summary so that I understand my charges.

**Acceptance Criteria**

- Billing summary displays itemized charges.

- Insurance coverage and patient responsibility are clearly shown.

- Patient can pay digitally or choose in‑clinic payment.

- Checkout cannot complete until payment method is selected.

- Patient receives a digital receipt after checkout.

## Epic 7: Patient Communication & Notifications

User Story:
As a patient, I want wait‑time notifications so that I know how long I’ll be waiting.

**Acceptance Criteria**

- System calculates estimated wait time based on queue and provider availability.

- Patient receives notifications for changes greater than 5 minutes.

- Notifications include reason for delay (e.g., “Provider finishing previous visit”).

- Patient can view updated wait time in their dashboard.

- Staff can manually trigger a delay notification if needed.

## Epic 8: Operational Analytics & Reporting

User Story:
As a clinic manager, I want wait‑time analytics so that I can identify problem areas.

**Acceptance Criteria**

- Dashboard displays average wait times for each stage.

- Data can be filtered by date, provider, or visit type.

- Bottlenecks are highlighted visually.

- Reports can be exported for analysis.

- Metrics refresh every 15 minutes.

## Epic 9: Admin & Configuration

User Story:
As a clinic manager, I want to manage role‑based access so that staff only see relevant information.

**Acceptance Criteria**

- Admin panel allows assigning roles (Front Desk, Nurse, Provider, Manager).

- Each role has predefined permissions.

- Changes take effect immediately after saving.

- Unauthorized users cannot access restricted dashboards.

- Audit logs track permission changes.
