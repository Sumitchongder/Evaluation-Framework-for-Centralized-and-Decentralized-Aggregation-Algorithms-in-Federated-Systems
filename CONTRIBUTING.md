# Contributing to the Federated Learning Evaluation Framework

Thank you for your interest in contributing to this research framework.
This repository accompanies a peer-reviewed arXiv paper and prioritizes
**reproducibility, correctness, and scientific rigor**.

---

## Types of Contributions

We welcome contributions including:

- Bug fixes and performance improvements
- Additional evaluation metrics
- Extensions to new datasets or models
- Improvements to documentation or visualizations
- Reproducibility enhancements
- Experimental baselines or ablation studies

---

## Contribution Principles

### Reproducibility (Mandatory)

All contributions must:

- Preserve deterministic behavior where applicable
- Clearly document hyperparameters and assumptions
- Avoid breaking published experimental results
- Include seeds, configurations, or scripts as needed

---

### Code Standards

- Follow **PEP 8** for Python
- Use modular, readable, and well-documented code
- Add docstrings to public functions
- Avoid hard-coded values (use configuration files or parameters)

---

## Experimental Contributions

If contributing experiments:

- Clearly describe the experimental setup
- Specify datasets, splits, and assumptions
- Ensure results are reproducible
- Add plots under `docs/results/` with captions
- Clearly label exploratory or non-paper results

---

## Workflow

1. Fork the repository
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
````

3. Make small, well-documented commits
4. Test your changes
5. Push to your fork
6. Open a Pull Request (PR)

---

## Pull Request Requirements

Each PR should include:

* Clear description of changes
* Motivation and research impact
* Reproducibility considerations
* Related issues or paper sections (if applicable)

PRs are reviewed for:

* Scientific correctness
* Reproducibility
* Code quality
* Alignment with the published framework

---

## Licensing

By contributing, you agree that your contributions will be licensed under the
same license as this project.

---

Thank you for supporting reproducible federated learning research 🚀
