# CI/CD

## Jenkins Pipeline

Stages:

1. Checkout
2. Install Dependencies
3. Playwright Install
4. Execute Tests
5. Generate Allure Report
6. Publish Results

---

## Build Trigger

Manual

GitHub Webhook

Scheduled

---

## Sample Jenkins Command

npm install

npx playwright install

npx playwright test

---

## GitHub Actions

Workflow:

.github/workflows/ci.yml

Triggers:

push
pull_request

---

## Pipeline Flow

Developer Push
↓
GitHub
↓
GitHub Actions
↓
Playwright Tests
↓
Allure Report
