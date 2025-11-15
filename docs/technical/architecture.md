# System architecture

## Overview

The system uses a modular service-oriented architecture:

- **Web UI** – React/TypeScript SPA
- **API Gateway** – REST endpoints for UI and integrations
- **Core services**
  - client-service
  - trade-service
  - workflow-service
- **Data layer**
  - PostgreSQL for transactions
  - Redis for caching
- **Messaging**
  - Kafka for event-driven integration

## Environments

- `dev` – development and integration
- `qa` – testing
- `uat` – user acceptance
- `prod` – production

