RIKA Drugstore Pharmacy Management System

Database Design

The RIKA Drugstore Pharmacy Management System is a proposed web-based pharmacy management project. This repository focuses on the design and development of the MySQL database that will support the system.

Project Overview

The database is designed to organize pharmacy-related records, including user accounts and roles, patient information, prescribers, prescriptions, medication details, dispensing transactions, suppliers, purchase orders, inventory batches, stock movements, and sales.

The project emphasizes relational database design, data integrity, and structured data management through primary keys, foreign keys, unique constraints, and related table relationships.

Database Features

User accounts and role management

Administrator, pharmacist, and pharmacy assistant profiles

Patient records and allergy information

Prescriber information

Medication categories and measurement units

Medication and prescription management

Prescription safety alerts

Supplier and purchase order records

Inventory batch and expiration tracking

Dispensing logs and dispensing items

Stock-in and stock movement records

Sales and sale item records

Audit logs for recorded user activities

Database Technology

Database Management System: MySQL

Database Engine: InnoDB

Database Design: Relational database

Character Set: utf8mb4

Repository Contents

RIKA-Drugstore-Pharmacy-Management-System/
├── RIKA_Pharmacy_Schema_Only.sql
└── README.md

The SQL file contains the database creation statement, 26 table definitions, and primary-key and foreign-key constraints. It does not contain sample records or INSERT statements.

Project Status

This repository contains the database component of the proposed RIKA Drugstore Pharmacy Management System. It includes the MySQL database structure and relationships. The frontend and backend application are not included in this repository.

Purpose

The database serves as the foundation for the proposed RIKA Drugstore Pharmacy Management System, supporting organized pharmacy record management and future system development.

