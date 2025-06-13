# 🧪 Python Tests with GitHub Actions

![CI](https://github.com//makolesnik/demo-python-test-github-actions/actions/workflows/test.yml/badge.svg)

This repository runs automated Python tests using GitHub Actions. On every push or pull request to the `main` branch, it sets up Python 3.11, installs dependencies from `requirements.txt`, runs `pytest` on the `tests/` directory, and generates a JUnit XML report. The report is uploaded as an artifact named `junit-report` for easy access. This setup ensures continuous integration and immediate feedback on test results.
