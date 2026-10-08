
# Playwright Python QA Portfolio

A test automation project built using **Python, Playwright and Pytest**, demonstrating web application testing, automated test design and modern QA development practices.

This repository is an ongoing portfolio project focused on developing and demonstrating practical test automation skills.

## Technologies

- **Python** – Test automation programming language
- **Playwright** – Browser automation framework
- **Pytest** – Test execution and assertions
- **Git & GitHub** – Source control and repository management

## Current Test Coverage

The initial test suite contains a browser-based test that:

- Navigates to https://example.com
- Verifies the expected page title using Playwright assertions
- Supports both headless and headed execution

Additional functional tests will be introduced as the project develops.

## Project Structure

```text
playwright-python-qa-portfolio/
├── tests/
│   └── test_example.py
├── .gitignore
├── requirements.txt
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.14
- Git

### 1. Clone the repository

```bash
git clone https://github.com/jbonge-qa/playwright-python-qa-portfolio.git
cd playwright-python-qa-portfolio
```

### 2. Create a virtual environment

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```powershell
python -m pip install -r requirements.txt
```

### 4. Install Chromium

```powershell
python -m playwright install chromium
```

### 5. Run the tests

Run all tests in headless mode:

```powershell
python -m pytest -v
```

Run tests with a visible browser:

```powershell
python -m pytest -v --headed
```

## Planned Enhancements

- Functional UI testing of a sample e-commerce application
- Positive and negative test scenarios
- Page Object Model (POM) architecture
- Reusable fixtures and test data
- API testing
- Cross-browser testing
- Test reporting and failure diagnostics
- GitHub Actions CI/CD integration

## Project Goals

The aim of this repository is to demonstrate practical QA automation skills, maintainable test design, and continuous improvement through hands-on development.

The project will evolve incrementally, with changes tracked through Git.
  