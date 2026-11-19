
# Engineering Prompts

<p align="center">
  <img src="https://img.shields.io/badge/Engineering-Prompts-blue?style=for-the-badge" alt="Engineering Prompts">
  <img src="https://img.shields.io/badge/DevOps-DevSecOps-orange?style=for-the-badge" alt="DevOps and DevSecOps">
  <img src="https://img.shields.io/badge/MLOps-Machine%20Learning-purple?style=for-the-badge" alt="MLOps">
</p>

<p align="center">
  <a href="https://github.com/Angloma-federico/engineering-prompts">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?logo=github" alt="GitHub Repository">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg" alt="CC BY 4.0 License">
  </a>
  <a href="CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg" alt="Contributions Welcome">
  </a>
</p>

<p align="center">
  <a href="https://creativecommons.org/licenses/by/4.0/">
    <img src="https://licensebuttons.net/l/by/4.0/88x31.png" alt="Creative Commons Attribution 4.0 International">
  </a>
</p>

<p align="center">
  <strong>Documentation:</strong>
  <a href="README.md">🇺🇸 🇬🇧 English</a> |
  <a href="FR_README.md">🇫🇷 French</a>
</p>

A structured collection of reusable AI prompts for software engineering, system administration, DevOps, DevSecOps, and MLOps.

The goal of this repository is to improve the quality, consistency, security, and maintainability of AI-assisted engineering work.

---

## Objectives

This repository provides reusable prompts designed to help engineers:

- Understand technical problems before implementing solutions.
- Design maintainable and reliable architectures.
- Write clean, readable, and secure code.
- Automate infrastructure and software delivery.
- Integrate security into development and operations.
- Build, deploy, and monitor machine learning systems.
- Produce clear technical documentation.
- Improve troubleshooting and problem-solving skills.

The prompts are designed to support learning, practical engineering, and professional workflows.

## Repository Structure

```text
engineering-prompts/
├── LICENSE
├── README.md
├── FR_README.md
├── CONTRIBUTING.md
│
├── shared/
│   ├── engineering-standards.md
│   └── project-context-template.md
│
├── general/
│   ├── code-review.md
│   ├── clean-code.md
│   ├── debugging.md
│   ├── documentation.md
│   └── commit-message.md
│
├── devops/
│   ├── docker.md
│   ├── kubernetes.md
│   ├── terraform.md
│   └── cicd.md
│
├── devsecops/
│   ├── security-audit.md
│   └── vulnerability-analysis.md
│
└── mlops/
    ├── model-training.md
    ├── model-deployment.md
    └── model-monitoring.md
```

## Categories

| Category | Purpose |
|---|---|
| `shared/` | Common engineering standards and project context |
| `general/` | Code quality, debugging, documentation, and reviews |
| `devops/` | Containers, Kubernetes, infrastructure as code, and CI/CD |
| `devsecops/` | Defensive security audits and vulnerability analysis |
| `mlops/` | Model training, deployment, and monitoring |

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Angloma-federico/engineering-prompts.git
cd engineering-prompts
```

### 2. Choose a prompt

Navigate to the category corresponding to your task.

For example:

```text
devops/docker.md
```

### 3. Provide your project context

For better results, use:

```text
shared/project-context-template.md
```

Provide relevant information such as:

- Project objectives
- Technology stack
- Architecture
- Repository structure
- Current implementation
- Constraints and requirements
- Expected outcome

Do not invent missing technical details. Leave unknown information unspecified.

### 4. Apply the prompt

Copy the selected prompt into your AI assistant and provide the necessary project context.

Adapt the instructions to your actual environment and requirements.

### 5. Validate the results

AI-generated suggestions must be reviewed and validated before being applied.

Check:

- Technical correctness
- Security implications
- Compatibility with your environment
- Tests and validation results
- Documentation accuracy

## Engineering Principles

The prompts follow a shared set of engineering principles:

- **Understand before implementing:** analyze the context and problem first.
- **Keep it simple:** avoid unnecessary complexity and dependencies.
- **Clean code:** prioritize readability, maintainability, and consistency.
- **Security by design:** consider security throughout the engineering lifecycle.
- **Reliability:** validate configurations, implementations, and expected behavior.
- **Evidence-based troubleshooting:** distinguish confirmed facts from assumptions.
- **Documentation:** explain important decisions, changes, and limitations.
- **Continuous improvement:** prefer practical and maintainable solutions.

For common requirements, refer to [`shared/engineering-standards.md`](shared/engineering-standards.md).

## Documentation

The repository provides English and French documentation:

- [English README](README.md)
- [French README](FR_README.md)

Individual prompts may also define documentation expectations for the projects in which they are used.

## Contributing

Contributions, corrections, and improvements are welcome.

Before submitting changes, read [`CONTRIBUTING.md`](CONTRIBUTING.md).

Please focus on practical, reusable, technically accurate, and well-structured prompts.

## License

<p align="center">
  <a href="https://creativecommons.org/licenses/by/4.0/">
    <img src="https://licensebuttons.net/l/by/4.0/88x31.png" alt="CC BY 4.0">
  </a>
</p>

Unless otherwise stated, the original prompts, templates, and documentation in this repository are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to share, adapt, and use this material, including for commercial purposes, provided that you:

- Give appropriate credit to the original author.
- Provide a link to the license.
- Indicate whether changes were made.

See:

- [LICENSE](LICENSE)
- [CC BY 4.0 Legal Code](https://creativecommons.org/licenses/by/4.0/legalcode)

**Original author:** [Angloma-federico](https://github.com/Angloma-federico)

---

<p align="center">
  Maintained by <a href="https://github.com/Angloma-federico">Angloma-federico</a>
</p>
