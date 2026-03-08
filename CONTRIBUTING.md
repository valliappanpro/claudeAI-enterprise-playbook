# Contributing to Claude AI Enterprise Playbook

Thank you for your interest in contributing! This playbook thrives on real-world experience from AI practitioners, consultants, and implementation teams. Whether you're fixing a typo or sharing a battle-tested enterprise pattern, your contribution is valued.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Ways to Contribute](#ways-to-contribute)
- [Contribution Workflow](#contribution-workflow)
- [Content Guidelines](#content-guidelines)
- [File & Folder Structure](#file--folder-structure)
- [Style Guide](#style-guide)
- [Licensing](#licensing)
- [Code of Conduct](#code-of-conduct)
- [Questions](#questions)

---

## Getting Started

1. **Fork** this repository
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/claudeAI-enterprise-playbook.git
   cd claudeAI-enterprise-playbook
   ```
3. **Create a branch** for your contribution:
   ```bash
   git checkout -b feature/your-contribution-name
   ```
4. Make your changes, commit, and push to your fork
5. Open a **Pull Request** against `main`

---

## Ways to Contribute

### Share Enterprise Patterns
Have a Claude AI pattern that works well in production? We'd love to include it. Patterns from any industry are welcome, though healthcare payer operations and consulting workflows are areas of particular focus.

### Improve Documentation
Clarify existing content, fix errors, add missing context, or improve readability. Even small fixes make a difference.

### Add Templates or Examples
Contribute reusable templates for prompts, document automation, dashboards, or integration patterns. Place them in the appropriate `templates/` or `examples/` subfolder.

### Report Issues or Suggest Topics
Open a [GitHub Issue](../../issues) to:
- Report inaccuracies or outdated information
- Suggest new topics or patterns
- Propose structural improvements
- Request coverage of specific use cases

---

## Contribution Workflow

1. **Check existing issues** to see if your idea or fix is already being discussed
2. **Open an issue first** for significant additions (new sections, major rewrites) so we can align before you invest time
3. **Keep PRs focused** — one topic or fix per pull request
4. **Write a clear PR description** explaining what changed and why
5. **Reference related issues** in your PR description (e.g., `Closes #12`)

### Pull Request Checklist

- [ ] Content is placed in the correct directory
- [ ] Markdown renders correctly (preview before submitting)
- [ ] Links are valid and relative where possible
- [ ] No proprietary, confidential, or client-specific information is included
- [ ] Sensitive data (PHI, PII, credentials) has been removed or anonymized
- [ ] Contribution follows the [Style Guide](#style-guide) below

---

## Content Guidelines

### What We're Looking For

- **Production-tested patterns** — not theoretical ideas but approaches that have worked in real deployments
- **Generalized content** — strip out client names, proprietary details, and anything confidential before contributing
- **Actionable guidance** — readers should be able to apply your contribution directly
- **Measurable outcomes** — where possible, include metrics or indicators of success

### What to Avoid

- Client-specific or proprietary information
- Protected Health Information (PHI) or Personally Identifiable Information (PII)
- Speculative or untested approaches presented as best practices
- Marketing language or product promotion
- Content that duplicates existing sections without adding value

---

## File & Folder Structure

Place your contributions in the appropriate section:

| Section | Content Type |
|---------|-------------|
| `01-prompt-engineering/` | Prompt design patterns, system prompts, few-shot templates |
| `02-claude-projects/` | Claude Projects architecture and use cases |
| `03-document-automation/` | PPTX, DOCX, PDF, XLSX generation patterns |
| `04-ai-adoption-measurement/` | Surveys, analytics, ROI models, dashboards |
| `05-enterprise-integration/` | Jira, Confluence, Smartsheet, AWS Bedrock patterns |
| `06-healthcare-ai-patterns/` | Healthcare payer domain patterns and compliance |
| `07-resources/` | Tools, reading lists, glossary entries |

- Add **examples** to the `examples/` subfolder within the relevant section
- Add **templates** to the `templates/` subfolder within the relevant section
- Each new file should be referenced in the parent directory's `README.md`

---

## Style Guide

### Markdown Formatting

- Use **ATX-style headers** (`#`, `##`, `###`)
- Use `---` for horizontal rules between major sections
- Use fenced code blocks with language identifiers (` ```python `, ` ```javascript `, ` ```bash `)
- Use tables for structured comparisons
- Keep line lengths reasonable for readability

### Writing Style

- Write in a **clear, professional tone** suitable for enterprise audiences
- Use **active voice** and direct language
- Define acronyms on first use (e.g., "Health Level Seven (HL7)")
- Use **bold** for key terms and emphasis, *italics* sparingly
- Structure content with headers, bullet points, and tables for scannability

### Naming Conventions

- File names: `lowercase-with-hyphens.md`
- Folder names: `lowercase-with-hyphens/`
- Use descriptive, concise names (e.g., `roi-calculation-models.md`, not `models.md`)

### Code Examples

- Include comments explaining non-obvious logic
- Use realistic but anonymized sample data
- Specify language and any dependency requirements
- Keep examples self-contained where possible

---

## Licensing

By contributing to this repository, you agree that your contributions will be licensed under:

- **Code samples:** [MIT License](LICENSE)
- **Written content & frameworks:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

You confirm that you have the right to submit the contribution and that it does not contain proprietary or confidential material.

---

## Code of Conduct

We are committed to providing a welcoming and inclusive experience for everyone. Contributors are expected to:

- Be respectful and constructive in discussions
- Welcome diverse perspectives and experience levels
- Focus feedback on the content, not the contributor
- Accept constructive criticism gracefully
- Prioritize what is best for the community and the playbook

Unacceptable behavior includes harassment, trolling, personal attacks, or publishing others' private information. Violations may result in removal of contributions and being blocked from future participation.

---

## Questions

If you have questions about contributing or want to discuss an idea before submitting:

- **Open a GitHub Issue** for public discussion
- **Email:** valliappanpro@gmail.com
- **LinkedIn:** [linkedin.com/in/valliappan617](https://www.linkedin.com/in/valliappan617/)
- **GitHub:** [github.com/valliappanpro](https://github.com/valliappanpro)

---

*Thank you for helping make the Claude AI Enterprise Playbook a better resource for the community!*
