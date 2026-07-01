# Few-Shot Prompting Pattern

## What it is

Few-shot prompting is a technique where you provide the model with a small number of examples before asking it to perform a task.

These examples guide the model’s behavior, style, and structure.

---

## When to use it

Use few-shot prompting when:
- You need consistent formatting
- The task is ambiguous without examples
- You want to enforce a specific style
- Zero-shot prompting is unreliable

---

## Template

Task instruction:
[DEFINE TASK]

Examples:

Input: [Example Input 1]
Output: [Example Output 1]

Input: [Example Input 2]
Output: [Example Output 2]

Input: [New Input]
Output:

##Example

Prompt:

Classify customer messages into categories: Billing, Technical Issue, or General Inquiry.

Input: "I was charged twice this month"
Output: Billing

Input: "The app keeps crashing when I open it" 
Output: Technical Issue

Input: "How do I change my password?" 
Output: General Inquiry

Input: "I don’t understand my latest invoice" 
Output:


---

## Why it works

Few-shot prompting improves performance by:
- Showing expected behavior instead of describing it
- Reducing ambiguity
- Aligning model output with user expectations
- Improving consistency across responses

---

## Common mistakes

- Using too many examples (dilutes signal)
- Using inconsistent formatting
- Providing low-quality examples
- Not matching input/output structure clearly

---

## Best practices

- Use 2–5 high-quality examples
- Keep formatting identical across examples
- Make examples representative of real inputs
- Keep outputs short and consistent

---

## Real-world use cases

- Content classification systems
- Chatbot intent detection
- Data labeling tasks
- Structured output generation
- Customer support routing
