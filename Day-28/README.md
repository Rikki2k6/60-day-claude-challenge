# Day 28 — Hospital Admission Readiness Simulator

## Overview

For Day 28 of the **60 Days Claude Challenge**, I built a **Hospital Admission Readiness Simulator** using Claude.

The application simulates the operational work required before a patient is ready for inpatient admission. Instead of treating admission as a single decision, the simulator evaluates multiple dependencies such as Prior Authorization, insurance verification, documentation, physician orders, consent, and bed availability.

The goal was to understand how different operational risks affect hospital admission readiness and how completing workflow actions can improve the final decision.

---

## Final Application

![Hospital Admission Readiness Simulator](Screenshot%20(254).png)

The simulator includes:

- Provider and physician configuration
- Multiple diagnosis scenarios
- Inpatient and observation admission types
- Prior Authorization status tracking
- Dynamic admission readiness scoring
- Workflow actions
- Documentation and insurance risk tracking
- Bed assignment
- Physician order management
- Patient consent tracking
- Care coordination responsibilities
- Admission timeline
- Final admission decision
- Governance Snapshot when applicable

---

## How the Simulator Works

The simulation begins by configuring a patient admission scenario.

The user can enter:

- Provider details
- Attending physician
- Diagnosis
- Admission type
- Prior Authorization status
- Admission date

After the scenario is created, the simulator generates an initial **Admission Readiness Score**.

The score depends on several operational factors:

- Prior Authorization
- Insurance verification
- Clinical documentation
- Physician orders
- Patient consent
- Bed availability

---

## Initial Admission Status

In my simulation, the patient scenario was:

**Diagnosis:** Acute MI  
**Admission Type:** Inpatient

The initial readiness score was:

### 58% Ready

The status summary showed:

- **Prior Authorization:** Approved
- **Insurance:** Pending
- **Bed:** Unassigned
- **Documentation:** Partial
- **Physician Orders:** Partial
- **Consent:** Pending

This demonstrated that Prior Authorization approval alone does not make a patient ready for admission.

Several operational dependencies still need to be resolved.

---

## Workflow Actions

The simulator provides several actions to improve admission readiness:

- Assign Bed
- Verify Insurance
- Upload Documentation
- Complete Consent
- Contact Physician
- Notify Nursing
- Prepare Patient Arrival

Each action updates the relevant workflow status and contributes to the overall readiness score.

This made the application feel less like a static dashboard and more like an operational decision simulator.

---

## Prior Authorization Logic

The simulator includes different Prior Authorization scenarios, including:

- Approved
- Pending
- Denied
- Appeal required
- No further action required

In my scenario, the Prior Authorization had already been approved, so the simulator displayed:

> **Continue — no further PA action required.**

This allowed the workflow to focus on the remaining admission risks instead of repeating unnecessary authorization steps.

---

## Care Coordination

One of the most useful sections was the **Care Coordination** panel.

It explains how different teams contribute to the admission process.

### Attending Physician

Oversees the plan of care and provides the final admission order.

### Case Manager

Coordinates level-of-care placement and payer communication.

### Nursing

Confirms bed readiness and unit-level clinical handoff.

### Utilization Review

Performs concurrent review and identifies denial risks against medical necessity criteria.

This helped me understand that hospital admission is not managed by a single person or department.

It is a coordinated workflow involving multiple operational and clinical teams.

---

## Medical Necessity

The simulator also introduced the role of medical necessity criteria.

For inpatient admissions, documentation must support the required level of care before Utilization Review.

The application referenced criteria frameworks such as:

- InterQual
- Milliman

This showed how clinical documentation, admission status, and payer requirements are connected.

---

## What I Learned

### 1. Admission readiness is a multi-factor decision

A patient may be clinically ready for admission but still face operational blockers.

Readiness depends on multiple factors being resolved together:

- Authorization
- Insurance
- Documentation
- Orders
- Consent
- Bed availability

### 2. A score makes operational risk easier to understand

The dynamic readiness score converts multiple workflow conditions into one visible indicator.

Instead of manually checking every status, the user can immediately see whether the admission is progressing or still at risk.

### 3. Approved Prior Authorization does not mean the workflow is complete

My scenario had an approved PA but only a **58% readiness score**.

This was an important learning because several other dependencies were still unresolved.

### 4. Healthcare operations require coordination across teams

The Attending Physician, Case Manager, Nursing team, and Utilization Review team all have different responsibilities.

A delay from one team can affect the entire admission timeline.

### 5. Interactive workflows explain dependencies better than static diagrams

Completing actions and watching the readiness score change made the relationship between different workflow stages easier to understand.

---

## Key Technical Concepts

- JavaScript state management
- Dynamic readiness scoring
- Conditional workflow logic
- Status updates
- Event-driven interactions
- Scenario configuration
- Risk-state tracking
- Timeline progression
- Conditional UI rendering
- Responsive dashboard design

---

## Limitation

The application uses the Tailwind CSS CDN for rapid prototyping, which generates a browser console warning because the CDN build is not recommended for production.

This does not affect the functionality of the local prototype.

A production version would use a compiled Tailwind CSS build through the Tailwind CLI or a build tool.

---

## Key Takeaway

The most important insight from this task was:

> **A patient can be clinically ready but operationally unready for admission.**

Hospital admission depends on several interconnected systems. Prior Authorization is only one part of the process.

The real challenge is ensuring that insurance, documentation, physician orders, consent, bed availability, and care coordination are all ready at the same time.

---

## Conclusion

Day 28 expanded the healthcare workflow exploration from Prior Authorization into the broader hospital admission process.

Unlike the Day 27 story simulator, this application focuses on operational decision-making.

The user does not simply read what happens. They actively resolve blockers, improve the readiness score, and move the patient toward a final admission decision.

This task helped me understand how interactive simulations can make complex operational systems easier to explore.

---

## Challenge

**60 Days Claude Challenge — Day 28**

Built with Claude and explored through interactive healthcare workflow simulation.
