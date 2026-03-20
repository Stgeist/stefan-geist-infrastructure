# Stefan Geist Deployment Infrastructure

This repository contains the infrastructure setup for my personal web services, including CI/CD workflows and Docker Compose configuration. It is designed to make building, testing, and deploying my projects easy and consistent.  
**Note:** This repository is for deploying my portfolio and backend tools; it is not intended for local use by others.

---

## Included Services
- **Frontend**: Dev-Portfolio
- **Backend Tool (Lab)**: Link Shortener
- **Database**: PostgreSQL
- **Orchestration**: Docker Compose

## Features
- Full containerization of services
- Automated build, test, and deployment via CI/CD
- Easy scaling and separation of multiple projects
- Centralized management of environment variables and ports

## Setup Instructions

### 1. Environment Variables
Create a `.env` file in the same directory as the `docker-compose.yml` file. Example:

```env
# PostgreSQL settings
POSTGRES_DB=linkshortener
POSTGRES_USER=user
POSTGRES_PASSWORD=supersecurepasswordofuser
POSTGRES_PORT=

# Backend service
LINK_SHORTENER_PORT=

# Frontend service
DEV_PORTFOLIO_PORT=
