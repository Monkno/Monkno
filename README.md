# Monkno

I build test systems that make browser, API, and performance behavior inspectable.

My public work focuses on Playwright and TypeScript end-to-end suites, plus Gatling-based performance engineering. I document what passes, why the suite is designed that way, where the application disagrees with the expected behavior, and what the tests deliberately leave untouched.

<a href="https://www.linkedin.com/in/luis-up/">
  <img src="https://skillicons.dev/icons?i=linkedin" height="32" alt="LinkedIn profile">
</a>

## Selected work

### [automationintesting.online](https://github.com/Monkno/automationintesting.online)

An end-to-end suite for a booking platform with a public site, admin panel, and REST API.

- 37 executable tests covering catalogue, booking, contact, admin, and unit behavior
- 16 documented defects and oddities found during implementation
- API-backed cleanup that protects seed data and other users' records on the shared demo
- A written strategy covering isolation, redundancy, coverage gaps, and trade-offs

### [ParaBank](https://github.com/Monkno/ParaBank)

A browser and API test suite for Parasoft's demo banking application.

- 72 tests running without retries
- Coverage for authentication, accounts, transfers, bill payments, loans, transaction search, and profile changes
- Worker count chosen from measured rate-limit behavior, not a default setting
- Defect-pinning tests that fail when the underlying application behavior changes

### [QuickPizza Performance Engineering](https://github.com/Monkno/Quickpizza)

A performance-testing and black-box observability project for Grafana's public QuickPizza environment.

- Gatling simulations written in TypeScript
- Manual-only smoke, baseline, and light-ramp workflows with explicit safety controls
- Versioned evidence for every completed run and claim
- A credit-bounded workload design that preserves the investigation buffer

### [SauceDemo QA Challenge](https://github.com/Monkno/qa-saucedemo)

A focused Playwright suite for SauceDemo's login module.

- Page Object Model structure in TypeScript
- Automated coverage for valid, empty, invalid, locked-out, and whitespace-padded credentials
- A test-execution report generated from the latest run

## How I work

- A green suite should mean the product behavior was checked, not that failures were hidden behind retries.
- Shared test environments need unique data, bounded workloads, and reliable cleanup.
- UI checks become more useful when they verify the backend state that the user action was supposed to create.
- Test documentation should explain exclusions and trade-offs instead of pretending coverage is complete.

## Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Monkno&amp;theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Monkno&amp;theme=github">
  <img alt="Monkno's public GitHub contribution activity over the last year" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Monkno&amp;theme=github">
</picture>

## Tools in these projects

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,nodejs,git,github,githubactions&amp;theme=dark">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=ts,nodejs,git,github,githubactions&amp;theme=light">
  <img alt="TypeScript, Node.js, Git, GitHub, and GitHub Actions" src="https://skillicons.dev/icons?i=ts,nodejs,git,github,githubactions&amp;theme=light">
</picture>

TypeScript, Playwright, Gatling, GitHub Actions, REST APIs, Page Objects, fixtures, test-data factories, and CI quality gates.

## Public profile

The repositories above contain the implementation, strategy notes, test cases, and run evidence behind each summary.
