# Test Execution

## Execute All Tests

npx playwright test

---

## Execute UI Tests

npx playwright test tests/ui

---

## Execute API Tests

npx playwright test tests/api

---

## Execute Integration Tests

npx playwright test tests/integration

---

## Execute Specific Test

npx playwright test login.spec.ts

---

## Execute in Headed Mode

npx playwright test --headed

---

## Execute in Debug Mode

npx playwright test --debug

---

## Parallel Execution

npx playwright test --workers=4

---

## Retry Execution

Configured in playwright.config.ts

Example:

retries: 2

---

## Generate Allure Results

npx playwright test

---

## Open Allure Report

allure serve allure-results
