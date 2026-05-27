# Contributing to Awesome AI Prompts

Thanks for helping improve this repository.

This is a curated prompt library, not a prompt dump. Contributions should improve the usefulness, consistency, and reliability of the collection.

## What We Accept

Good prompts should be:

- Practical and workflow-oriented
- Reusable across multiple situations
- Clear about required inputs
- Clear about expected outputs
- Easy to copy, customize, and run
- Documented with examples and limitations
- Placed in the correct category

## What We Do Not Accept

Please avoid submitting:

- Generic "act as an expert" prompts without a concrete workflow
- Jailbreaks, bypasses, or prompt-injection techniques
- Meme prompts or entertainment-only prompts
- Duplicates of existing prompts
- Overly long prompts that are difficult to adapt
- Tool-specific prompts outside `prompts/tool-specific/`
- Prompts that make unsafe, misleading, or unsupported claims

## Prompt File Requirements

Each prompt should be a small Markdown file using lowercase kebab-case.

Good filenames:

```text
code-review.md
market-analysis.md
tradeoff-analysis.md
meeting-summary.md
```

Avoid:

```text
Best Prompt Ever.md
prompt1.md
ChatGPT Hack.md
```

Use [`prompts/_template.md`](prompts/_template.md) as the base format.

## Required Sections

Each prompt should include:

1. Use Case
2. Best For
3. Prompt
4. Variables
5. Example Usage
6. Expected Output
7. Notes

## Review Criteria

A prompt is ready to merge when:

- The workflow is clear.
- The prompt can be reused beyond one narrow example.
- Placeholders are documented.
- The output format is specific.
- Risks, assumptions, or limitations are noted where relevant.
- The file is named and categorized consistently.

## Pull Request Checklist

Before opening a pull request, confirm that:

- [ ] The prompt solves a real workflow.
- [ ] The file uses lowercase kebab-case.
- [ ] The prompt follows the standard template.
- [ ] The placeholders are documented.
- [ ] The expected output is defined.
- [ ] The prompt does not duplicate an existing prompt.
- [ ] Tool-specific dependencies are clearly marked.

## Category Guidance

Add prompts to existing categories unless a new category is clearly justified.

New categories should only be added when there are enough related prompts to support them. Avoid creating many narrow categories too early.
