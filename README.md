# CI/CD Pipeline with GitHub Actions (Python)

## Overview

This project is a basic example of setting up a CI pipeline for a Python application using GitHub Actions.

The idea is to run tests automatically whenever changes are pushed, so it’s easier to catch issues early instead of testing everything manually.

---

## What it does

* Runs tests using pytest
* Triggers automatically on push and pull requests
* Helps check that the code is working as expected

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

## Run locally

```bash
git clone https://github.com/bahjo-awad/ci-cd-python-project.git
cd ci-cd-python-project
pip install -r requirements.txt
pytest
```

---

## What I learned

* How to set up a simple CI pipeline
* How GitHub Actions runs workflows when code changes
* Why automated testing is useful

---

## Next steps

* Add more tests
* Try Docker
* Look into deployment

---

## Author

Bahjo Omar Awad
