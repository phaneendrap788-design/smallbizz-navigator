<p align="center">
<img src="./screenshots/banner.png" width="100%">
</p>

<h1 align="center">
🏢 SmallBizz Navigator
</h1>

<p align="center">

![Database](https://img.shields.io/badge/Database-MySQL-blue?style=for-the-badge)
![Architecture](https://img.shields.io/badge/Architecture-Enterprise-success?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-Role%20Based%20Access-red?style=for-the-badge)
![Management](https://img.shields.io/badge/Business-Management-orange?style=for-the-badge)

</p>

---

# 📖 Overview

SmallBizz Navigator is an **Enterprise Business Management System** designed to simplify day-to-day operations for small and medium-sized businesses.

The platform centralizes employee management, payroll, attendance tracking, customer management, inventory tracking, project management, analytics, and reporting into a single database-driven solution.

The system focuses on improving operational efficiency, reducing manual processes, and enabling secure business data management through a scalable relational database architecture.

---

# 🎯 Project Objectives

- Improve operational efficiency
- Centralize employee information
- Manage payroll and attendance
- Track inventory and business assets
- Manage customer relationships (CRM)
- Generate business reports
- Support project and task management
- Provide role-based user access
- Enable future scalability

---

# 🚀 Key Features

### 👨‍💼 Employee Management
- Employee profiles
- Department management
- Employee onboarding
- Experience records
- Personal information

---

### 💰 Payroll Management

- Salary processing
- Benefits management
- Loan management
- Payroll reports

---

### 🗓 Attendance & Leave

- Attendance tracking
- Leave requests
- Leave approval workflow
- Holiday management

---

### 📦 Inventory & Asset Management

- Inventory tracking
- Company assets
- Asset categories
- Employee asset assignment

---

### 📊 Business Analytics

- Reports Dashboard
- Employee statistics
- Payroll reports
- Attendance reports
- Performance insights

---

### 🔐 Security

- Role-Based Access Control (RBAC)
- Secure employee records
- Data privacy
- Permission management

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| MySQL | Relational Database |
| MySQL Workbench | Database Design |
| Draw.io | ER Diagram Design |
| Microsoft Office | Documentation |
| Windows | Development Environment |

---

# 🏗️ System Architecture

The platform follows a modular enterprise architecture where each business function interacts with a centralized MySQL database.

```text
                    Admin
                      │
        ┌─────────────┼──────────────┐
        │             │              │
   Employee      Attendance      Payroll
        │             │              │
        ├─────────────┼──────────────┤
        │             │              │
   Inventory      Projects      Reports
              │
         Authentication
              │
          MySQL Database
```

---

# 🗄️ Entity Relationship Diagram

The database design models employee information, departments, attendance, payroll, projects, leave requests, assets, and supporting business entities.

<p align="center">
<img width="1600" height="1207" alt="erd-overview png" src="https://github.com/user-attachments/assets/b3ef819f-d6be-425c-9f61-6ef728e0cce8" />

</p>

---

# 🏢 Enterprise Database Schema

The complete enterprise schema illustrates the relationships between employee records, departments, projects, payroll, attendance, assets, and administrative modules.

<p align="center">
<img width="1600" height="1007" alt="enterprise-schema png" src="https://github.com/user-attachments/assets/1f31a367-3d63-4c05-8725-a6f2eaee2652" />
</p>

---

# 📂 Repository Structure

```text
smallbizz-navigator
│
├── assets/
│
├── database/
│
├── diagrams/
│
├── docs/
│   ├── SmallBiz_Navigator_Report.pdf
│   └── SmallBiz_Project_Proposal.pdf
│
├── screenshots/
│   ├── banner.png
│   ├── erd-overview.png
│   └── enterprise-schema.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📈 Future Enhancements

- Web-based dashboard
- Mobile application
- Cloud deployment
- REST API integration
- Authentication with OAuth 2.0
- Business intelligence dashboard
- Real-time notifications
- Audit logging
- Multi-company support

---

# 📚 Documentation

Detailed project documentation and proposal are available in the **docs/** directory.

---

# 👥 Contributors

- Bala Phaneendra Pothuri
- Satya Vara Prasad Namala

---

## ⭐ Support

If you found this project interesting, consider giving the repository a **Star**.
