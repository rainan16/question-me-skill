# Question Me Skill

> "No-one knows exactly what they want"
> — David Thomas & Andrew Hunt, *The Pragmatic Programmer*

## The Problem

You tell an agent what you want.

It builds something. 

And it's not what you meant.

This isn't an AI problem, but it's a human one. People rarely know exactly what they want upfront, and vague instructions lead to misaligned results. The agent isn't mind-reading. It's following your words literally.

How to fix this? Don't just tell the agent what to build. Let it question you first.

## The Solution

This skill helps you align with the AI agent before you get started, and think deeply about the change you're making. 

**Use it every time you want to make a change, challenge a design or refine an idea.**

## How It Works

The `question-me` skill follows a structured questioning approach:

1. **Intent Clarification** — If your request is vague, the agent uses the intent-refine guide to understand context
2. **One Question at a Time** — Multiple-choice options (A/B/C/D) with a recommended answer
3. **Adaptive Framework** — Infers which dimensions matter based on your input
4. **Inconsistency Detection** — Flags contradictions in your answers
5. **Structured Output** — Produces a refined intent, key decisions, open questions, and next steps

## Installation

Place the `.agents/skills/question-me/` directory in your project root or when using e.g. Opencode in `~/.config/opencode/skills/`.

## Usage

Simply mention "question me" or ask the agent to grill your idea. The skill will activate automatically.
