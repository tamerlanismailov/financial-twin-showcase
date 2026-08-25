# Financial Twin

**Personal finance assistant built as a Telegram Mini App.**

Financial Twin is a full-stack fintech product for managing everyday personal finances directly inside Telegram.

It combines income and expense tracking, balance management, financial goals, analytics and account management in a single interface.

> This repository is a public showcase of the project.  
> Production source code, credentials, infrastructure secrets and user data are intentionally not included.

---

## Product Overview

Financial Twin was developed as a complete product — from product logic and UI to backend architecture, database design, security, deployment and production infrastructure.

The current MVP focuses on the core personal finance workflow:

- Income tracking
- Expense tracking
- Current balance
- Financial goals
- Analytics
- Transaction history
- Calendar
- Onboarding
- Account and privacy management

---

## Core Features

### Personal Finance

- Income management
- Expense management
- Automatic balance calculation
- Financial goals
- Monthly analytics
- Transaction history
- Calendar-based finance overview

### Telegram Integration

- Telegram Mini App interface
- Telegram user authentication
- Protected API requests
- User-specific data access

### Account & Privacy

- User onboarding
- Account management
- Personal data isolation
- Account deletion flow
- Privacy controls

---

## Architecture

```text
Telegram
   │
   ▼
Telegram Mini App
   │
   ▼
HTML / CSS / JavaScript
   │
   │ REST API
   ▼
FastAPI
   │
   ├── Authentication
   ├── Business Logic
   ├── Validation
   └── User Isolation
   │
   ▼
SQLAlchemy
   │
   ▼
PostgreSQL
```

### Production Infrastructure

```text
Client
   │
   │ HTTPS
   ▼
Nginx
   │
   ▼
FastAPI / Uvicorn
   │
   ▼
PostgreSQL
```

---

## Tech Stack

### Backend

- Python
- FastAPI
- SQLAlchemy
- Pydantic
- PostgreSQL
- Alembic

### Frontend

- HTML
- CSS
- JavaScript
- Telegram Mini Apps API

### Infrastructure

- Linux
- Nginx
- Uvicorn
- VPS
- HTTPS
- Git
- GitHub

---

## Security

Security is treated as part of the product architecture rather than an afterthought.

Implemented practices include:

- Telegram authentication validation
- Protected API endpoints
- User data isolation
- Resource ownership checks
- Input validation
- Environment-based secret management
- Credentials stored outside source code
- HTTPS
- Privacy controls
- Account deletion flow

Sensitive production information is intentionally excluded from this public repository.

---

## Engineering Highlights

Financial Twin includes more than the core finance functionality.

The project also covers:

- Database migrations and schema evolution
- Backend validation and error handling
- Loading, empty, error, success and disabled UI states
- Telegram-specific navigation and authentication
- Mobile keyboard and safe-area handling
- Infrastructure configuration
- Backup and recovery preparation
- Production deployment workflow
- Internal QA before closed beta

---

## Project Status

**MVP v0.1.0**

The MVP includes the complete core finance workflow and has been deployed to production infrastructure.

Current implementation includes:

- Core income and expense management
- Balance calculation
- Financial goals
- Analytics
- Calendar
- Telegram authentication
- User onboarding
- User data isolation
- Privacy and deletion flows
- Production infrastructure

---

## Screenshots

Product screenshots will be added to this repository to demonstrate the Financial Twin interface and main user flows.

Planned showcase screens:

- Home dashboard
- Expenses
- Income
- Analytics
- Calendar
- Financial goal
- Onboarding
- Profile and account management

---

## Public Showcase Policy

The main Financial Twin development repository is private.

This public repository exists to demonstrate:

- The product concept
- Product functionality
- System architecture
- Technology stack
- Engineering approach
- UI/UX
- Development scope

It intentionally does **not** contain:

- Production credentials
- `.env` files
- Database passwords
- Telegram tokens
- Private infrastructure configuration
- Database dumps
- User data
- Production logs
- Internal production source code

---

## Repository Roadmap

This showcase will be expanded with:

- Product screenshots
- Architecture diagrams
- Additional technical documentation
- Product development history
- Selected engineering decisions

---

## Author

**Tamerlan Ismailov**

Business Informatics student focused on backend development and building digital products.

[GitHub Profile](https://github.com/tamerlanismailov)
