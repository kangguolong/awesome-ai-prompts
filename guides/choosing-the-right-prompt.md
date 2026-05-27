# Choosing the Right Prompt

Use the workflow first, then select the prompt.

## Selection Framework

| User Need | Recommended Category |
|---|---|
| Review, debug, design, or document software | `prompts/coding/` |
| Understand a topic or compare sources | `prompts/research/` |
| Analyze markets, competitors, customers, or business models | `prompts/business/` |
| Draft, rewrite, summarize, or improve written content | `prompts/writing/` |
| Plan work, summarize meetings, or prioritize tasks | `prompts/productivity/` |
| Compare options, evaluate trade-offs, or assess risks | `prompts/decision-making/` |
| Learn a concept or build a study plan | `prompts/learning/` |
| Use a prompt that depends on a specific AI product | `prompts/tool-specific/` |

## Use General Prompts First

Prefer general workflow prompts unless the task depends on a specific tool feature.

Use `tool-specific/` only when the prompt relies on things like:

- Cursor repository context
- Perplexity web search behavior
- ChatGPT custom GPT instructions
- Claude artifact workflows
- GitHub Copilot coding environment assumptions

## When to Create a New Category

Create a new category only when:

- The workflow is meaningfully different from existing categories.
- There are enough related prompts to justify a folder.
- The category improves discoverability.
- The category is not just a narrow one-off topic.

When unsure, place the prompt in `misc/` first and reorganize later.
