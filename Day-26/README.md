# Day 26 — Prior Authorization Workflow Simulator

## Overview

For Day 26 of the **60 Days Claude Challenge**, I built an interactive **Prior Authorization Workflow Simulator** using Claude.

The goal was to understand how a healthcare prior authorization request moves through the complete journey — from the initial patient visit to medical necessity review, document collection, payer submission, review, and final decision.

The simulator was generated as a single HTML application using HTML, CSS, and vanilla JavaScript.

---

## Final Application

![Prior Authorization Workflow Simulator](Screenshot%20(252).png)

The simulator includes:

- Multiple patient scenarios with different denial risks
- A six-stage prior authorization journey tracker
- Medical necessity evaluation
- Required document collection
- Payer submission and review
- Approval, pend, and denial outcomes
- Peer-to-peer review and formal appeal pathways
- Elapsed-day tracking
- Efficiency scoring
- Final workflow summary and activity log

---

## Workflow

The simulated prior authorization journey follows six stages:

1. **Patient Visit** — A physician recommends a treatment or procedure.
2. **Medical Necessity Review** — The case is checked against payer criteria.
3. **Document Collection** — Required clinical evidence is assembled.
4. **Submission** — The complete request is sent to the payer.
5. **Payer Review** — The Utilization Management team evaluates the case.
6. **Decision** — The request may be approved, pended, or denied.

A denial can also lead to a **Peer-to-Peer Review** or a **Formal Appeal**.

---

## Scenarios Included

The application contains four patient scenarios:

- Elective Knee Surgery
- Lumbar Spine MRI
- Specialty Medication (Biologic)
- Inpatient Admission for Pneumonia

Each scenario has its own:

- Clinical documentation requirements
- Medical necessity criteria
- Base denial risk
- Payer review time range

This made the simulator feel more like a workflow system rather than a static educational page.

---

## Interaction Issue and Fix

The first generated version looked complete, but the workflow was not reliably interactive in my browser.

The application depended heavily on **HTML5 drag-and-drop**. Although the underlying JavaScript logic existed, the workflow could feel stuck when drag events did not work properly.

I improved the interaction by adding **click/tap fallbacks**:

- Click the highlighted next workflow stage to move the case
- Click document chips to add them to the authorization packet
- Keep drag-and-drop available where supported

This made the simulator much easier and more reliable to use.

---

## What I Learned

### 1. A good-looking interface is not proof of functionality

The first output visually matched the task, but actual interaction testing exposed a usability problem. Generated applications must be tested as complete workflows, not judged from screenshots alone.

### 2. Drag-and-drop should not be the only interaction method

Drag-and-drop can behave differently across browsers and preview environments. Important actions should also have click or tap alternatives.

### 3. Healthcare workflows are state-driven

Each stage depends on the previous stage being completed. The simulator helped me understand how application state can control:

- Which workflow stage is active
- Which action is unlocked
- Which documents are complete
- How many days have elapsed
- What final outcome is possible

### 4. Simulation logic creates better learning experiences

Instead of simply explaining prior authorization, the application lets the user experience delays, incomplete documentation, denials, pends, appeals, and approvals.

### 5. AI-generated code still needs debugging

Claude generated a substantial working structure, but the interaction issue required reviewing the actual code and improving the UX. The task reinforced that AI can accelerate development, but testing and refinement are still necessary.

---

## Key Technical Concepts

- HTML5 Drag and Drop API
- DOM event handling
- Click and tap fallbacks
- JavaScript state management
- Conditional workflow progression
- Randomized simulation outcomes
- Dynamic DOM rendering
- Modal-based decisions
- Canvas confetti animation
- Responsive CSS layout

---

## Conclusion

Day 26 was not just about generating another HTML application. The most useful part was discovering that a visually complete product can still fail at the interaction layer.

The original simulator had the workflow logic, but its dependence on drag-and-drop made it unreliable. Adding click-based alternatives turned it into a much more usable application.

The biggest takeaway from this task:

> **Generate, test, find what breaks, and improve it. A polished UI is only useful when the workflow actually works.**

---

## Challenge

**60 Days Claude Challenge — Day 26**

Built with Claude and refined through testing and debugging.
