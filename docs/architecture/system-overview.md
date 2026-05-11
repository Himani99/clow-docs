# System Overview

The Clow platform is composed of modular services that automate CRM operations and AI workflows.

## Core Components

- Frontend Dashboard
- Workflow Engine
- AI Agent Services
- CRM Services
- Notification System
- Selenium Automation

```mermaid
graph TD
    A[Frontend Dashboard] --> B[API Gateway]

    B --> C[CRM Service]
    B --> D[Workflow Engine]
    B --> E[AI Agent Service]

    D --> F[Selenium Automation]
    E --> G[LLM Provider]

    C --> H[Database]
```