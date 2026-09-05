# Sprint Plan 🚀

The delivery plan is organized into four 2‑week sprints. Each sprint builds on the previous one, delivering incremental value while reducing operational risk. The structure mirrors real Agile delivery: clear goals, scoped stories, dependencies, risks, and measurable outcomes.

## Sprint 1 — MVP Foundation (Weeks 1–2)

\*\*Goal: Establish the core patient flow visibility: check‑in → status → triage readiness.

### Scope

- Digital check‑in

- Identity verification

- Patient status timeline (basic)

- Triage readiness indicator

- Front desk dashboard (basic)

### User Stories Delivered

- Patient digital check‑in

- Front desk sees new check‑ins

- Patient sees “Checked In” + next step

- Nurse sees “Ready for Triage”

### Dependencies

- Intake data model

- Basic role permissions

- Patient status API

### Risks & Mitigations

- Risk: Patients struggle with digital check‑in
  Mitigation: Add fallback manual check‑in

- Risk: Status updates lag
  Mitigation: Use lightweight polling (5s refresh)

### Outcome

- Clinic can track patients from check‑in to triage

- Staff coordination improves immediately

- Foundation for all future workflows is established

## Sprint 2 — Workflow Expansion (Weeks 3–4)

\*\*Goal: Improve staff coordination and reduce bottlenecks between triage and provider.

### Scope

- Digital intake forms

- Room availability alerts

- Provider ready‑to‑see dashboard

- Visit status updates

- Wait‑time notifications

### User Stories Delivered

- Patients complete intake forms

- Nurses receive rooming alerts

- Providers see ready‑to‑see patients

- Patients receive wait‑time updates

### Dependencies

- Triage workflow from Sprint 1

- Notification service

- Provider schedule data

### Risks & Mitigations

- Risk: Intake forms become too long
  Mitigation: Use progressive disclosure

- Risk: Provider dashboard becomes cluttered
  Mitigation: Prioritize essential fields only

### Outcome

- Staff handoffs become smoother

- Providers move between visits faster

- Patients feel more informed during delays

## Sprint 3 — Clinical Coordination & Labs (Weeks 5–6)

\*\*Goal: Connect providers and lab technicians to reduce turnaround time.

### Scope

- Lab order creation

- Lab status tracking

- Result notifications

- Follow‑up workflow integration

### User Stories Delivered

- Providers create lab orders

- Lab technicians update status

- Providers receive result alerts

- Patients move smoothly into follow‑up

### Dependencies

- Provider workflow from Sprint 2

- Lab data model

- Notification service (enhanced)

### Risks & Mitigations

- Risk: Lab workflows vary by clinic
  Mitigation: Build flexible status states

- Risk: Result notifications overwhelm providers
  Mitigation: Batch notifications for non‑urgent results

### Outcome

- Lab coordination becomes predictable

- Providers reduce idle time waiting for results

- Patients experience fewer delays

## Sprint 4 — Analytics & Admin (Weeks 7–8)

\*\*Goal: Add intelligence, configurability, and operational insights.

### Scope

- Operational analytics dashboard

- Predictive wait‑time modeling

- Peak‑hour analysis

- Role‑based access control

- Custom triage rules

### User Stories Delivered

- Managers view wait‑time analytics

- Predictive wait‑time estimates improve accuracy

- Staff access is restricted by role

- Clinics customize triage rules

### Dependencies

- All previous sprints

- Historical data storage

- Admin configuration panel

### Risks & Mitigations

- Risk: Predictive model accuracy varies
  Mitigation: Start with simple heuristics

- Risk: Admin panel becomes too complex
  Mitigation: Release minimal version first

## Outcome

- Clinics gain actionable insights

- System becomes configurable and scalable

- Full patient flow lifecycle is supported end‑to‑end
