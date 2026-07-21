# JDMart Order Management Database System

## Week 1 – Understanding the Business Problem

### Project Title
E-Commerce Order Management Database System

---

## Project Overview

This project is developed as part of the Database Management System course. The objective is to analyze the business requirements of an E-Commerce Order Management System and prepare the necessary requirement documents before designing the database.

The proposed system manages customer registration, product management, inventory tracking, order processing, payment management, shipment tracking, and customer reviews using a centralized database.

---

## Project Objectives

- Analyze the business requirements of the system.
- Identify stakeholders and their responsibilities.
- Study the business processes.
- Define functional and non-functional requirements.
- Define project scope.
- Identify assumptions and constraints.
- Prepare a Software Requirement Specification (SRS).
- Create the foundation for database design.

---

## Business Scenario

A rapidly growing e-commerce company requires a centralized database system to efficiently manage its daily business operations. The system should support customer registration, product management, inventory tracking, order processing, payment management, shipment tracking, and customer reviews while reducing data redundancy and improving operational efficiency.

---

## Core Entities

- Customer
- Category
- Product
- Supplier
- Order
- Order Details
- Payment
- Shipment
- Review

> Note: Only the predefined entities provided in the project statement are used.

---

## Deliverables

- Requirement Analysis Report
- Business Requirement Document (BRD)
- Stakeholder Analysis
- Functional Requirements
- Non-Functional Requirements
- Project Scope
- Assumptions and Constraints
- Software Requirement Specification (SRS)

---

## Repository Structure

```
Week1/
│── Requirement_Analysis_Report.pdf
│── Business_Requirement_Document.pdf
│── SRS_Document.pdf
│── README.md
```

---

## Functional Modules

- Customer Management
- Category Management
- Product Management
- Supplier Management
- Order Management
- Payment Management
- Shipment Tracking
- Customer Review Management

---

## Technologies Used

- Documentation (Microsoft Word)
- PDF
- Git
- GitHub



# Week 2 – Entity and Relationship Analysis

## Project Title
**E-Commerce Order Management Database System**

## Overview
This repository contains the Week 2 deliverables for the E-Commerce Order Management Database System project. The documents analyze the database entities, their attributes, primary keys, foreign keys, relationships, and cardinality based on the Software Requirement Specification (SRS) prepared in Week 1.

## Contents

### 1. Entity_Analysis_Report.pdf
Includes:
- Entity Identification
- Entity Attribute List
- Primary Keys (PK)
- Foreign Keys (FK)
- Database Constraints (NOT NULL, UNIQUE, CHECK, DEFAULT)

### 2. Entity_Relationship_Analysis.pdf
Includes:
- Relationship Analysis
- One-to-One (1:1)
- One-to-Many (1:M)
- Many-to-One (M:1)
- Many-to-Many (M:M)
- Cardinality Analysis
- Relationship Summary

## Project Objective
To design a structured and normalized database for an E-Commerce Order Management System by identifying entities, defining relationships, and maintaining data integrity.

## Tools Used
- Microsoft Word
- PDF
- GitHub



  # E-Commerce Order Management Database System

## Week 3 – Entity Relationship (ER) Diagram and Relational Schema Design


## Project Description

The E-Commerce Order Management Database System is designed to manage the complete online shopping process. It stores customer information, product details, categories, suppliers, orders, payments, shipments, and customer reviews. The system ensures proper data organization and maintains relationships between different entities.

---

## Week 3 Objective

The objective of Week 3 is to design the **Entity Relationship (ER) Diagram** and convert the conceptual model into a **Relational Schema**. This logical database design will be used for database implementation in the upcoming weeks.

---

## Deliverables

This folder contains the following files:

- **ER_Diagram.png** – Entity Relationship Diagram of the E-Commerce Order Management Database System.
- **Relational_Schema.pdf** – Relational schema showing all tables with Primary Keys and Foreign Keys.
- **ER_Design_Report.pdf** – Detailed report explaining the ER Diagram, relationships, cardinality, participation constraints, and relational schema.
- **README.md** – Project documentation.

---

## Entities Used

- Customer
- Category
- Supplier
- Product
- Orders
- OrderDetails
- Payment
- Shipment
- Review

---

## Relationships

- Customer → Orders (One-to-Many)
- Category → Product (One-to-Many)
- Supplier → Product (One-to-Many)
- Orders → OrderDetails (One-to-Many)
- Orders → Payment (One-to-One)
- Orders → Shipment (One-to-One)
- Customer → Review (One-to-Many)
- Product → Review (One-to-Many)
- Orders ↔ Product (Many-to-Many through OrderDetails)

---

## Tools Used

- Draw.io / ER Diagram Tool
- Microsoft Word
- Microsoft PowerPoint / PDF Converter
- GitHub

---

## GitHub Folder Structure

```
Week3/
│── ER_Diagram.png
│── Relational_Schema.pdf
│── ER_Design_Report.pdf
│── README.md
```

---

## Learning Outcome

- Designed an Entity Relationship (ER) Diagram.
- Identified entities, attributes, primary keys, and foreign keys.
- Defined relationships and cardinality.
- Converted the ER model into a Relational Schema.
- Prepared documentation suitable for database implementation.

---

## Conclusion

The ER Diagram and Relational Schema provide a clear logical structure for the E-Commerce Order Management Database System. The design minimizes data redundancy, maintains referential integrity, and serves as the foundation for implementing the database in future project phases.







