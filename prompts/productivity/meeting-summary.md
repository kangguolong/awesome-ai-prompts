# Meeting Summary

## Use Case

Use this prompt to turn meeting notes or transcripts into a structured summary with decisions, action items, owners, and risks.

## Best For

- ChatGPT
- Claude
- Gemini

## Prompt

```text
Summarize the meeting notes or transcript below into a practical operating summary.

Context:
[CONTEXT]

Meeting notes or transcript:
[INPUT]

Constraints:
[CONSTRAINTS]

Return the summary in this format:
1. Executive summary
2. Key decisions
3. Action items with owner and due date
4. Open questions
5. Risks or blockers
6. Follow-up agenda

If an owner or due date is unclear, mark it as "Unassigned" or "TBD" instead of guessing.
```

## Variables

| Placeholder | Description |
|---|---|
| `[CONTEXT]` | Meeting purpose, team, project, or background |
| `[INPUT]` | Notes, transcript, or rough meeting record |
| `[CONSTRAINTS]` | Required level of detail, naming conventions, exclusions, or formatting rules |

## Example Usage

```text
Context:
Weekly product and engineering sync for the billing project.

Meeting notes or transcript:
[Paste transcript here]

Constraints:
Keep the executive summary under 5 bullets. Extract only concrete action items.
```

## Expected Output

A concise summary that separates decisions, tasks, open questions, and risks.

## Notes

- For transcripts, remove irrelevant small talk before using if possible.
- Ask the model not to invent owners, dates, or decisions.
- Useful for async updates and project tracking.
