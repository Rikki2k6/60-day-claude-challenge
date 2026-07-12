# Day 35

## Prompt Puzzle

Today I built an interactive Prompt Puzzle using Claude. The application turned prompt engineering into a game where I had to identify weak prompts, clean messy prompts, and build better prompts by combining role, context, and task clearly.

The simulator included three different challenge types and ended with a personalized Prompt Performance Report that showed accuracy, time, moves, hints used, and overall prompt score.

This task was useful because it showed how small changes in prompt structure can completely change the quality of the AI response.

---

## Interactive Experience

The simulator guides the user through multiple prompt engineering challenges.

The user can:

- Choose the domain and difficulty
- Drag and arrange prompt blocks in the correct order
- Remove unnecessary parts from messy prompts
- Select the best prompt from multiple options
- Review weak versus optimized outputs
- See a final performance report
- Replay with new randomized scenarios

Every challenge reinforces the idea that prompt quality matters as much as the task itself.

---

## What I Learned

### 1. Specificity improves output quality

When a prompt clearly names the role, context, and exact task, the AI gives a much better answer.

### 2. Too much length is not always better

Over-engineered prompts can become noisy and less effective. Clear and focused instructions work better.

### 3. Audience matters

A prompt should match the level of the user or the goal. Beginner prompts need plain language, while technical prompts can include more structure.

### 4. Structure gives control

Good prompts are easier to guide and debug because each part has a purpose.

### 5. Reusable prompts save time

Instead of rewriting the same instruction again and again, a strong prompt can be reused with only small changes.

---

## Key Technical Concepts

- Interactive HTML simulation
- JavaScript state management
- Drag-and-drop gameplay
- Conditional scoring system
- Dynamic feedback messages
- Randomized scenario generation
- Responsive UI layout
- Performance report generation

---

## Files

- `prompt-puzzle-datascience-beginner.html` — Complete Prompt Puzzle application
- `image(46).png` — Final performance report screenshot

---

## Conclusion

Day 35 showed that prompt engineering is not just about writing more text. It is about giving the AI the right structure, the right context, and the right level of detail.

The simulator made it clear that a strong prompt can produce a much stronger response, while a vague or bloated prompt often leads to weak results.

The biggest takeaway from this task:

> **A good prompt is not long — it is clear, specific, and purposeful.**

---

## Challenge

**60 Days Claude Challenge — Day 35**

Built with Claude and explored prompt engineering through an interactive Prompt Puzzle.
