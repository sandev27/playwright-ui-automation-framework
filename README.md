# Playwright UI Automation Framework

A UI test automation project built using Playwright, TypeScript and GitHub Actions.

## Tech Stack

- Playwright
- TypeScript
- Node.js
- Git and GitHub
- GitHub Actions

## Project Structure

```text
playwright-ui-automation-framework/
├── .github/
│   └── workflows/
│       └── playwright.yml
├── test/
│   └── example.spec.ts
├── .gitignore
├── package.json
├── package-lock.json
├── playwright.config.ts
└── README.md
```

## Getting Started

### Install Dependencies

```bash
npm ci
```

### Install Playwright Browsers

```bash
npx playwright install
```

## Running Tests

Run all configured tests:

```bash
npx playwright test
```

Run tests in Chromium:

```bash
npx playwright test --project=chromium
```

Run tests using Playwright UI Mode:

```bash
npx playwright test --ui
```

## Test Reports

View the HTML test report:

```bash
npx playwright show-report
```

## Continuous Integration

This project uses GitHub Actions to automatically execute Playwright tests on pushes and pull requests to the configured branches.

The workflow installs dependencies, installs Playwright browsers, executes tests and uploads the Playwright HTML report.

## Current Progress

- [x] Initial Playwright project setup
- [x] TypeScript configuration
- [x] Local test execution
- [x] GitHub repository setup
- [x] GitHub Actions CI integration
- [x] Initial CI execution — 6 tests passed
- [ ] Page Object Model implementation
- [ ] Additional UI automation scenarios
- [ ] Reusable fixtures and test data

## Project Purpose

This project demonstrates my hands-on learning and development of UI test automation skills using Playwright and TypeScript. It will be expanded with maintainable test architecture, reusable components and realistic end-to-end testing scenarios.
