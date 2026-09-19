🏛️ Digital Subsidy & Grant Administration Platform

A web-based Government Subsidy and Grant Administration Platform designed to manage the complete subsidy lifecycle — from beneficiary registration and eligibility evaluation to multi-level verification, approval, staged disbursement, fund utilization, and compliance monitoring.

The system provides role-based access for beneficiaries and government officers while maintaining application status tracking, audit logs, utilization monitoring, and reporting.

🚀 Key Features

- 👤 Beneficiary registration and management
- 🏛️ Government scheme management
- 📊 Automated eligibility scoring
- 🔍 Multi-level verification workflow
- ✅ Application approval and rejection
- 💰 Staged subsidy disbursement
- 📌 Milestone-based compliance tracking
- 🏦 DBT payment simulation
- 📈 Fund utilization monitoring
- 📊 Regional and scheme-level analytics
- 📄 PDF and Excel report generation
- 🔐 JWT-based authentication
- 👥 Role-Based Access Control (RBAC)
- 📝 Application status tracking
- 📋 Audit logging
- ⏰ Automated compliance monitoring

🛠️ Technology Stack

Backend

- Java 21
- Spring Boot 3.2.5
- Spring Security
- JWT Authentication
- Spring Data JPA
- Hibernate
- Maven

Database

- MySQL 8
- MySQL Connector/J

Frontend

- React 18
- Vite
- Axios
- JavaScript
- CSS

 Reporting

- Apache POI for Excel reports
- OpenPDF for PDF reports

---

🏗️ System Architecture

```text
                    ┌──────────────────────┐
                    │      React UI        │
                    │   React + Vite       │
                    └──────────┬───────────┘
                               │
                               │ REST API
                               ▼
                    ┌──────────────────────┐
                    │    Spring Boot       │
                    │      Backend         │
                    ├──────────────────────┤
                    │ Controllers           │
                    │ Services              │
                    │ Repositories          │
                    │ Security / JWT        │
                    │ Business Logic        │
                    └──────────┬───────────┘
                               │
                               │ JPA / Hibernate
                               ▼
                    ┌──────────────────────┐
                    │       MySQL           │
                    │    subsidy_db         │
                    └──────────────────────┘
