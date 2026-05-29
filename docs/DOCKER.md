# Docker Setup

## Build Docker Image

docker build -t automation-framework .

---

## Run Container

docker run automation-framework

---

## Docker Compose

docker compose up

---

## Stop Containers

docker compose down

---

## Execute Tests Inside Container

docker exec -it container-id bash

npx playwright test

---

## Rebuild Image

docker compose build

---

## Benefits

Consistent Environment

No Local Dependency Issues

CI/CD Friendly

Portable Execution
