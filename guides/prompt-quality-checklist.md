# Prompt Quality Checklist

Use this checklist before adding or reviewing a prompt.

## Core Quality

- [ ] Does the prompt solve a real workflow?
- [ ] Is it reusable across multiple situations?
- [ ] Is the goal clear?
- [ ] Are the required inputs clear?
- [ ] Is the expected output defined?
- [ ] Is the prompt not unnecessarily long?
- [ ] Can a user copy, customize, and run it quickly?

## Structure

- [ ] Does the file follow [`prompts/_template.md`](../prompts/_template.md)?
- [ ] Are placeholders documented?
- [ ] Is there an example usage section?
- [ ] Are assumptions or limitations documented?
- [ ] Is the file named with lowercase kebab-case?
- [ ] Is the category appropriate?

## Reusability

- [ ] Can the prompt work across more than one narrow scenario?
- [ ] Does it avoid hard-coded facts that will go stale?
- [ ] Does it avoid unnecessary tool-specific behavior?
- [ ] If tool-specific, is it placed under `prompts/tool-specific/`?

## Safety and Reliability

- [ ] Does it avoid jailbreaks or bypass instructions?
- [ ] Does it avoid misleading guarantees?
- [ ] Does it encourage verification when accuracy matters?
- [ ] Does it mention risks, failure modes, or review steps where relevant?

## Practical Standard

A strong prompt should help a user produce a useful output faster than they could by writing from scratch.

Reject prompts that are clever but not operationally useful.
