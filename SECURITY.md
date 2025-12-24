# Security Policy

## Scope

This repository provides an **experimental research framework** for evaluating
federated learning aggregation strategies. It is **not intended for production
deployment**.

Nevertheless, security and responsible disclosure are taken seriously.

---

## Supported Versions

Only the **latest version of the main branch** is supported for security-related
fixes.

---

## Reporting a Vulnerability

Please **do not open public issues** for potential security vulnerabilities.

Instead:

- Use GitHub Security Advisories (preferred), or
- Contact the repository maintainer privately

When reporting, include:

- Description of the issue
- Potential impact
- Reproduction steps (if applicable)
- Suggested mitigation (optional)

---

## Security Considerations in Scope

- Data leakage between clients
- Incorrect aggregation logic leading to privacy exposure
- Insecure handling of model parameters or metrics
- Dataset misuse or unintended data persistence

---

## Out of Scope

- Production-grade threat models
- Attacks requiring physical access
- Misconfiguration in user-modified deployments
- Third-party library vulnerabilities (unless exploitable here)

---

## Responsible Disclosure

We ask reporters to:

- Avoid public disclosure before remediation
- Act in good faith
- Limit exploitation to proof-of-concept only

---

## Disclaimer

This framework is intended **solely for research and educational purposes**.
It has not undergone formal security audits and should not be deployed in
real-world production environments without additional safeguards.

---

Thank you for helping maintain responsible and secure research software.
