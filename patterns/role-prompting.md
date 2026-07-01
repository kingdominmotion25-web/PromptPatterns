# Role Prompting Pattern

## What it is

The Role Prompting Pattern assigns a specific role, expertise level, and mindset to the AI before it responds. This improves consistency, tone, and domain accuracy.

---

## When to use it

Use this pattern when you need:
- Expert-level responses
- Consistent tone or style
- Domain-specific knowledge framing
- Structured outputs

---

## Template

You are a [ROLE] with [EXPERIENCE LEVEL].

Your task is to:
- [TASK 1]
- [TASK 2]
- [TASK 3]

Constraints:
- Be clear and concise
- Avoid unnecessary assumptions
- Ask clarifying questions if needed

Output format:
[DEFINE STRUCTURE]

---

## Example

### Prompt:

You are a senior software engineer with 10 years of experience.

Your task is to explain how Git works to a beginner.

Constraints:
- Use simple language
- Include a real-world analogy
- Keep it under 200 words

Output format:
- Explanation
- Analogy
- Summary

---

## Why it works

Assigning a role activates relevant patterns in the model’s training data, improving:
- Accuracy
- Tone consistency
- Depth of reasoning
- Output structure

---

## Common mistakes

- Using vague roles ("helpful assistant")
- Overloading roles with too many instructions
- Not defining output format

---

## Related patterns

- Chain-of-Thought Prompting
- Few-Shot Prompting
- Critic-Refine Pattern
