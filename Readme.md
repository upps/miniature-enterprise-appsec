
# Miniature Enterprise AppSec

**An open-source, enterprise-inspired Application Security ecosystem.**

Miniature Enterprise AppSec aims to demonstrate how organisations design, implement, automate, and manage Application Security across the entire Software Development Life Cycle (SDLC).

The project brings together open-source security tools, DevSecOps practices, vulnerability management, secrets management, cloud security, security governance, and automation into a unified, reproducible environment.

Rather than demonstrating individual security scanners in isolation, this project focuses on building an integrated Application Security programme inspired by real-world enterprise security operations.

> **Project status:** Under active development. Capabilities will be implemented incrementally. See the roadmap for planned features.

---

## Objectives

- Demonstrate an end-to-end enterprise-inspired Application Security programme.
- Integrate security throughout the Software Development Life Cycle.
- Automate security testing and enforcement within CI/CD pipelines.
- Establish centralised vulnerability management and risk prioritisation.
- Demonstrate enterprise secrets and cryptographic key management.
- Secure applications, APIs, containers, infrastructure, and cloud environments.
- Implement security governance, exception management, and auditability.
- Improve developer security experience through automation and self-service.
- Provide reusable reference architectures, configurations, and documentation.

## Security Capabilities

The project is organised into the following security domains.

| Domain | Planned capabilities |
|---|---|
| Secure SDLC | Security requirements, threat modelling, architecture reviews, secure coding |
| SAST | Static application security testing and custom security rules |
| SCA | Dependency analysis, vulnerability detection, and dependency governance |
| DAST | Dynamic application security testing and API security testing |
| Secrets Security | Secret detection, centralised storage, rotation, and revocation |
| API Security | Authentication, authorisation, API vulnerability testing |
| IaC Security | Terraform, Kubernetes, and infrastructure misconfiguration scanning |
| Container Security | Image scanning, hardening, and runtime security |
| Cloud Security | IAM, cloud misconfiguration detection, and security posture |
| Supply Chain Security | SBOM, artifact signing, provenance, and dependency integrity |
| Vulnerability Management | Finding aggregation, prioritisation, remediation, and verification |
| ASPM | Application security posture visibility and risk management |
| Governance | Security policies, risk acceptance, exceptions, and audit trails |
| Security Operations | Incident response, vulnerability management, and security monitoring |
| Security Champions | Developer enablement, security training, and programme management |
| Automation | Ticket creation, notifications, reporting, and workflow automation |
| AI Security | AI application security, RAG security, and AI-powered security assistance |
| Metrics & Reporting | Security KPIs, KRIs, vulnerability trends, and management dashboards |

## Technology Stack

The project will prioritise open-source technologies.

| Security Area | Planned Tools |
|---|---|
| Application | Java, Spring Boot |
| CI/CD | GitHub Actions |
| SAST | Semgrep, CodeQL |
| SCA | Trivy, OWASP Dependency-Check |
| Secrets Detection | Gitleaks |
| Secrets Management | HashiCorp Vault / OpenBao |
| DAST | OWASP ZAP |
| API Security | OWASP ZAP, Burp Suite Community |
| IaC Security | Checkov |
| Container Security | Trivy |
| SBOM | CycloneDX, SPDX |
| SBOM Management | OWASP Dependency-Track |
| Vulnerability Management | OWASP DefectDojo |
| Artifact Signing | Cosign / Sigstore |
| Automation | n8n |
| Infrastructure | Docker, Terraform, Kubernetes |
| Cloud | AWS |
| Threat Modelling | OWASP Threat Dragon / STRIDE |

Tool selection may evolve as the project develops. Each integration will document its purpose, configuration, limitations, and licensing.

## Architecture

The intended architecture consists of three interconnected layers.

### 1. Application and Infrastructure Layer

A sample application and supporting infrastructure containing both intentionally vulnerable and secure implementations.

### 2. Security Testing and Enforcement Layer

Automated and manual security controls integrated throughout the development and deployment lifecycle.

### 3. Security Operations Layer

Centralised vulnerability management, secrets management, risk tracking, security governance, automation, and reporting.

The architecture and deployment documentation will evolve alongside implementation.

## Project Roadmap

The project will be developed incrementally through the following milestones.

- [ ] Repository foundation and architecture
- [ ] Sample application and secure SDLC
- [ ] GitHub Actions and CI/CD security
- [ ] SAST, SCA, and secrets detection
- [ ] DAST and API security
- [ ] IaC, container, and Kubernetes security
- [ ] Cloud security
- [ ] SBOM and software supply-chain security
- [ ] Secrets and cryptographic key management
- [ ] Vulnerability management and ASPM
- [ ] Security governance and risk management
- [ ] Security operations and incident response
- [ ] Security automation and developer experience
- [ ] AI-powered security assistant
- [ ] Security metrics and dashboards
- [ ] Documentation and community release

See the repository issues and project board for implementation progress.

## Getting Started

The project is currently under development.

Deployment instructions, prerequisites, configuration examples, and demonstrations will be added as individual components become available.

The intended deployment options are:

- **Quick Start:** A lightweight local environment for developers and security enthusiasts.
- **Enterprise Simulation:** A more comprehensive environment demonstrating integrated enterprise AppSec capabilities.

## Security Philosophy

This project follows several core principles:

- Security by design.
- Shift-left and continuous security.
- Risk-based vulnerability prioritisation.
- Least privilege and zero-trust principles.
- Defence in depth.
- Developer-friendly security controls.
- Continuous monitoring and improvement.
- Security automation and measurable outcomes.

## Contributing

Contributions, suggestions, feature requests, and improvements are welcome.

Please refer to `CONTRIBUTING.md` for contribution guidelines once available.

Whether you are an application security engineer, security researcher, developer, or DevSecOps practitioner, you are welcome to contribute.

## Disclaimer

This project is intended for educational purposes, security research, and as a reference implementation of enterprise-inspired Application Security practices.

Intentionally vulnerable applications and infrastructure configurations are provided strictly for controlled testing environments.

Do not expose vulnerable components to public networks or deploy demonstration configurations in production environments.

The project does not claim to provide a complete production-ready enterprise security platform.

## Licence

Distributed under the Apache License 2.0.

See the `LICENSE` file for details.
