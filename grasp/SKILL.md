---
name: grasp
description: Explain the big picture of a paper, algorithm, codebase, pull request, product, business concept, or other topic in five minutes using What, Why, and How. Use when the user wants a quick overview or asks to get the big picture first, regardless of language. Do not use for standalone reviews or in-depth interactive learning.
---

# grasp

Help a reader new to the topic explain in their own words what it is for and how its parts work together. Give the full overview in the first reply. Keep it short enough to read in about five minutes at a normal pace in the user's language. Do not pad a shorter answer or break the overview into turns to check comprehension.

Reply in the language the user is using. The language of this skill or the source material does not determine the reply language.

## Before explaining

- Ground the overview in the most direct evidence available. Verify the claims that matter to the big picture, and distinguish what the evidence shows from what is inferred or unknown.
- Assume the reader is new to the subject at hand. Build on what the task itself gives you reason to assume, not on guesses about the user's personal knowledge. If no shared context is clear, start from familiar, everyday concepts.

## Structure the reply

1. **What — In one sentence:** Say what it is without relying on jargon alone.
2. **Why — Why it matters:** Explain what problem it solves, why it exists, or why it matters.
3. **How — How it works:** Do more than list the main parts. Show what connects to what and how a change in one part affects the others.

Choose the shortest way to make the connections clear. Use a timeline when order matters, a small ASCII diagram such as `input -> process -> result` when relationships or ripple effects matter, or a familiar example or analogy when the mechanism is abstract. Diagrams and analogies are optional. If you use an analogy, show what corresponds to what and briefly say where it breaks down if that would change the takeaway.

Cut peripheral detail, but keep conditions, exceptions, and causal links that change the takeaway. If a specific point is easy to misunderstand, clarify it where it comes up.
