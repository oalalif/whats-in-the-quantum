# Contributing to Quantum Circuit Simulator

Thank you for your interest in contributing to the Quantum Circuit Simulator! We welcome all contributions, including bug reports, feature requests, and code contributions.

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally
3. Create a new branch for your changes
4. Make your changes and commit them
5. Push your changes to your fork
6. Open a pull request

## Development Setup

```bash
# Install development dependencies
pip install -r requirements-dev.txt

# Run tests
pytest

# Run linter
flake8 quantum_core/

# Run type checker
mypy quantum_core/
```

## Code Style

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for Python code
- Use [Google-style docstrings](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html)
- Keep lines under 88 characters (Black formatter will enforce this)

## Pull Request Guidelines

- Keep pull requests focused on a single feature or bug fix
- Include tests for new features and bug fixes
- Update documentation as needed
- Ensure all tests pass before submitting

## Reporting Issues

When reporting issues, please include:

- A clear description of the problem
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Environment details (Python version, OS, etc.)

## License

By contributing, you agree that your contributions will be licensed under the project's [MIT License](LICENSE).
