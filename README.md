# 🏥 Clinic Booking System – MySQL Database Project

## 📌 Project Title

**Clinic Booking System**

## 📄 Description

This project implements a complete relational **Clinic Booking System** using MySQL. It is designed to manage day-to-day clinical operations including patient management, doctor records, appointment scheduling, treatment tracking, and medication prescriptions.

The system uses proper relational database design principles and supports:

* One-to-many and many-to-many relationships
* Cascading deletions and updates for referential integrity
* Indexing for optimized queries

## 🚀 How to Set Up / Run

### Prerequisites:

* MySQL Server (8.0 or compatible)
* A MySQL client (e.g., MySQL Workbench, DBeaver, phpMyAdmin, or CLI)

### Setup Steps:

1. **Create a new database:**

```sql
CREATE DATABASE ClinicDB;
USE ClinicDB;
```

2. **Run the SQL script:**

```sql
SOURCE path/to/ClinicDbSchema.sql;
```

> Replace `path/to/ClinicDbSchema.sql` with the actual file path on your computer.

## 📸 ERD (Entity-Relationship Diagram)

* View the ERD here: \[Insert Link to ERD Image or PDF]
* Or include a file like `ERD.png` or `ERD.pdf` in your repo

## 📂 Files Included

* `ClinicDbSchema.sql` – SQL script for schema creation
* `README.md` – Project documentation
* *(Optional)* `ERD.png` or `ERD.pdf` – Entity Relationship Diagram

## 💡 Database Tables Overview

| Table           | Purpose                                 |
| --------------- | --------------------------------------- |
| `Patients`      | Stores patient personal information     |
| `Doctors`       | Stores doctor contact and specialty     |
| `Appointments`  | Links patients and doctors with reasons |
| `Treatments`    | Details medical treatments and cost     |
| `Medications`   | Catalogs available medications          |
| `Prescriptions` | Prescribes medications for treatments   |

## 🔧 Example Use Case

A clinic receptionist books an appointment between a doctor and a patient. After the consultation, the treatment is recorded and any medications are prescribed through the system. Each action is stored and traceable in the database.

## ✅ Project Status

Complete and ready for deployment or extension.

