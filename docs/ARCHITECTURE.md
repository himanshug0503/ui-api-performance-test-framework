# Architecture

## Framework Design

The framework follows a layered architecture.

Tests
↓
Page Objects / API Clients
↓
Utilities
↓
Configurations
↓
Reporting

---

## Folder Structure

src/pages
Contains all Page Object Models.

src/api
Contains API request wrappers.

src/components
Reusable UI components.

src/fixtures
Shared test fixtures.

src/utils
Common utilities.

src/data
JSON and Excel test data.

src/config
Environment configurations.

tests/ui
UI test cases.

tests/api
API test cases.

tests/integration
UI + API combined scenarios.

tests/performance
Performance test execution.

---

## Design Patterns

### Page Object Model

Each page has:

- Locators
- Actions
- Validations

### Factory Pattern

Environment-specific configuration creation.

### Singleton Pattern

Reusable configuration manager.

### Data Driven Testing

JSON
Excel

### Dependency Injection

Fixtures inject dependencies.
