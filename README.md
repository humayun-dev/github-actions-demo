# GitHub Actions Demo Project

[![CI](https://github.com/humayun-dev/github-actions-demo/actions/workflows/ci.yml/badge.svg)](https://github.com/humayun-dev/github-actions-demo/actions)

This project demonstrates **Continuous Integration (CI)** using **GitHub Actions** with Python.  
It automatically runs tests and checks code quality every time you push code to GitHub.

---

## Project Structure
```text
github-actions-demo/
├── app.py            # Your main application code
├── test_app.py       # Unit tests for app.py
├── requirements.txt  # Python dependencies
└── .github/
    └── workflows/
        └── ci.yml   # GitHub Actions workflow file


---

## Features

- Automated **unit testing** using `pytest`
- **Code style checking** using `flake8`
- Multi-job CI pipeline:
  - Run tests
  - Run linter
- Runs automatically on every push to `main` branch
- Beginner-friendly setup — no extra configuration needed

---

## Getting Started (Local Setup)


How it Works
Every push triggers the CI workflow
pytest ensures your code behaves as expected
flake8 ensures your code follows Python style standards
Green ✅ = all tests pass and code is clean
Red ❌ = tests fail or code style issues