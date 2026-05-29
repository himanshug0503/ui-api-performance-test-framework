# Setup Guide

## Prerequisites

Install the following:

### 1. Node.js

Version:
18+

Verify:

node -v
npm -v

---

### 2. Git

Verify:

git --version

---

### 3. Java JDK

Required for JMeter.

Version:
17+

Verify:

java -version

---

### 4. Apache JMeter

Download:
https://jmeter.apache.org

Verify:

jmeter -v

---

### 5. Docker Desktop

Verify:

docker --version

docker compose version

---

### 6. Jenkins

Verify:

http://localhost:8080

---

### 7. Visual Studio Code

Recommended Extensions:

Playwright Test
ESLint
Prettier
GitLens

---

## Clone Repository

git clone <repo-url>

cd ui-api-performance-test-framework

---

## Install Dependencies

npm install

---

## Install Playwright Browsers

npx playwright install

Install all browsers:

npx playwright install chromium firefox webkit

---

## Install Allure

npm install -g allure-commandline

Verify:

allure --version

---

## Install TypeScript

npm install -g typescript

Verify:

tsc -v

---

## Install JMeter Plugins

Plugin Manager

Custom Thread Groups

Dummy Sampler

Throughput Shaping Timer

---

## Environment Variables

Create:

.env

Example:

BASE_URL=https://demo.opencart.com

API_URL=https://reqres.in

USERNAME=admin

PASSWORD=admin123

ENV=qa

---

## Verify Installation

Run:

npx playwright test

Expected:

Tests execute successfully.
