# Secure Investor Client Portal for Fund Management

## Project Overview
This capstone project focuses on developing a secure web-based Investor Client Portal for a fund management environment. The system aims to improve investor reporting, security, transparency, and operational efficiency by replacing manual spreadsheet and email-based workflows with a centralized digital platform.

The portal allows authenticated investors to securely access portfolio information, account value, daily P&L, performance trends, and selected self-service workflows through a responsive dashboard interface.

---

# Key Features

## Authentication & Security
- Invitation-based onboarding
- Secure login with MFA simulation
- Password hashing using bcrypt
- Session timeout handling
- Password reset functionality
- Role-Based Access Control (RBAC)
- Audit logging for security events

## Investor Dashboard
- Account value overview
- Daily P&L tracking
- Daily, Monthly, and YTD returns
- Performance charts and trend analysis
- Clear “as of” date references

## Backend & Data Processing
- REST API architecture
- Relational database design
- Daily P&L calculation pipeline
- Dummy transaction data ingestion
- Audit log tracking

## Optional Stretch Features
- Deposit and withdrawal request workflow
- Operations approval/review process
- Request status tracking

---

# Tech Stack

## Frontend
- React.js / Next.js
- Chart.js / Recharts
- HTML/CSS
- JavaScript

## Backend
- Node.js
- Express.js

## Database
- PostgreSQL / MySQL

## Authentication & Security
- JWT Authentication
- bcrypt
- MFA Simulation

## Development Tools
- Git & GitHub
- Visual Studio Code
- Postman / Thunder Client
- Figma

---

# System Roles

## Investor
- View account performance
- View portfolio metrics
- Track request statuses

## Operations User
- Review investor requests
- Update workflow statuses

## Admin
- Manage roles and permissions
- Review audit logs
- Monitor authentication activity

---

# Project Objectives
- Develop a secure investor-facing web portal
- Improve transparency and reporting efficiency
- Demonstrate authentication and RBAC implementation
- Provide portfolio analytics and dashboard visualization
- Maintain auditability and compliance awareness
- Create a scalable architecture for future enhancements

---

# Project Scope

## Mandatory MVP
- Authentication system
- MFA simulation
- RBAC
- Investor dashboard
- Daily P&L reporting
- Performance charts
- Audit logging
- Database and API integration

## Stretch Scope
- Deposit/withdrawal workflow
- Operations approval system
- Status tracking

---

# Team Members

| Name | Role |
|---|---|
| Jerremmy Lee Rasni | Project Team Leader / Backend Developer |
| Simon Saw Yong Ping | Scrum Master / Authentication Developer |
| Daymas Shield | Frontend / Dashboard Developer |
| Suganesan | Backend / Data & Testing Developer |

---

# Sprint Structure

| Sprint | Focus |
|---|---|
| Sprint 1 | Planning, Scope & Architecture |
| Sprint 2 | Authentication & RBAC |
| Sprint 3 | Backend, Database & P&L Pipeline |
| Sprint 4 | Investor Dashboard & Charts |
| Sprint 5 | Optional Operations Workflow |
| Sprint 6 | Testing, Security Review & Deployment |
| Sprint 7 | Demo, Viva & Final Report |

---

# Installation & Setup

## Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/secure-investor-client-portal.git
