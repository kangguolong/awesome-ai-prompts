# Strategic Source Discovery for NotebookLM

## Use Case

Use this prompt before building a NotebookLM research notebook for a strategic decision. It helps discover, screen, and rank web sources before you decide which materials to add to the notebook.

## Best For

- NotebookLM source preparation
- ChatGPT with browsing
- Perplexity
- Gemini with web access

## Prompt

```text
I am building a high-quality research notebook for strategic decision-making.

Topic:
[TOPIC]

Decision I need to make:
[DECISION]

Context:
[CONTEXT]

Please discover sources from the web that help answer this decision.

Source requirements:
1. Prioritize authoritative, recent, data-rich sources.
2. Prefer primary sources: official documentation, government data, company filings, regulator publications, academic papers, standards bodies, reputable datasets, and credible market reports.
3. Include reputable secondary analysis only if it adds interpretation, comparison, or useful synthesis.
4. Avoid shallow SEO content, generic blog posts, duplicate articles, and promotional material unless clearly marked as vendor perspective.
5. Include sources that show both upside and downside.
6. Prefer sources that help validate or invalidate the decision, not just describe the topic.

For each source, provide:
- Source title
- Publisher
- Date
- URL
- Source type: primary / secondary / commentary / vendor
- Why it matters
- What decision question it helps answer
- Key evidence or data likely to be useful
- Reliability score from 1 to 5
- Recommendation: Must add / Optional / Reject

Return the result in this format:
1. Source selection strategy
2. Recommended sources table
3. Rejected or low-priority source types to avoid
4. Coverage gaps and missing evidence
5. Suggested source set for the first NotebookLM upload

After recommending sources, stop and wait for me to choose which ones to add.
Do not synthesize the final decision yet.
```

## Variables

| Placeholder | Description |
|---|---|
| `[TOPIC]` | The research topic, market, technology, product, policy, or opportunity being studied |
| `[DECISION]` | The final judgment the notebook should support, such as whether to build, buy, enter a market, adopt a tool, or invest |
| `[CONTEXT]` | Background, constraints, geography, time horizon, company situation, risk tolerance, and known assumptions |

## Example Usage

```text
Topic:
AI coding agents for backend engineering teams.

Decision I need to make:
Should I adopt Codex CLI, Claude Code, or another AI coding assistant for a small backend team?

Context:
The team has 5 engineers, mostly works in TypeScript and Python, and cares about productivity, security, code quality, repository access control, and long-term maintainability.
```

## Expected Output

A ranked source shortlist that helps the user decide what to add to NotebookLM before synthesis. The output should separate strong primary sources, useful secondary analysis, vendor perspectives, and sources to reject.

## Notes

- Use this prompt before uploading sources into NotebookLM.
- The goal is source curation, not final synthesis.
- For current topics, require recent sources and publication dates.
- For strategic decisions, include sources that challenge the preferred option.
- Vendor sources can be useful but should not dominate the notebook.
