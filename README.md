# Hotel Management System

A comprehensive Hotel Management System developed as part of the **SE104 – Introduction to Software Engineering** course at the University of Information Technology (UIT – VNUHCM).

The project was built following the **Waterfall Software Development Life Cycle (SDLC)**, covering requirement analysis, system modeling, database design, implementation, testing, and deployment.

## Overview

Managing hotel operations manually becomes increasingly difficult as the number of guests, rooms, and transactions grows. This project aims to digitalize hotel management activities, enabling hotel staff to efficiently manage room inventories, customer information, room rentals, invoices, business regulations, and monthly reports through a centralized web-based system.

## Key Features

### Room Management

* Manage room categories and room information
* Add, update, and remove rooms
* Configure room pricing
* Track room status and availability

### Customer Management

* Store customer information
* Search customers by name or ID card number
* Manage customer categories and affiliated organizations
* View rental history of customers

### Room Rental Management

* Create rental forms
* Assign multiple guests to a room
* Update rental information
* Check-in and check-out processing
* Rental history tracking

### Invoice Management

* Generate payment invoices
* Calculate room charges automatically
* Apply surcharges based on hotel regulations
* Search invoices by invoice ID, customer, or paying organization
* View invoice details

### Reports & Statistics

* Monthly revenue reports
* Guest volume reports
* Business performance monitoring

### Hotel Regulation Management

* Manage customer type surcharges
* Configure occupancy surcharge coefficients
* Update hotel business parameters
* Maintain flexible business rules without modifying source code

### User & Permission Management

* User account management
* Role and permission group management
* Authorization for system functions

## Functional Requirements

The system implements 10 core business requirements:

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

## System Modules

* Authentication & Authorization
* Room Management
* Room Type Management
* Customer Management
* Organization Management
* Rental Management
* Invoice Management
* Reporting & Statistics
* User Management
* Regulation Management

The system consists of more than 25 user interfaces supporting the complete hotel operation workflow.

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### Backend

* Node.js
* Express.js

### Database

* PostgreSQL
* Neon Database

### Deployment

* Render

## Software Engineering Artifacts

During development, the following software engineering artifacts were produced:

* Requirement Specification
* Data Flow Diagrams (DFD)
* Entity Relationship Diagram (ERD)
* Relational Database Schema
* User Interface Design
* Functional Specifications
* Test Cases
* Deployment Documentation

## Development Process

The project follows the Waterfall model:

1. Requirement Elicitation
2. Requirement Analysis
3. System Design
4. Software Implementation
5. Testing & Validation

Testing activities include:

* Unit Testing
* Integration Testing
* User Acceptance Testing (UAT)
* System Evaluation

## Database Design

Main entities include:

* RoomType
* Room
* Customer
* CustomerType
* Organization
* RentalForm
* RentalDetail
* Invoice
* UserAccount
* PermissionGroup
* Regulation
* MonthlyReport

The database is designed using normalization principles to ensure consistency and efficient data retrieval.

## Installation

### Clone Repository

```bash
git clone https://github.com/trinhnth23521662/Hotel-Management-System.git
cd Hotel-Management-System
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
DATABASE_URL=your_database_url
PORT=3000
```

### Run Application

```bash
npm start
```

Development mode:

```bash
npm run dev
```

## Live Demo

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://trinhnth23521662.github.io/Hotel-Management-System/)


## Academic Information

**Course:** SE104 – Introduction to Software Engineering

**University:** University of Information Technology (UIT) – Vietnam National University Ho Chi Minh City

## Future Improvements

* Online booking portal for customers
* Responsive mobile interface
* Email notification system
* Dashboard analytics and visualization
* Export reports to PDF/Excel
* Multi-branch hotel support

## License

This project was developed for educational and research purposes.
