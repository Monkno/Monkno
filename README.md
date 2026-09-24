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

## Tools and platforms

**Automation and code**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts%2Cjs%2Cnodejs%2Cjava%2Ccypress%2Cselenium&amp;theme=dark">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=ts%2Cjs%2Cnodejs%2Cjava%2Ccypress%2Cselenium&amp;theme=light">
  <img alt="TypeScript, JavaScript, Node.js, Java, Cypress, and Selenium" src="https://skillicons.dev/icons?i=ts,js,nodejs,java,cypress,selenium&amp;theme=light">
</picture>

**Delivery, cloud, and data**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=git%2Cgithub%2Cgithubactions%2Cgitlab%2Cjenkins%2Caws%2Cpostgres%2Cmysql%2Cmongodb%2Cgrafana%2Cpostman&amp;perline=6&amp;theme=dark">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=git%2Cgithub%2Cgithubactions%2Cgitlab%2Cjenkins%2Caws%2Cpostgres%2Cmysql%2Cmongodb%2Cgrafana%2Cpostman&amp;perline=6&amp;theme=light">
  <img alt="Git, GitHub, GitHub Actions, GitLab, Jenkins, AWS, PostgreSQL, MySQL, MongoDB, Grafana, and Postman" src="https://skillicons.dev/icons?i=git,github,githubactions,gitlab,jenkins,aws,postgres,mysql,mongodb,grafana,postman&amp;perline=6&amp;theme=light">
</picture>

Also in my testing work: Playwright, Gatling, REST APIs, Swagger, SoapUI, BrowserStack, New Relic, Testiny, Jira, Confluence, VTEX, Salesforce, Page Objects, fixtures, test-data factories, and CI quality gates.

## Public profile

The repositories above contain the implementation, strategy notes, test cases, and run evidence behind each summary.
