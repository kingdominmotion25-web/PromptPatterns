# Agent-Style Prompting System

## What it is

Agent-style prompting is a structured framework that simulates autonomous behavior in an AI model by breaking tasks into:

1. Planning
2. Execution
3. Reflection

This creates a loop similar to how AI agents operate in production systems.

---

## When to use it

Use this pattern when:
- Tasks require multiple steps
- You need iterative improvement
- Decisions depend on intermediate results
- You are simulating autonomous workflows

---

## Core Loop

### 1. Plan
Define the steps required to solve the problem.

### 2. Execute
Carry out each step one at a time.

### 3. Reflect
Evaluate the results and improve the approach if needed.

---

## Template

You are an autonomous AI agent.

Your task is:
[INSERT TASK]

---

Step 1: Plan
Break the task into clear steps.

Step 2: Execute
Perform each step sequentially.

Step 3: Reflect
Analyze results and identify improvements.

Step 4: Refine
If needed, adjust the plan and repeat execution.

Final Output:
[RESULT]

---

## Example

### Task:
Create a simple study plan for learning Python in 7 days.

---

### Step 1: Plan
- Day 1: Basics
- Day 2: Variables and data types
- Day 3: Control flow
- Day 4: Functions
- Day 5: Lists and dictionaries
- Day 6: Mini project
- Day 7: Review

---

### Step 2: Execute
Each day includes learning + practice exercises.

---

### Step 3: Reflect
The plan may be too dense for beginners.

---

### Step 4: Refine
Add more practice time and reduce daily scope.

---

### Final Output:
A simplified, beginner-friendly 7-day Python learning plan.

---

## Why it works

Agent-style prompting works because it:
- Simulates structured reasoning loops
- Introduces iteration instead of single-pass output
- Encourages self-correction
- Breaks complex tasks into manageable steps

---

## Common mistakes

- Skipping reflection step
- Treating it like a simple step-by-step prompt
- Not iterating based on feedback
- Overloading execution phase

---

## Best practices

- Always include a reflection phase
- Keep steps modular and clear
- Allow iteration when needed
- Use for multi-step real-world tasks

---

## Real-world applications

- AI assistants (task planners)
- Workflow automation systems
- Coding agents
- Research assistants
- Multi-step decision engines
