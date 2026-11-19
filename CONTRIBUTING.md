# Contributing to Engineering Prompts

Thank you for your interest in contributing to **Engineering Prompts**.

Contributions are welcome. Whether you are correcting an issue, improving an existing prompt, or adding a new one, your contribution can help make this collection more useful and reliable for the engineering community.

## Contribution Guidelines

Please follow these principles:

- Keep prompts practical, reusable, and technically accurate.
- Prefer clear instructions over unnecessarily complex rules.
- Avoid duplicated instructions and unnecessary content.
- Explain the reasoning behind important technical recommendations.
- Consider security, reliability, maintainability, and testing.
- Never include credentials, API keys, passwords, private information, or confidential project data.
- Do not submit copyrighted material unless you have the necessary rights or permission.

## What Can You Contribute?

You can contribute in several ways:

| Contribution | Examples |
|---|---|
| New prompts | Add prompts for Ansible, AWS, monitoring, or security |
| Improvements | Make existing instructions clearer or more effective |
| Corrections | Fix technical inaccuracies or outdated recommendations |
| Documentation | Improve README files and usage examples |
| Organization | Improve the repository structure and consistency |
| Testing | Validate prompts against realistic engineering scenarios |

## Repository Organization

Place your contribution in the appropriate directory:

```text
shared/       Common engineering standards and templates
general/      General software engineering
devops/       Infrastructure and automation
devsecops/    Defensive security engineering
mlops/        Machine learning operations
```

If you are unsure where a new prompt belongs, explain your proposal in the pull request.

## Prompt Quality Standards

Every new or significantly modified prompt should:

1. Define a clear role and objective.
2. Explain the expected technical context.
3. Identify relevant constraints and requirements.
4. Ask for analysis before implementation when appropriate.
5. Prioritize secure, maintainable, and practical solutions.
6. Avoid unnecessary dependencies and complexity.
7. Include validation and testing expectations.
8. Distinguish confirmed information from assumptions.
9. Avoid inventing commands, configurations, outputs, or test results.
10. Provide useful documentation expectations.

Prompts should encourage understanding and independent problem-solving, not just generate unexplained solutions.

## File Naming and Formatting

Use descriptive lowercase filenames with hyphens.

Examples:

```text
docker-security.md
aws-infrastructure.md
kubernetes-monitoring.md
```

Use Markdown consistently:

- Clear headings.
- Short and meaningful sections.
- Code blocks for commands and configurations.
- Tables when they improve readability.
- No unnecessary decorative formatting.

## Commit Messages

Use the following format:

```text
type: imperative verb + object
```

Accepted types:

| Type | Purpose |
|---|---|
| `feat` | Add a new prompt or feature |
| `fix` | Correct an issue |
| `docs` | Update documentation |
| `refactor` | Improve structure without changing intended behavior |
| `test` | Add or update validation |
| `chore` | Maintenance and repository configuration |

Examples:

```bash
git commit -m "feat: add ansible automation prompt"
git commit -m "fix: clarify docker security requirements"
git commit -m "docs: improve contribution guidelines"
```

Keep commit messages concise, use the imperative form, and avoid unnecessary punctuation.

## Pull Request Process

1. Fork the repository.
2. Create a dedicated branch.
3. Make your changes.
4. Review your modifications.
5. Validate Markdown formatting and internal links.
6. Commit your changes using the project's commit convention.
7. Push your branch to your fork.
8. Open a pull request against the original repository.

A pull request should explain:

- What changed?
- Why was the change necessary?
- Which files were modified?
- How was the contribution validated?
- Are there any limitations or known issues?

Keep pull requests focused on one logical change whenever possible.

## License and Attribution

Unless otherwise stated, the original prompts, templates, and documentation in this repository are distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

By submitting a contribution, you confirm that:

- You have the right to submit the contributed material.
- Your contribution does not knowingly infringe another party's intellectual property rights.
- You agree that your submitted original prompts, templates, and documentation may be distributed under CC BY 4.0.

You retain the copyright in your original contribution. You grant users the permissions provided by the CC BY 4.0 license.

Please identify third-party material and its applicable license where relevant.

Read the [LICENSE](LICENSE) file and the [CC BY 4.0 legal code](https://creativecommons.org/licenses/by/4.0/legalcode).

## Code of Conduct

Be respectful, constructive, and professional.

- Respect different experience levels and perspectives.
- Focus feedback on the work, not the individual.
- Explain technical disagreements with evidence.
- Keep discussions relevant and collaborative.

## Questions and Discussions

For questions, suggestions, or issues, use the repository's GitHub Issues.

Thank you for helping improve Engineering Prompts.

---

Maintained by [Angloma-federico](https://github.com/Angloma-federico)

