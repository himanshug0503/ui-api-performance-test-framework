# ui-api-performance-test-framework
Scalable test automation framework using Playwright + TypeScript featuring POM, data-driven testing, CI/CD with Jenkins, Dockerized execution, API and performance testing extensions.

Overview

Tech Stack

Project Architecture

Setup

Run Tests

Reports

CI/CD Pipeline

Docker Execution

Future Enhancements

Roadmap

[x] UI Automation
[ ] API Automation
[ ] Jenkins Pipeline
[ ] Dockerized Runs
[ ] JMeter Performance Suite
[ ] Allure Reporting

ui-api-performance-test-framework/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── src/
│   ├── pages/
│   │   ├── LoginPage.ts
│   │   ├── DashboardPage.ts
│   │   ├── ExpensePage.ts
│   │
│   ├── components/
│   │   ├── Modal.ts
│   │   └── Navbar.ts
│   │
│   ├── fixtures/
│   │   └── testFixtures.ts
│   │
│   ├── utils/
│   │   ├── apiClient.ts
│   │   ├── testData.ts
│   │   └── logger.ts
│   │
│   └── data/
│       └── expenses.json
│
├── tests/
│   ├── smoke/
│   ├── regression/
│   └── api/
│
├── docker/
│   └── Dockerfile
│
├── jmeter/
│
├── Jenkinsfile
├── playwright.config.ts
└── README.md
