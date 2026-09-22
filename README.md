# Kennel - Issue Tracker & Feedback

> [!NOTE]
> This repository serves strictly as the **public issue tracker and feature request forum** for **Kennel**. This repository does not contain the application source code.

---

## About Kennel

**Kennel** is an analytics platform designed to help software engineers discover and resolve security, dependency, and lifecycle issues in software containers. 

It inspects sofware container images (OCI), automatically selects optimal SBOM generators based on target directories, cross-references findings against public vulnerability databases (OSV), and synthesizes complex security data into an intuitive dashboard.

### Core Features

- **Container Image Analysis**: Inspects Docker software container images to extract deep dependency trees and software metadata.
- **Smart SBOM Generation**: Evaluates container directories to select and run best-of-breed SBOM generators tailored to the detected tech stack.
- **OSV Vulnerability Matching**: Cross-references generated SBOM components against the Open Source Vulnerability (OSV) database to flag known security flaws.
- **End of Life (EOL) Reporting**: Optionally identifies outdated or unsupported components and generates lifecycle status reports.
- **Intuitive Analytics Dashboard**: Boils down raw SBOM, vulnerability, and EOL metrics into a clean, actionable view for engineers.

---

## 🐛 Submitting Issues & Feature Requests

We use this repository to track bugs, performance improvements, and user requests.

### Before Opening an Issue
1. **Search existing issues**: Check the [Issues](../../issues) tab to see if your bug or request has already been logged.
2. **Provide context**: When reporting a bug, please include:
   - Reproduction steps
   - Target container image name/tag (if applicable)
   - Expected vs. actual behavior
   - Screenshots or relevant logs

---

## 🔒 Source Code Access

The core **Kennel** codebase is maintained in a private repository. 

If you require access to the source code for development, security auditing, or contribution purposes:

1. **Request an Invitation**: Send an email to **[kennel@blueshoe.io](mailto:kennel@blueshoe.io)**.
2. **Provide Details**: State your GitHub username, organization, and the purpose of your request.
3. **Invitation**: Once approved, an official invitation to the private codebase repository will be dispatched to your GitHub account.

---

## License

This repository and its issue tracking content are public. The core Kennel codebase is subject to its own repository license terms.
