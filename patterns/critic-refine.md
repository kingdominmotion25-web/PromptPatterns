# Critic–Refine Prompting Pattern

## What it is

The Critic–Refine pattern improves output quality by forcing the model to:
1. Generate an initial response
2. Critically evaluate that response
3. Improve it based on self-critique

This mimics a human editing process.

---

## When to use it

Use this pattern when:
- Output quality is important
- Tasks require reasoning or writing
- You want fewer mistakes or hallucinations
- You need structured, polished responses

---

## Template

Step 1: Generate an initial answer.

Step 2: Critically evaluate your answer for:
- Accuracy
- Completeness
- Clarity
- Logical consistency

Step 3: Improve the answer based on your critique.

Step 4: Provide the final improved response.

---

## Example

### Prompt:

Write a short explanation of why the sky is blue.

---

### Step 1: Initial Answer

The sky is blue because of how light interacts with the atmosphere.

---

### Step 2: Critique

- The explanation is too vague
- It does not mention Rayleigh scattering
- It lacks scientific detail
- It is not beginner-friendly enough

---

### Step 3: Improved Answer

The sky appears blue because of a phenomenon called Rayleigh scattering. When sunlight enters Earth’s atmosphere, shorter blue wavelengths scatter more than other colors, making the sky look blue to our eyes.

---

## Why it works

This pattern improves outputs by:
- Reducing shallow responses
- Encouraging self-correction
- Increasing factual accuracy
- Improving clarity and structure

---

## Common mistakes

- Skipping the critique step
- Not defining evaluation criteria
- Overcomplicating simple tasks
- Producing overly long refinements

---

## Related patterns

- Chain-of-Thought Prompting
- Role Prompting
- Self-Consistency Prompting
