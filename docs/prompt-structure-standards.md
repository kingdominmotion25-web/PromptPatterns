# Prompt Structure & Formatting Standards

## Overview

Consistent prompt structure improves:
- Reliability of LLM outputs
- Readability of prompts
- Debugging and iteration speed
- Reusability across projects

This document defines a standard format for writing high-quality prompts.

---

## Recommended Structure

A strong prompt should include the following sections:

### 1. Role
Defines who the model is acting as.

Example:
You are a senior software engineer with expertise in Python and system design.

---

### 2. Objective
Clearly state the task.

Example:
Your task is to explain how APIs work to a beginner.

---

### 3. Context
Provide necessary background information.

Example:
The audience has no prior technical knowledge.

---

### 4. Constraints
Define boundaries and rules.

Example:
- Keep explanation under 200 words
- Use simple language
- Avoid jargon

---

### 5. Output Format
Specify structure of response.

Example:
- Explanation
- Analogy
- Summary

---

## Full Example

You are a senior software engineer with expertise in Python.

Your task is to explain how APIs work.

Context:
The audience is non-technical beginners.

Constraints:
- Keep under 200 words
- Use simple language
- Include a real-world analogy

Output format:
- Explanation
- Analogy
- Summary

---

## Why this works

This structure improves:
- Clarity of instructions
- Output consistency
- Model performance
- Ease of debugging prompts

---

## Common mistakes

- Mixing role and task together
- Missing constraints
- Not specifying output format
- Overloading prompts with unnecessary detail

---

## Best Practice Rule

Always structure prompts in this order:

1. Role
2. Objective
3. Context
4. Constraints
5. Output Format

---

## Related Patterns

- Role Prompting
- Chain-of-Thought
- Critic–Refine
