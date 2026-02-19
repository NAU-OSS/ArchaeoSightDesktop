# Contributing to ArchaeoSightDesktop
Thank you for contributing to ArchaeoSightDesktop.  
This project focuses on scientific clarity, reproducibility, and maintainable code for archaeological data analysis.
---
# Reporting Issues
Before opening an issue:
1. Make sure you are on the latest version.
2. Search existing issues to avoid duplicates.
3. Confirm you can reproduce the problem.
When creating an issue, include:
- Operating system
- Python version
- Relevant dependency versions (`pip freeze`)
- Clear steps to reproduce
- Expected behavior
- Actual behavior
- Full error traceback (if applicable)
Use clear, descriptive titles.
---
# Bug Reports
A good bug report includes:
- A short description of the problem
- A minimal reproducible example
- Input data (if relevant)
- Model type being used (GBDT or Autoencoder + HDBSCAN)
- Full error message
Incomplete reports may be closed until more information is provided.
---
# Feature Requests
When requesting a feature, include:
- The problem it solves
- Why it benefits archaeological workflows
- A rough implementation idea (optional)
Keep requests focused and relevant to the project's goals.
---
# Pull Requests
Before submitting a pull request:
1. Create a new branch.
2. Add or update tests.
3. Run the full test suite.
4. Ensure code follows style guidelines.
5. Update documentation if needed.
Each PR should include:
- A clear description of changes
- Reference to a related issue (if applicable)
- Tests for new functionality
Small, focused pull requests are preferred.
---
# Code Style
All Python code must follow PEP 8:
https://peps.python.org/pep-0008/
Please ensure your code adheres to this standard before submitting.
---
# Testing Requirements
We use `pytest`.
Install:
```bash
pip install pytest
```
Run tests:
```
pytest
```
Requirements:
- New features must include tests.
- Tests must pass before submission.
- Avoid network calls in unit tests.
- Use deterministic behavior for ML models (set random seeds).
Pull requests without tests will not be merged.
---
# Documentation Standards
All public functions must include docstrings that describe:
- What the function does
- Parameters and types
- Return values
- Exceptions (if applicable)
If you modify architecture or user-facing behavior, update:
- README
- Relevant documentation
- Docstrings
Clear documentation is required for acceptance.
---
# Development Workflow
1. Fork the repository.
2. Clone your fork.
3. Create a virtual environment.
4. Install dependencies.
5. Create a feature branch.
6. Implement changes.
7. Add tests.
8. Run tests.
9. Submit pull request.
---
Thank you for contributing to ArchaeoSightDesktop.
