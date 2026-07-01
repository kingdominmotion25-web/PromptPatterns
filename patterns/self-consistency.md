# Self-Consistency Prompting Pattern

## What it is

Self-consistency prompting improves accuracy by generating multiple independent reasoning paths for the same problem, then selecting the most consistent answer.

Instead of relying on a single response, the model explores multiple solutions.

---

## When to use it

Use this pattern when:
- The problem involves reasoning or calculation
- Accuracy is more important than speed
- There may be multiple valid approaches
- You want to reduce random errors

---

## Template

Solve the problem below using multiple reasoning paths.

Problem:
[INSERT QUESTION]

Step 1: Generate at least 3 different approaches to solving the problem.

Step 2: Solve the problem independently using each approach.

Step 3: Compare the results.

Step 4: Choose the most consistent and reliable answer.

Final Answer:
[OUTPUT]

---

## Example

### Problem:
A store sells apples for $2 each. How much do 15 apples cost?

---

### Approach 1:
2 × 15 = 30

### Approach 2:
10 apples = 20, 5 apples = 10 → total = 30

### Approach 3:
Repeated addition confirms 30

---

### Final Answer:
$30

---

## Why it works

Self-consistency improves reliability by:
- Reducing random reasoning errors
- Encouraging multiple solution paths
- Highlighting contradictions
- Increasing confidence in final answers

---

## Common mistakes

- Using identical reasoning paths (no diversity)
- Skipping comparison step
- Overcomplicating simple problems
- Not selecting a final answer explicitly

---

## Best practices

- Ensure each solution path is meaningfully different
- Use 3–5 reasoning attempts
- Always compare outputs before finalizing
- Use for logic-heavy tasks, not simple questions

---

## Real-world applications

- Math reasoning systems
- AI research assistants
- Automated decision-making tools
- Code validation systems
- Multi-agent reasoning frameworks
