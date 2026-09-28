# Monkno

I build test systems that make browser, API, and performance behavior inspectable.

My public work focuses on Playwright and TypeScript end-to-end suites, plus Gatling-based performance engineering. I document what passes, why the suite is designed that way, where the application disagrees with the expected behavior, and what the tests deliberately leave untouched.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-up/)

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
  <source media="(prefers-color-scheme: dark)" srcset="https://ghchart.xqsit94.in/dark:default/Monkno">
  <source media="(prefers-color-scheme: light)" srcset="https://ghchart.xqsit94.in/Monkno">
  <img alt="Monkno's public GitHub contribution calendar for the last year" src="https://ghchart.xqsit94.in/Monkno">
</picture>

## Tools and platforms

**Automation and testing**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Gatling](https://img.shields.io/badge/Gatling-FF9E2A?style=flat-square&logo=gatling&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![BrowserStack](https://img.shields.io/badge/BrowserStack-F4B400?style=flat-square&logo=browserstack&logoColor=white)

**Code and delivery**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000000)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Cloud, data, and observability**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-1CE783?style=flat-square&logo=newrelic&logoColor=001E2B)

Also in my testing work: REST APIs, Swagger, SoapUI, Testiny, Jira, Confluence, VTEX, Salesforce, Page Objects, fixtures, test-data factories, and CI quality gates.

## Public profile

The repositories above contain the implementation, strategy notes, test cases, and run evidence behind each summary.
