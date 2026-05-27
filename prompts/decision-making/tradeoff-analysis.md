# Trade-off Analysis

## Use Case

Use this prompt when you need to compare multiple options and make a practical decision under constraints.

## Best For

- ChatGPT
- Claude
- Gemini

## Prompt

```text
You are helping me make a practical decision by analyzing trade-offs, risks, upside, downside, and second-order effects.

Context:
[CONTEXT]

Decision to make:
[DECISION]

Options:
[OPTIONS]

Constraints:
[CONSTRAINTS]

Evaluation criteria:
[CRITERIA]

Return the analysis in this format:
1. Core decision summary
2. Ranked recommendation
3. Trade-off table comparing each option
4. Key risks and mitigations
5. Second-order effects
6. Best short-term action
7. Best long-term strategy
8. Conditions that would change the recommendation
```

## Variables

| Placeholder | Description |
|---|---|
| `[CONTEXT]` | Background, goals, current situation, and relevant facts |
| `[DECISION]` | The specific decision being made |
| `[OPTIONS]` | The options to compare |
| `[CONSTRAINTS]` | Budget, timing, risk tolerance, resources, dependencies, or exclusions |
| `[CRITERIA]` | Decision criteria such as cost, speed, quality, scalability, risk, or reversibility |

## Example Usage

```text
Context:
I am choosing between building an internal admin tool, buying a SaaS product, or delaying the project.

Decision to make:
Which option should we choose for the next 6 months?

Options:
1. Build internally
2. Buy SaaS
3. Delay until next quarter

Constraints:
Small engineering team, limited budget, need operational improvement quickly.

Evaluation criteria:
Time to value, total cost, maintenance burden, flexibility, security, and scalability.
```

## Expected Output

A structured decision brief with a clear recommendation, comparison table, risk analysis, and execution guidance.

## Notes

- Best used when there are two to five realistic options.
- Add quantitative data when available.
- Ask the model to state assumptions when information is incomplete.
