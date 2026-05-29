# ui-api-performance-test-framework

# UI API Performance Test Framework

A scalable and maintainable test automation framework built with **Playwright + TypeScript**, designed to demonstrate modern automation practices including UI, API, and Performance Testing.

## Features

- UI Automation using Playwright and Page Object Model (POM)
- API Automation using ReqRes and JSONPlaceholder APIs
- Data-Driven Testing with JSON and Excel
- Parallel Execution and Retry Mechanism
- Allure Reporting with Screenshots and Videos
- CI/CD Integration using Jenkins and GitHub Actions
- Dockerized Test Execution
- Performance Testing using JMeter
- Environment-Based Configuration
- Reusable Utilities, Fixtures, and Custom Logging

## Automated Applications

### OpenCart

- Login & Authentication
- Product Search
- Add to Cart
- Checkout Flow
- Order History Validation

### OrangeHRM

- Employee Management
- Leave Management
- Admin Module
- File Upload Validation
- Dynamic Tables & Search Filters

## Project Goals

This framework showcases an enterprise-style automation solution that combines UI, API, and Performance Testing into a single repository while following industry best practices for scalability, maintainability, and CI/CD readiness.

## Documentation

- [Framework Architecture](docs/ARCHITECTURE.md)
- [Setup Guide](docs/SETUP.md)
- [CI/CD Pipeline](docs/CI-CD.md)
- [Docker Execution](docs/DOCKER.md)
- [Reporting](docs/REPORTING.md)

## Roadmap

- [ ] UI Automation
- [ ] API Automation
- [ ] Data-Driven Testing
- [ ] Excel Integration
- [ ] Jenkins Pipeline
- [ ] GitHub Actions
- [ ] Dockerized Execution
- [ ] Allure Reporting
- [ ] JMeter Performance Testing
- [ ] Parallel Execution
- [ ] Database Validation
- [ ] Visual Testing
- [ ] Kubernetes Integration
- [ ] Accessibility Testing

ui-api-performance-test-framework/
│
├── .github/
│ └── workflows/
│ └── ci.yml
│
├── docs/
│ ├── ARCHITECTURE.md
│ ├── SETUP.md
│ ├── EXECUTION.md
│ ├── CI-CD.md
│ ├── DOCKER.md
│ └── PERFORMANCE.md
│
├── src/
│ ├── pages/
│ │ ├── opencart/
│ │ └── orangehrm/
│ │
│ ├── api/
│ │ ├── reqres/
│ │ ├── jsonplaceholder/
│ │ └── opencart/
│ │
│ ├── components/
│ ├── fixtures/
│ ├── utils/
│ │
│ ├── data/
│ │ ├── json/
│ │ └── excel/
│ │
│ └── config/
│
├── tests/
│ ├── ui/
│ │ ├── opencart/
│ │ └── orangehrm/
│ │
│ ├── api/
│ ├── integration/
│ └── performance/
│
├── jmeter/
├── docker/
├── reports/
│
├── Jenkinsfile
├── Dockerfile
├── docker-compose.yml
├── playwright.config.ts
├── package.json
├── tsconfig.json
└── README.md
