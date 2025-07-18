# DineTap · GitHub Organization

Welcome to **DineTap's GitHub** – the central hub for our engineering projects that power seamless dining and payment experiences for restaurants and their guests.

DineTap provides a modern ecosystem for:
- 💳 **In-Store & Online Payments**
- 🖥️ **Cloud POS & Ordering**
- 🧾 **Invoice Automation & Reporting**
- 🧑‍🍳 **Restaurant Back Office Management**
- 📱 **Customer & Partner Mobile Apps**

---

## 🔗 Core Repositories

Below is a curated list of the most important repositories across services, frontends, infrastructure, and shared libraries:

### 🖥️ Web & Mobile Frontends

| Repository | Description |
|------------|-------------|
| [`pos-app`](https://github.com/eatme-global/pos-app) | React Native application for the Point-of-Sale system |
| [`backoffice-web`](https://github.com/eatme-global/backoffice-web) | Web application for restaurant back-office users |
| [`admin-web`](https://github.com/eatme-global/admin-web) | Web interface for DineTap's internal admin team |
| [`dashboard-app`](https://github.com/eatme-global/dashboard-app) | UI dashboard for analytics and reporting |
| [`payments-app`](https://github.com/eatme-global/payments-app) | React Native app for payment workflows |
| [`restaurant-owners-app`](https://github.com/eatme-global/restaurant-owners-app) | Dashboard app for restaurant partners |
| [`dinetap-app`](https://github.com/eatme-global/dinetap-app) | Expo-based mobile app (WIP) for customer wallet & ordering |

---

### ⚙️ Backend Services & APIs

| Repository | Description |
|------------|-------------|
| [`payments-service`](https://github.com/eatme-global/payments-service) | Node.js service for payment orchestration |
| [`admin-api`](https://github.com/eatme-global/admin-api) | Express API for admin operations |
| [`restaurants-service`](https://github.com/eatme-global/restaurants-service) | Microservice for restaurant data |
| [`menu-service`](https://github.com/eatme-global/menu-service) | Menu & catalog microservice |
| [`discounts-service`](https://github.com/eatme-global/discounts-service) | Service managing offers and discounts |
| [`adyen-payments-api`](https://github.com/eatme-global/adyen-payments-api) | API wrapper for Adyen integrations |

---

### 🧱 Infrastructure & DevOps

| Repository | Description |
|------------|-------------|
| [`ecs-service-cdk`](https://github.com/eatme-global/ecs-service-cdk) | AWS CDK setup for ECS service deployments |
| [`ecs-infra-cdk`](https://github.com/eatme-global/ecs-infra-cdk) | Infrastructure provisioning for networking, logs, etc. |
| [`database-cdk`](https://github.com/eatme-global/database-cdk) | CDK configuration for managed RDS databases |
| [`etl-cdk`](https://github.com/eatme-global/etl-cdk) | CDK definitions for ETL-related Lambdas |
| [`sqs-cdk`](https://github.com/eatme-global/sqs-cdk) | CDK stack for message queues |

---

### 🧠 ETL, Reporting & Data

| Repository | Description |
|------------|-------------|
| [`lambda-payments-etl`](https://github.com/eatme-global/lambda-payments-etl) | ETL for payment records |
| [`lambda-monthly-payments-etl`](https://github.com/eatme-global/lambda-monthly-payments-etl) | Monthly financial reports |
| [`lambda-invoices-etl`](https://github.com/eatme-global/lambda-invoices-etl) | Invoice generation pipeline |
| [`lambda-adyen-costs-etl`](https://github.com/eatme-global/lambda-adyen-costs-etl) | Cost aggregation from Adyen |
| [`lambda-restaurants-performances-etl`](https://github.com/eatme-global/lambda-restaurants-performances-etl) | Restaurant performance analytics |

---

### 🔄 Webhooks & Integrations

| Repository | Description |
|------------|-------------|
| [`lambda-dinetap-payments-webhook`](https://github.com/eatme-global/lambda-dinetap-payments-webhook) | Stripe webhook for payment events |
| [`lambda-adyen-payments-webhook`](https://github.com/eatme-global/lambda-adyen-payments-webhook) | Adyen webhook processor |
| [`lambda-adyen-onboarding-webhook`](https://github.com/eatme-global/lambda-adyen-onboarding-webhook) | Adyen onboarding status handling |
| [`lambda-adyen-transfers-webhook`](https://github.com/eatme-global/lambda-adyen-transfers-webhook) | Webhook for Adyen fund transfers |

---

## 🛠 Contribution Guidelines

We use [Conventional Commits](https://www.conventionalcommits.org/) and follow a standard branching model:
- `main`: Production-ready code
- `dev`: Latest development
- `feature/*`: New feature branches
- `fix/*`: Bugfix branches

🔒 Many repositories are private. Access is granted based on project scope and role.

---

## 📬 Contact

- For access or repo onboarding: `devops@dinetap.com`
- Security issues: `security@dinetap.com`
- General support: [https://dinetap.com](https://dinetap.com)

---

> © 2025 DineTap Technologies. All rights reserved.
