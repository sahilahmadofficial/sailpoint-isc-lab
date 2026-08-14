# SailPoint Identity Security Cloud (ISC) Lab

A structured, version-controlled workspace for learning, experimenting with, and managing configurations in SailPoint Identity Security Cloud (ISC).

**Purpose:** Build hands-on expertise in Identity Governance and Administration (IGA) by working with a dedicated SailPoint ISC Sandbox tenant using modern development tools and best practices.

---

## Objectives

- Learn SailPoint ISC from the ground up
- Practice real-world Identity Governance concepts
- Develop and test transforms, workflows, provisioning policies, and identity profiles
- Manage configurations using Visual Studio Code
- Explore SailPoint REST APIs
- Maintain configuration history using Git
- Build a public portfolio of IAM/IGA work

---

## Environment

| Item | Value |
|---|---|
| Platform | SailPoint Identity Security Cloud (ISC) |
| Environment | Sandbox |
| IDE | Visual Studio Code |
| Version Control | Git |
| API Tool | Postman |
| Operating System | Windows 11 + WSL2 (Ubuntu) |

---

## Repository Structure

```
sailpoint-isc-lab/
│
├── core/ # Core ISC configurations
│ ├── sources/
│ ├── schemas/
│ ├── identity-profiles/
│ ├── identity-attributes/
│ ├── transforms/
│ ├── lifecycle-states/
│ └── provisioning/
│
├── governance/ # Access governance
│ ├── access-profiles/
│ ├── roles/
│ ├── entitlements/
│ ├── certifications/
│ ├── campaigns/
│ └── governance-groups/
│
├── automation/ # Automation and rules
│ ├── workflows/
│ ├── events/
│ ├── rules/
│ ├── password-policies/
│ └── scripts/
│
├── integrations/ # Integrations
│ ├── connectors/
│ ├── applications/
│ ├── sources/
│ └── schemas/
│
├── api/ # API resources
│ └── postman-collections/
│
├── data/ # Sample data and exports
│ ├── sample-data/
│ ├── exports/
│ ├── imports/
│ └── backups/
│
├── docs/ # Documentation
│ ├── learning-notes/
│ ├── troubleshooting/
│ └── reports/
│
├── assets/ # Visual assets
│ ├── diagrams/
│ └── images/
│
├── .vscode/ # VS Code workspace settings
├── .gitignore
├── CHANGELOG.md
├── LICENSE
└── README.md

```

---

## Tools

- SailPoint Identity Security Cloud
- Visual Studio Code
- SailPoint VS Code Extension
- Git
- Postman
- PowerShell
- Bash (WSL)

---

## Learning Roadmap

### Foundation
- Identity Governance concepts
- SailPoint ISC architecture
- Identity lifecycle
- Authentication and authorization
- Roles and entitlements

### Core Administration
- Sources
- Schemas
- Aggregations
- Correlation
- Identity Profiles
- Identity Attributes

### Configuration
- Transforms
- Lifecycle States
- Provisioning Policies
- Access Profiles
- Roles
- Password Policies

### Automation
- Workflows
- Event Triggers
- Provisioning
- REST APIs

### Integrations
- Active Directory
- Microsoft Entra ID
- ServiceNow
- JDBC
- Web Services
- Delimited File
- Workday

### Advanced Topics
- Governance Groups
- Access Certifications
- Search
- Reporting
- Identity Security Best Practices

---

## Workflow

1. Create or modify objects in the ISC Sandbox tenant.
2. Export configurations using the SailPoint VS Code extension or API.
3. Organize exported artifacts into the appropriate folders.
4. Review changes before committing (use `git diff` and `git status`).
5. Commit with a descriptive message (e.g., `feat: add manager approval workflow`).
6. Push to GitHub and document key findings in `CHANGELOG.md`.

---

## Repository Guidelines

- Organize exported configurations by object type in the corresponding folder.
- Use descriptive filenames (e.g., `manager-approval-workflow.json`, not `workflow-1.json`).
- Document significant changes in `CHANGELOG.md` with date, change type, and brief description.
- Never commit secrets, credentials, or access tokens. Use environment variables or `.env` files.
- Test all changes in the Sandbox tenant before committing.
- Commit with meaningful messages following conventional commit format:
  - `feat:` for new configurations
  - `fix:` for bug fixes or corrections
  - `docs:` for documentation updates
  - `refactor:` for restructuring

---

## Notes

This repository is intended for learning and experimentation using a SailPoint ISC Sandbox tenant. It serves as a centralized workspace for configurations, exported objects, automation scripts, API resources, and supporting documentation.

All work is performed in a Sandbox environment to ensure a safe, isolated space for learning.

---

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Connect

- **LinkedIn:** [linkedin.com/in/sahilahmadofficial](https://linkedin.com/in/sahilahmadofficial)
- **GitHub:** [github.com/sahilahmadofficial](https://github.com/sahilahmadofficial)
- **Blog:** [sahilahmad.is-a.dev](https://sahilahmad.is-a.dev)
- **Email:** hello.sahilahmad@gmail.com