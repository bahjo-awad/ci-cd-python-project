# CI/CD Pipeline with GitHub Actions (Python)

## Overview

This project is a simple example of setting up a CI pipeline using GitHub Actions for a Python application.

The goal was to understand how automated testing works in a real workflow, where tests run every time code is pushed or updated.

---

## What it does

* Runs tests automatically using pytest
* Triggers on push and pull requests
* Helps make sure the code is working correctly

---

## Tools used

* Python
* pytest
* Git & GitHub
* GitHub Actions

---

## Project structure

```text
ci-cd-python-project/
├── app.py
├── test_app.py
├── requirements.txt
└── .github/
    └── workflows/
        └── ci.yml
```

---

## Running it locally

```bash
git clone https://github.com/bahjo-awad/ci-cd-python-project.git
cd ci-cd-python-project
pip install -r requirements.txt
pytest
```

---

## What I learned

* How CI pipelines work in practice
* How to use GitHub Actions to automate testing
* Why automated testing is important in development

---

## Next steps

* Try adding Docker
* Improve test coverage
* Learn how to deploy applications

---

## Author

Bahjo Omar Awad
