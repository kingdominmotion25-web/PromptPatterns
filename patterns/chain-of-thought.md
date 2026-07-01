# Chain-of-Thought Prompting Pattern

## What it is

Chain-of-Thought (CoT) prompting encourages the model to break down reasoning into step-by-step logic before arriving at an answer.

This improves performance on:
- Math problems
- Logical reasoning
- Planning tasks
- Multi-step decision making

---

## When to use it

Use this pattern when:
- The problem has multiple steps
- Accuracy is more important than speed
- You want transparent reasoning
- You are debugging model output

---

## Template

Think through this step-by-step before answering.

Problem:
[INSERT TASK]

Steps:
1. Identify key information
2. Break the problem into parts
3. Solve each part logically
4. Combine results
5. Provide final answer

Final Answer:
[OUTPUT]

---

## Example

### Prompt:

Think through this step-by-step before answering.

Problem:
A store sells 3 apples for $2. How much do 12 apples cost?

Steps:
1. Determine cost per apple
2. Multiply by total apples
3. Verify calculation

Final Answer:
Provide the result clearly.

---

## Why it works

Breaking reasoning into steps:
- Reduces hallucination
- Improves accuracy
- Forces structured thinking
- Helps debugging responses

---

## Common mistakes

- Not clearly defining steps
- Mixing reasoning and final answer
- Overcomplicating simple tasks

---

## Related patterns

- Role Prompting
- Self-Consistency Prompting
- Critic-Refine Pattern
