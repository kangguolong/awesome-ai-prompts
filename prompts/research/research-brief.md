# Research Brief

## Use Case

Use this prompt to produce a structured research brief on a topic, question, market, technology, or trend.

## Best For

- ChatGPT with browsing
- Claude
- Gemini
- Perplexity

## Prompt

```text
You are preparing a concise research brief.

Research topic:
[TOPIC]

Context:
[CONTEXT]

Audience:
[AUDIENCE]

Research questions:
[QUESTIONS]

Constraints:
[CONSTRAINTS]

Return the brief in this format:
1. Executive summary
2. Key findings
3. Important evidence or sources
4. Areas of uncertainty
5. Risks, limitations, or conflicting views
6. Practical implications
7. Recommended next questions

If current or factual accuracy matters, clearly separate verified facts from assumptions and cite sources where possible.
```

## Variables

| Placeholder | Description |
|---|---|
| `[TOPIC]` | Subject being researched |
| `[CONTEXT]` | Why the research is needed and how it will be used |
| `[AUDIENCE]` | Intended reader, such as executives, engineers, investors, or operators |
| `[QUESTIONS]` | Specific questions the brief should answer |
| `[CONSTRAINTS]` | Time horizon, geography, source requirements, depth, exclusions, or format |

## Example Usage

```text
Research topic:
AI coding assistants for backend engineering teams.

Context:
I am evaluating whether to introduce coding assistants into a small engineering team.

Audience:
Technical founder and engineering lead.

Research questions:
What are the benefits, risks, adoption requirements, and common failure modes?

Constraints:
Focus on practical implementation and risk management. Keep the brief concise.
```

## Expected Output

A structured brief that separates findings, uncertainty, risks, and practical implications.

## Notes

- Use browsing or source citations when the answer depends on current facts.
- For controversial topics, ask for competing viewpoints.
- For high-stakes decisions, verify claims against primary sources.
