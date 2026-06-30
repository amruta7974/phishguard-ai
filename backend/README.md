# PhishGuard AI - Backend API Service

This directory houses the core backend service and business logic APIs for the PhishGuard AI platform.

## Purpose

To handle API requests from the frontend and browser extensions, coordinate with the AI Engine for real-time analysis, manage persistent data, handle authentication, and orchestrate background threat detection tasks.

## Planned Contents

* **API Endpoints**: RESTful endpoints for threat scoring, user management, alert notifications, and historical analysis.
* **Database Models**: Schemas for user accounts, domain reputations, threat logs, and analytics.
* **Services & Utilities**: Integration with the AI inference model, email and SMS analyzers, and rate-limiting modules.

## Planned Technologies

* **Language**: Python
* **API Framework**: FastAPI
* **Primary Database**: PostgreSQL (with SQLAlchemy ORM / Alembic migrations)
* **Caching & Queueing**: Redis (for session cache and task queue management)
