# Hi, I'm Neelima Gunduboina 👋

QA Engineer with 4+ years of experience in Banking and Insurance domains, based in London, UK.

I specialise in manual testing, API testing, SQL validation, and end-to-end business workflow testing — and I'm actively building automation skills with Selenium and Playwright.

---

## What I Work With

**Testing**
Manual · Functional · Regression · Sanity · Smoke · End-to-End · API · Data Migration · Release Validation

**Tools**
Postman · Jira · Zephyr · Azure DevOps · GitHub · Jenkins (basic)

**Automation**
Selenium WebDriver · Java · TestNG · Playwright · TypeScript · Page Object Model · REST Assured · GitHub Actions CI/CD

**Database**
SQL · Oracle · Backend Data Validation

**Domains**
Banking (Oracle FLEXCUBE / Citi Bank) · Insurance (Royal London)

---

## Featured Projects

### [qa-portfolio-parabank](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank)
[![CI](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/actions/workflows/ci.yml/badge.svg)](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/actions/workflows/ci.yml)

Banking test framework covering the layers I test at work: **UI** (Selenium + TestNG + Page Object Model), **API** (Postman/Newman and REST Assured) and **SQL backend validation** (Oracle-mode schema checking balances, rollback and audit trail).
End-to-end fund transfer and bill payment flows with balance reconciliation.

**5 real defects found and documented** in the live demo bank, each with a full report and an automated test:
- [DEF-002](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/blob/main/docs/defects/DEF-002-login-accepts-unknown-credentials.md) (Critical): login with unknown credentials signed you in as another customer
- [DEF-001](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/blob/main/docs/defects/DEF-001-negative-transfer-amount.md) (High): the transfer API accepts negative amounts
- [DEF-003](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/blob/main/docs/defects/DEF-003-ui-bill-pay-does-not-debit.md) (High): UI bill pay confirmed payments that were never debited
- [DEF-004](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/blob/main/docs/defects/DEF-004-zero-and-same-account-transfer.md) (Medium): $0 and same-account transfers are accepted
- [DEF-005](https://github.com/Neelima-Gunduboina/qa-portfolio-parabank/blob/main/docs/defects/DEF-005-long-username-reported-as-duplicate.md) (Medium): new usernames over 20 characters are rejected as "already exists"

### [ai-banking-qa-portfolio](https://github.com/Neelima-Gunduboina/ai-banking-qa-portfolio)
[![CI](https://github.com/Neelima-Gunduboina/ai-banking-qa-portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/Neelima-Gunduboina/ai-banking-qa-portfolio/actions/workflows/ci.yml)

Playwright + TypeScript framework for the same banking app, covering UI, API, visual regression and accessibility (WCAG 2.1 AA) tests across Chromium, Firefox and WebKit. It also adds Claude-powered GenAI tooling with a human review step: self-healing locators, test generation from requirements, and AI triage of CI failures. Includes a [WCAG 2.1 AA accessibility audit](https://github.com/Neelima-Gunduboina/ai-banking-qa-portfolio/blob/main/docs/accessibility-findings.md) of the bank (7 issues).

---

## Currently Learning

I'm working toward a Quality Engineer / SDET role in financial services.

- **Now:** automation fundamentals from a blank file: Java, Selenium + POM, REST Assured, SQL and test design, then Docker, framework design, CI and Playwright
- **Next:** Python for testers and testing LLM applications: evaluation, agents and MCP

---

## How I Test

- **Check the data, not just the screen**: balances are read before and after every transaction and reconciled to the penny.
- **Test every layer**: the same flow is checked in the UI, the API and the database, which is how DEF-003 was traced to the UI path only.
- **Find the real cause**: boundary-value testing showed DEF-005 was about username length, not what it first looked like.
- **Report defects properly**: steps to reproduce, expected vs actual, severity, evidence and a retest plan.
- **Keep CI green honestly**: open defects are tracked in a separate test group, not deleted or skipped silently; fixed ones stay as regression guards.

---

## Certifications

- ISTQB Certified Tester – Foundation Level (CTFL)
- Agile Testing Certification

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Neelima%20Gunduboina-blue?logo=linkedin)](https://www.linkedin.com/in/neelimagunduboina/)
