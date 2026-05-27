# Awesome AI Prompts

A curated library of practical, reusable AI prompt templates for real-world workflows.

## Why This Exists

Most prompt collections are noisy, inconsistent, or too tool-specific. This repository focuses on prompts that solve repeatable workflows and can be adapted across AI tools.

## Principles

- **Workflow-first, not tool-first**: prompts are organized around tasks and outcomes.
- **Reusable by default**: templates use clear placeholders and expected output formats.
- **Practical over clever**: no gimmicks, jailbreaks, or fragile prompt hacks.
- **Quality over volume**: a smaller set of strong prompts is better than a large prompt dump.
- **Tool-specific only when justified**: tool-specific prompts belong under `prompts/tool-specific/`.

## Categories

| Category | Purpose |
|---|---|
| [`coding`](prompts/coding/) | Code review, debugging, architecture, API design, documentation |
| [`research`](prompts/research/) | Topic research, source comparison, brief generation, claim checking |
| [`business`](prompts/business/) | Market analysis, competitors, business models, positioning |
| [`writing`](prompts/writing/) | Drafting, rewriting, summarizing, style improvement |
| [`productivity`](prompts/productivity/) | Meeting summaries, planning, prioritization, operating cadence |
| [`decision-making`](prompts/decision-making/) | Trade-offs, risk reviews, option ranking, pre-mortems |
| [`learning`](prompts/learning/) | Study plans, concept breakdowns, skill development |
| [`tool-specific`](prompts/tool-specific/) | Prompts that depend heavily on a specific AI product |
| [`misc`](prompts/misc/) | Useful prompts that do not yet justify a dedicated category |

## How to Use

1. Browse a category.
2. Copy a prompt template.
3. Replace placeholders such as `[GOAL]`, `[CONTEXT]`, `[CONSTRAINTS]`, and `[OUTPUT_FORMAT]`.
4. Run the prompt in your AI tool of choice.
5. Adjust the prompt based on your domain, risk tolerance, and required level of detail.

## Prompt Format

Each prompt should include:

- Use case
- Best-fit tools
- Copy-paste-ready prompt block
- Variables/placeholders
- Example usage
- Expected output
- Notes, risks, or limitations

See [`prompts/_template.md`](prompts/_template.md) for the standard format.

## Contribution Standards

Contributions are welcome, but prompts must be practical, reusable, and clearly documented.

Good submissions are:

- Workflow-oriented
- Easy to customize
- Clear about inputs and outputs
- Tested or testable
- Not overly dependent on one AI tool unless clearly marked

Poor submissions include:

- Generic "act as an expert" prompts with no workflow
- Jailbreaks or prompt-injection tricks
- Meme prompts
- Overly long fragile prompts
- Duplicates of existing prompts
- Vague prompts without expected output

See [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`guides/prompt-quality-checklist.md`](guides/prompt-quality-checklist.md).

## Roadmap

### Phase 1: Foundation

- [x] Add README
- [x] Add MIT license
- [x] Add contribution guidelines
- [x] Add standard prompt template
- [x] Add starter prompt categories

### Phase 2: Quality System

- [x] Add prompt quality checklist
- [x] Add issue templates
- [x] Add pull request template
- [ ] Add more reviewed prompt examples

### Phase 3: Expansion

- [ ] Add more workflow categories when justified
- [ ] Add tool-specific prompts selectively
- [ ] Add before/after examples
- [ ] Add optional Chinese translations later

## License

This project is licensed under the [MIT License](LICENSE).
