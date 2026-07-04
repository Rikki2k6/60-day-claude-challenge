# Day 27 — Prior Authorization Story Simulator

## Overview

For Day 27 of the **60 Days Claude Challenge**, I continued from the Day 26 healthcare workflow task and built a **Prior Authorization Story Simulator** using Claude.

Instead of presenting Prior Authorization as a dashboard or process map, this application explains the workflow through an interactive story. The user follows **Rahul**, a patient diagnosed with Rheumatoid Arthritis, while **Priya**, a Healthcare Operations Specialist, explains what happens behind the scenes.

The application was generated as a single HTML file using HTML, Tailwind CSS, and JavaScript.

---

## Final Application

![Prior Authorization Story Simulator](Screenshot%20(243).png)

The simulator includes:

- An eight-scene interactive healthcare story
- Two dialogue choices after every scene
- A progress bar that updates throughout the journey
- Patient, doctor, narrator, and healthcare operations perspectives
- Educational explanations of Prior Authorization concepts
- Different dialogue paths based on user choices
- A restart option to explore alternative responses

---

## Rahul's Journey

The story follows Rahul through eight chapters:

### 1. Doctor Visit

Rahul is diagnosed with Rheumatoid Arthritis and prescribed Humira.

### 2. Insurance Roadblock

The treatment requires Prior Authorization before insurance coverage.

### 3. What is Prior Authorization?

Priya explains why insurers review certain treatments before agreeing to pay for them.

### 4. Insurance Review

The payer checks:

- Eligibility
- Clinical documentation
- Diagnosis codes
- Step-therapy history

### 5. Denial

The request is denied because evidence of previous step therapy is missing.

### 6. Appeal

The provider submits the missing documentation and builds a stronger medical necessity case.

### 7. Approval

The appeal succeeds and the treatment is authorized.

### 8. Takeaways

The story ends with lessons from both the patient and healthcare operations perspectives.

---

## Interactive Experience

After every chapter, the user chooses between two responses.

For example, Rahul can:

- Ask about treatment cost or side effects
- Wait for the insurance process or ask for updates
- Ask about step therapy or authorization timelines
- React emotionally to a denial or immediately ask about next steps
- Explore the patient perspective or the system perspective

The choices do not change the core healthcare outcome, but they create different dialogue paths and make the learning experience more engaging.

---

## What I Learned

### 1. Storytelling can explain complex systems better than static documentation

Prior Authorization involves providers, payers, documentation, clinical criteria, denials, and appeals.

Presenting these concepts through Rahul's journey made the entire process easier to understand.

### 2. Educational applications do not always need complex mechanics

The application is technically simple, but the combination of dialogue, choices, progression, and context creates an effective interactive experience.

### 3. UI state is central to interactive storytelling

The application tracks:

- Current scene
- Progress percentage
- Dialogue sequence
- User choice
- Follow-up conversation
- Continue and restart states

This helped me understand how JavaScript state controls a story-driven interface.

### 4. Different perspectives improve understanding

The simulator combines:

- Rahul's patient experience
- Dr. Patel's clinical perspective
- Priya's healthcare operations explanations
- The payer's administrative requirements

This makes the workflow easier to understand than showing only one side of the process.

### 5. Progressive disclosure keeps information manageable

Instead of displaying the entire process at once, the simulator reveals information scene by scene.

This prevents the user from being overwhelmed by a complex healthcare workflow.

---

## Key Technical Concepts

- JavaScript state management
- Dynamic DOM creation
- Event listeners
- Conditional dialogue paths
- Sequential scene rendering
- Timed message display
- Progress-bar updates
- Scroll management
- Responsive interface design
- Restart and replay functionality

---

## Files

- `prior_authorization_story_simulator.html` — Complete interactive story application
- `Screenshot (243).png` — Final scene and takeaways screenshot

---

## Conclusion

Day 27 transformed the Prior Authorization workflow from Day 26 into a more human-centered learning experience.

The most important improvement was not adding more technical complexity. It was changing the way the information was presented.

Instead of asking the user to operate a workflow dashboard, the simulator lets them experience the process through a patient's story.

The biggest takeaway from this task:

> **Complex systems become easier to understand when users experience them as a journey rather than read them as a process.**

---

## Challenge

**60 Days Claude Challenge — Day 27**

Built with Claude and explored through interactive storytelling.
