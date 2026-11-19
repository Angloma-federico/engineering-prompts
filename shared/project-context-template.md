# Project Context — Reusable Template

> Purpose: Provide the AI assistant with reliable project information before analysis, implementation, debugging, review, or documentation.
>
> Instructions: Complete the fields relevant to the task. Unknown or unavailable information can remain marked as `Not specified`. Do not invent project details.

---

## 1. Project Identity

| Field | Information |
|---|---|
| Project name | `[Project name]` |
| Repository | `[GitHub / GitLab URL or local path]` |
| Project type | `[Software / DevOps / DevSecOps / MLOps / Infrastructure / Other]` |
| Project status | `[Planning / Development / Testing / Staging / Production]` |
| Main objective | `[What the project aims to achieve]` |
| Problem addressed | `[Problem being solved]` |
| Target users | `[Who will use the solution]` |
| Project owner or team | `[Optional]` |

## 2. Project Description

### Overview

[Describe the project and its purpose.]

### Expected outcomes

- `[Expected outcome 1]`
- `[Expected outcome 2]`
- `[Expected outcome 3]`

### Scope

**In scope:**
- `[Included functionality or work]`

**Out of scope:**
- `[Excluded functionality or work]`

## 3. Technical Environment

### Operating environment

| Component | Details |
|---|---|
| Operating system | `[Distribution and version]` |
| Architecture | `[x86_64 / ARM64 / Other]` |
| Runtime | `[Python / Node.js / Go / Java / Other]` |
| Runtime version | `[Version]` |
| Development environment | `[Local / VM / Cloud / Container]` |

### Technologies and tools

| Category | Technology | Version or status |
|---|---|---|
| Programming language | `[Technology]` | `[Version]` |
| Framework | `[Technology]` | `[Version]` |
| Database | `[Technology]` | `[Version]` |
| Containerization | `[Docker / Podman / Other]` | `[Version]` |
| CI/CD | `[GitLab CI / GitHub Actions / Jenkins / Other]` | `[Version or status]` |
| Cloud provider | `[AWS / GCP / Azure / Other]` | `[Service or status]` |
| Orchestration | `[Kubernetes / Other]` | `[Version or status]` |
| Monitoring | `[Prometheus / Grafana / Other]` | `[Version or status]` |
| Security tools | `[Trivy / Semgrep / Other]` | `[Version or status]` |

Only include technologies relevant to the project.

## 4. Architecture and Components

### Architecture overview

[Describe the current architecture or reference an architecture document.]

### Main components

| Component | Responsibility | Current status |
|---|---|---|
| `[Component 1]` | `[Purpose]` | `[Working / In progress / Planned]` |
| `[Component 2]` | `[Purpose]` | `[Working / In progress / Planned]` |
| `[Component 3]` | `[Purpose]` | `[Working / In progress / Planned]` |

### Communication and dependencies

[Explain how the components communicate, including relevant APIs, ports, protocols, networks, and external dependencies.]

### Architecture constraints

- `[Resource constraints]`
- `[Network constraints]`
- `[Infrastructure constraints]`
- `[Compatibility requirements]`

## 5. Repository Structure

```text
project/
├── src/
├── tests/
├── config/
├── scripts/
├── docs/
├── README.md
└── FR_README.md
```

Replace this example with the actual repository structure.

### Important files

| File or directory | Purpose |
|---|---|
| `[Path]` | `[Description]` |
| `[Path]` | `[Description]` |

Do not assume that example paths exist in the actual project.

## 6. Current Implementation Status

### Completed

- `[Implemented functionality]`
- `[Validated functionality]`

### In progress

- `[Current work]`

### Not started

- `[Planned work]`

### Known issues

| Issue | Impact | Current status |
|---|---|---|
| `[Issue]` | `[Impact]` | `[Open / Investigating / Resolved]` |

Clearly distinguish implemented functionality from functionality that has actually been tested and verified.

## 7. Development and Execution

### Installation

[Provide actual installation prerequisites and commands.]

### Configuration

[Describe configuration files and required environment variables. Never include real credentials.]

### Execution

```bash
# Replace with actual project commands
[execution command]
```

### Testing

```bash
# Replace with actual project validation commands
[test command]
```

### Build and deployment

[Describe the existing build and deployment process, if applicable.]

Do not invent commands. Inspect the project or ask for missing information before recommending project-specific commands.

## 8. Data and Storage

Complete this section when the project uses data, databases, persistent storage, or ML artifacts.

| Field | Information |
|---|---|
| Data source | `[Source]` |
| Data format | `[CSV / JSON / SQL / Parquet / Other]` |
| Database | `[Technology or Not applicable]` |
| Storage | `[Local / Object storage / Persistent volume / Other]` |
| Data sensitivity | `[Public / Internal / Confidential / Unknown]` |
| Backup strategy | `[Description or Not specified]` |

### Data constraints

- `[Data quality requirements]`
- `[Retention requirements]`
- `[Access restrictions]`
- `[Privacy constraints]`

Never paste passwords, access tokens, private keys, or sensitive personal data into this document.

## 9. Security and Compliance

### Security requirements

- Authentication: `[Requirements]`
- Authorization: `[Requirements]`
- Secrets management: `[Requirements]`
- Network exposure: `[Requirements]`
- Encryption: `[Requirements]`
- Access control: `[Requirements]`

### Security scope

[For security assessments, define authorized assets, environments, methods, limitations, and excluded activities.]

### Applicable standards

[OWASP / CIS / NIST / ISO 27001 / Other, if applicable.]

Do not assume that a standard or compliance requirement applies unless the project establishes it.

## 10. Constraints and Decisions

### Technical constraints

- `[Required technologies]`
- `[Compatibility limitations]`
- `[Infrastructure limitations]`

### Budget and resources

- Budget: `[Known budget or Not specified]`
- CPU / RAM / Storage: `[Available resources]`
- Cloud or hosting limitations: `[Details]`

### Decisions already made

| Decision | Reason | Date or reference |
|---|---|---|
| `[Decision]` | `[Reason]` | `[Reference]` |

Do not reverse established project decisions without explaining the technical reason and consequences.

## 11. Current Task

Complete this section for each new request.

**Task title:**
`[What needs to be done]`

**Objective:**
`[Expected result]`

**Current problem:**
`[Describe the issue or requirement]`

**Relevant files:**
- `[File or directory]`

**Expected deliverables:**
- `[Code / Configuration / Documentation / Analysis / Tests / Other]`

**Acceptance criteria:**
- `[How success will be evaluated]`

**Constraints for this task:**
- `[Things that must not change or limitations to respect]`

## 12. Working Preferences

Apply the following preferences unless the task specifies otherwise:

- Explain important technical decisions progressively.
- Explain both why and how.
- Prefer practical implementation over unnecessary theory.
- Use clean, maintainable, and secure code.
- Avoid unnecessary dependencies and abstractions.
- Explain where new files belong.
- Provide commands with their purpose and expected result.
- Preserve working project components.
- Do not invent project information or execution results.
- Use English for project code, comments, commits, and `README.md` by default.
- Maintain `FR_README.md` in French.
- Use French for explanations when requested.
- Follow `shared/engineering-standards.md`.

## 13. Expected AI Behavior

Before starting the task:

1. Read and understand this project context.
2. Inspect the relevant existing files when available.
3. Identify missing information that could affect correctness.
4. Summarize the current situation.
5. Explain the proposed approach.
6. Identify risks and important assumptions.

During implementation:

1. Work in small logical steps.
2. Explain the purpose of each important change.
3. Identify the exact files to create or modify.
4. Provide implementation details and commands.
5. Validate each logical step where execution is possible.

At the end:

1. Summarize what was implemented.
2. Distinguish implementation from verified results.
3. List tests and their actual outcomes.
4. Identify unresolved issues.
5. Mention documentation updates.
6. Recommend only the most relevant next step.

## Final Instruction

Use this document as the project's source of context, not as permission to assume that every listed component or feature already exists.

If information is missing, identify it clearly. If the repository contradicts this document, report the discrepancy and ask for clarification when it affects the task.

The objective is to work with the actual project, its constraints, and its current state.