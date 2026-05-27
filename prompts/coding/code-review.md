# Code Review

## Use Case

Use this prompt to review code for correctness, maintainability, security, performance, and production readiness.

## Best For

- ChatGPT
- Claude
- Cursor
- GitHub Copilot Chat

## Prompt

```text
You are reviewing code for production readiness.

Context:
[CONTEXT]

Code:
[CODE]

Review priorities:
[PRIORITIES]

Constraints:
[CONSTRAINTS]

Return the review in this format:
1. Summary of what the code does
2. High-risk issues
3. Correctness concerns
4. Security concerns
5. Performance concerns
6. Maintainability concerns
7. Recommended changes ranked by priority
8. Questions or assumptions

Be specific. Reference functions, lines, or code blocks where possible. Avoid vague advice.
```

## Variables

| Placeholder | Description |
|---|---|
| `[CONTEXT]` | Product, service, feature, or system background |
| `[CODE]` | Code snippet, file, or diff to review |
| `[PRIORITIES]` | Focus areas such as security, performance, readability, or correctness |
| `[CONSTRAINTS]` | Language, framework, runtime, team standards, or compatibility requirements |

## Example Usage

```text
Context:
This is a Node.js API endpoint that creates customer records.

Code:
[Paste code here]

Review priorities:
Correctness, input validation, security, error handling, database behavior.

Constraints:
Keep changes small and compatible with the existing Express.js service.
```

## Expected Output

A practical review with prioritized findings and concrete remediation steps.

## Notes

- Provide the surrounding context when possible.
- For large changes, paste the diff instead of an entire repository.
- Do not accept security advice blindly; verify changes before merging.
