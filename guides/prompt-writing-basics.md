# Prompt Writing Basics

Good prompts are not magic phrases. They are structured task instructions.

## A Useful Prompt Defines

1. **Role or perspective** when it improves the task
2. **Context** the model needs
3. **Goal** the user wants to achieve
4. **Constraints** the model must respect
5. **Inputs** the model should analyze
6. **Output format** the response should follow
7. **Quality checks** the model should apply before answering

## Basic Pattern

```text
You are helping with [ROLE OR WORKFLOW].

Context:
[CONTEXT]

Goal:
[GOAL]

Input:
[INPUT]

Constraints:
[CONSTRAINTS]

Return the result in this format:
[OUTPUT_FORMAT]

Before finalizing, check for:
[QUALITY_CHECKS]
```

## Practical Tips

- Use specific workflows instead of vague expert roles.
- Provide enough context for the model to make useful trade-offs.
- Define the output format when you need structured results.
- Include constraints, exclusions, and success criteria.
- Ask for risks, assumptions, and edge cases when stakes are high.
- Keep templates modular so users can adapt them quickly.

## Common Failure Modes

| Failure Mode | Example | Better Approach |
|---|---|---|
| Vague role | "Act as an expert" | "Review this API design for reliability, security, and scalability risks" |
| Missing context | "Improve this" | Provide audience, goal, tone, and constraints |
| No output format | "Analyze this" | Request a table, checklist, brief, or ranked options |
| Too much scope | "Build my business strategy" | Split into market, customer, pricing, channel, and execution prompts |
| Fragile prompt | Long prompt with many hidden rules | Use clear sections and reusable placeholders |

## Better Prompt Example

```text
You are reviewing a backend API design for production readiness.

Context:
[CONTEXT]

Input:
[API_DESIGN]

Focus on:
- Reliability
- Security
- Scalability
- Observability
- Operational complexity

Return:
1. Executive summary
2. Risk table with severity and likelihood
3. Recommended changes ranked by impact
4. Open questions
```
