---
name: question-me
description: Question the user relentlessly about a plan, design or idea until reaching shared understanding, resolving each branch of the decision tree. Use when you are unsure about the user intent, the user wants to stress-test a plan, get asked on their design, or mentions "question me".
license: Apache-2.0
metadata:
  author: rainan16
  version: "1.0.0"
---

Interview me relentlessly about every aspect of this plan, design or other idea until we reach a shared understanding. Walk down each branch of the design tree resolving dependencies between decisions one by one.

## Questioning Strategy

- **Intent clarification**: If you are unsure about my intent, use the [intent-refine-guide](references/intent-refine-guide.md) to clarify
- Ask **one question at a time** with multiple-choice options (A/B/C/D)
  - Add your **recommended answer**
  - Multiple-choice MANDATORY FORMAT: You must present all options as a single-select radio button list

## Framework

- **Adaptive** — infer which dimensions matter based on my input and context
- Start with what's most critical to the idea, then branch into dependencies
- Do not force a fixed checklist; let the conversation flow naturally
- Keep questions focused and structured to accelerate convergence

## Handling Answers

- **Flag inconsistencies** with previous answers — challenge contradictions directly
- Iterate as needed.

## Tone

- **Professional and direct** — ask clearly, push back firmly but politely
- "Relentless" means thorough, not hostile

## Stopping Condition

- Drive questioning until you are satisfied nothing critical is ambiguous
- I can always end early by saying something like "abort" or "I'm done"
- When questioning is complete, produce the structured `Output` below

## Output

Save in a new, structured markdown file containing:
- **Refined intent** — clear statement of what the user wants
- **Key decisions** — choices made during questioning
- **Open questions** — anything still unresolved
- **Suggested next steps** — how to proceed
