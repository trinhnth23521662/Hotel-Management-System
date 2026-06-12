# Hotel Management System

![Node.js](https://img.shields.io/badge/Node.js-Backend-green)
![Express.js](https://img.shields.io/badge/Express.js-Framework-black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![Neon](https://img.shields.io/badge/Neon-Cloud%20Database-brightgreen)
![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-yellow)
![Render](https://img.shields.io/badge/Render-Deployed-purple)

<div align="center">

### SE104 – Introduction to Software Engineering

**University of Information Technology (UIT) – VNUHCM**

---

A web-based Hotel Management System designed to support hotel operations including room management, customer registration, room rental, invoice processing, reporting, and business rule administration.

</div>

---

# Introduction

As the hospitality industry continues to grow, hotels must manage increasing volumes of customer, room, and transaction data. Traditional manual processes are often time-consuming and prone to errors.

This project develops a centralized Hotel Management System that helps hotel staff:

* Manage rooms and room categories.
* Register and search customers.
* Create and track room rentals.
* Generate invoices automatically.
* Produce monthly business reports.
* Configure hotel regulations and surcharge policies.

The project was developed following the **Waterfall Software Development Life Cycle (SDLC)** as part of the SE104 course.

---

# Project Objectives

* Digitize hotel management operations.
* Improve accuracy and efficiency of hotel workflows.
* Centralize customer, room, rental, and invoice information.
* Support configurable business regulations.
* Apply software engineering principles throughout the development process.

---

# Live Demo

🌐 **Website:**
https://trinhnth23521662.github.io/Hotel-Management-System/

[![Live Demo](https://img.shields.io/badge/Website-Live_Demo-success?style=for-the-badge)](https://trinhnth23521662.github.io/Hotel-Management-System/)

### Demo Accounts

| Role         | Username    | Password |
| ------------ | ----------- | -------- |
| Director     | `giamdoc01` | `123456` |
| Receptionist | `letan01`   | `123456` |
| Manager      | `quanly01`  | `123456` |

> Use these accounts to explore different permission levels and system functionalities.

---

# System Architecture

```text
Frontend (HTML/CSS/JavaScript)
                │
                ▼
        Express.js API
                │
                ▼
     PostgreSQL Database
           (Neon)
```

The system follows a client-server architecture where the frontend communicates with RESTful APIs developed using Express.js. Data is stored and managed through PostgreSQL hosted on Neon.

---

# Functional Requirements

The system implements the following business requirements:

| ID | Requirement                 |
| -- | --------------------------- |
| 1  | Room Catalog Management     |
| 2  | Room Rental Form Management |
| 3  | Customer Lookup             |
| 4  | Room Lookup                 |
| 5  | Invoice Generation          |
| 6  | Rental History Lookup       |
| 7  | Invoice Lookup              |
| 8  | Monthly Revenue Reporting   |
| 9  | Guest Statistics Reporting  |
| 10 | Hotel Regulation Management |

---

# Main Features

## Room Management

* Manage room categories and room information.
* Add, edit, and remove rooms.
* Configure room pricing.
* Track room occupancy status.

## Customer Management

* Store customer information.
* Search customers by name or identification number.
* Manage customer categories and affiliated organizations.
* View customer rental history.

## Rental Management

* Create rental forms.
* Assign multiple guests to a room.
* Update rental information.
* Process room check-in and check-out.

## Invoice Management

* Generate invoices automatically.
* Calculate room charges and surcharges.
* Search invoices by invoice ID, customer, or organization.
* View invoice details.

## Reporting & Statistics

* Monthly revenue reports.
* Guest volume reports.
* Hotel business monitoring.

## Regulation Management

* Configure surcharge coefficients.
* Manage customer-type surcharge policies.
* Update hotel business parameters dynamically.

## User & Permission Management

* Manage user accounts.
* Manage permission groups.
* Control access to system functions.

---

# Software Engineering Process

The project was developed following the Waterfall model:

1. Requirement Elicitation
2. Requirement Analysis
3. System Design
4. Software Implementation
5. Testing & Validation

Project deliverables include:

* Requirement Specification Document
* Data Flow Diagrams (DFD)
* Entity Relationship Diagram (ERD)
* Relational Database Design
* User Interface Design
* Test Cases
* Deployment Documentation

---

# Technology Stack

| Layer           | Technology              |
| --------------- | ----------------------- |
| Frontend        | HTML5, CSS3, JavaScript |
| Backend         | Node.js, Express.js     |
| Database        | PostgreSQL              |
| Cloud Database  | Neon                    |
| Deployment      | Render                  |
| Version Control | Git, GitHub             |

---

# Project Structure

```text
Hotel-Management-System
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── db/
│   └── server.js
│
├── frontend/
│   ├── css/
│   ├── js/
│   ├── pages/
│   └── assets/
│
├── database/
│
├── docs/
│
├── README.md
└── package.json
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/trinhnth23521662/Hotel-Management-System.git

cd Hotel-Management-System
```

## Install Dependencies

```bash
npm install
```

## Configure Environment Variables

```env
DATABASE_URL=your_database_url
PORT=3000
```

## Run Application

```bash
npm start
```

Development mode:

```bash
npm run dev
```

---

# Results

* Successfully implemented a complete hotel management workflow.
* Automated room rental and invoice processing.
* Built a configurable regulation management mechanism.
* Designed and deployed a full-stack web application.
* Applied software engineering methodologies from requirements analysis to deployment.

---

# Team Members

| Full Name            | Student ID |
| -------------------- | ---------- |
| Nguyễn Thị Huệ Trinh | 23521662   |
| Đinh Nguyễn Anh Thư  | 23521534   |
| Tou Prong Ma Tiêm    | 23521566   |

---

# Acknowledgements

This project was developed as part of the SE104 – Introduction to Software Engineering course at the University of Information Technology (UIT), Vietnam National University Ho Chi Minh City.
