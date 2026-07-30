# SailPoint Identity Security Cloud (ISC) Lab

A structured, version-controlled workspace for learning, experimenting with, and managing configurations in **SailPoint Identity Security Cloud (ISC)**.

> **Purpose:** Build hands-on expertise in Identity Governance and Administration (IGA) by working with a dedicated SailPoint ISC Sandbox tenant using modern development tools and best practices.

---

## Objectives

- Learn SailPoint ISC from the ground up
- Practice real-world Identity Governance concepts
- Develop and test transforms, workflows, provisioning policies, and identity profiles
- Manage configurations using Visual Studio Code
- Explore SailPoint REST APIs
- Maintain configuration history using Git

---

## Environment

| Item | Value |
|------|-------|
| Platform | SailPoint Identity Security Cloud (ISC) |
| Environment | Sandbox |
| IDE | Visual Studio Code |
| Version Control | Git |
| API Tool | Postman |
| Operating System | Windows 11 + WSL2 (Ubuntu) |

---

## Repository Structure

```text
SailPoint-ISC/
│
├── .vscode/
├── api/
├── tenants/
├── sources/
├── schemas/
├── identity-profiles/
├── identity-attributes/
├── transforms/
├── lifecycle-states/
├── provisioning/
├── access-profiles/
├── roles/
├── entitlements/
├── workflows/
├── events/
├── rules/
├── governance-groups/
├── password-policies/
├── certifications/
├── campaigns/
├── search/
├── reports/
├── applications/
├── scripts/
├── sample-data/
├── exports/
├── imports/
├── backups/
├── documentation/
├── assets/
│
├── README.md
├── LICENSE
├── CHANGELOG.md
└── .gitignore
````

---

## Tools

* SailPoint Identity Security Cloud
* Visual Studio Code
* SailPoint VS Code Extension
* Git
* Postman
* PowerShell
* Bash (WSL)

---

## Learning Roadmap

### Foundation

* Identity Governance concepts
* SailPoint ISC architecture
* Identity lifecycle
* Authentication and authorization
* Roles and entitlements

### Core Administration

* Sources
* Schemas
* Aggregations
* Correlation
* Identity Profiles
* Identity Attributes

### Configuration

* Transforms
* Lifecycle States
* Provisioning Policies
* Access Profiles
* Roles
* Password Policies

### Automation

* Workflows
* Event Triggers
* Provisioning
* REST APIs

### Integrations

* Active Directory
* Microsoft Entra ID
* ServiceNow
* JDBC
* Web Services
* Delimited File
* Workday

### Advanced Topics

* Governance Groups
* Access Certifications
* Search
* Reporting
* Identity Security Best Practices

---

## Workflow

1. Create or modify objects in the Sandbox tenant.
2. Export configurations when needed.
3. Organize exported artifacts into the appropriate folders.
4. Commit meaningful changes to Git.
5. Document important findings and implementation notes.

---

## Repository Guidelines

* Keep exported configurations organized by object type.
* Use descriptive filenames.
* Document significant changes in `CHANGELOG.md`.
* Avoid committing secrets, credentials, or access tokens.
* Test changes in the Sandbox before reusing them elsewhere.

---

## Notes

This repository is intended for learning and experimentation using a SailPoint ISC Sandbox tenant. It serves as a centralized workspace for configurations, exported objects, automation scripts, API resources, and supporting documentation.

---

## License

This repository is for personal learning and educational purposes.