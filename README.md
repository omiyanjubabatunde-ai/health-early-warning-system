# Health Early Warning System (NEWS2-Style) — Secure Clinical Decision Support Platform

A secure, web-based Clinical Decision Support System (CDSS) that simulates hospital observations, calculates a NEWS2-style early warning score, triggers escalation alerts, and maintains audit logs. Built as an MSc Software Engineering capstone to demonstrate healthcare-grade software design, security, verification, and validation.

---

## Demo
- Video: (add link)
- Screenshots: (add images)

---

## Problem Statement
Clinical deterioration is often preceded by subtle physiological changes. Early warning scoring helps identify at-risk patients, but real-world systems must also manage alert workflows, access control, auditability, and data integrity. This project replicates a realistic workflow for early detection and escalation.

---

## Key Features
- Patient registration and encounter management
- Vital sign capture (simulated input + optional stream)
- NEWS2-style scoring engine (rule-based)
- Risk stratification and alert triggering
- Escalation workflow (e.g., nurse → doctor → rapid response)
- Role-Based Access Control (RBAC): Nurse / Doctor / Admin
- Audit logging of access and actions
- Secure authentication (JWT)
- Test suite (unit + integration)

---

## Architecture (High Level)
**Frontend:** React dashboard (observations, alerts, patient view)  
**Backend:** REST API (FastAPI / Node / .NET)  
**Database:** PostgreSQL (patients, observations, alerts, audit logs)  
**Security:** JWT + RBAC + audit trails

> Add your architecture diagram here:
> ![Architecture](docs/architecture-diagrams/architecture.png)

---

## Tech Stack
- Backend: FastAPI (Python) / (or your actual backend)
- Frontend: React
- Database: PostgreSQL
- Auth: JWT
- Containerization: Docker + docker-compose (optional)

---

## Repository Structure
