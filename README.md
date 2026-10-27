# Distribution Management System (Legacy FoxPro Application)

## Overview

This project is a legacy Distribution Management System developed using FoxPro. It is designed to support the day-to-day operations of a distribution company, including sales, purchases, inventory management, and the collection and reconciliation of sales proceeds by salesmen.

The system follows a daily business cycle in which salesmen are responsible for collecting payments from customers against their sales. At the end of the business day, the company completes its daily closing process after all salesmen have submitted their collected cash to the company.

The application provides a structured approach to managing distribution activities and maintaining business records using a file-based database architecture.

## Key Features

### 1. Sales Management
- Record and process sales transactions.
- Maintain sales records for daily distribution operations.
- Support the tracking of sales transactions associated with salesmen.
- Facilitate the monitoring of sales proceeds collected by salesmen.

### 2. Purchase Management
- Record purchase transactions.
- Maintain purchase records for inventory replenishment.
- Support stock updates resulting from purchases.

### 3. Stock and Inventory Management
- Maintain inventory records using DBF database files.
- Track stock movements associated with purchases and sales.
- Support inventory control as part of routine distribution operations.

### 4. Salesman Cash Collection
- Salesmen are responsible for collecting payments against their sales.
- Record and monitor the submission of collected cash to the company.
- Support the reconciliation of sales proceeds and cash received from salesmen.

### 5. Daily Business Closing
- The company follows a daily closing procedure.
- Daily closing is performed after all salesmen have submitted their collected cash.
- This process helps ensure that the day's sales collection activities are accounted for before the business day is finalized.

## Technology Stack

The application is built on legacy FoxPro technology and uses the following file types:

| File Extension | Purpose |
|---|---|
| `.DBF` | Database files containing business data and records. |
| `.PRG` | FoxPro program files containing application logic, processing routines, and form-related code. |
| `.RP1` | Legacy report-writer files used for report definitions and report generation. |

### Architecture

The application uses a file-based database structure, with DBF files for data storage, PRG files for program logic, and RP1 files for reporting.

This structure reflects a traditional FoxPro application architecture commonly used in business management systems before the widespread adoption of modern relational database servers and web-based applications.

## Business Workflow

The system supports the following general business workflow:

1. **Purchasing:** Purchase transactions are recorded and inventory is updated.
2. **Sales Processing:** Sales transactions are entered and processed.
3. **Stock Management:** Inventory records reflect relevant stock movements.
4. **Salesman Collection:** Salesmen collect payments from customers against their sales.
5. **Cash Submission:** Salesmen submit their collected cash to the company.
6. **Daily Closing:** The company closes the business day after all salesmen have submitted their cash.

This workflow supports the coordination of sales, inventory, and cash collection activities within a distribution business.

## Project Structure

The project consists primarily of the following types of files:

```text
distribution-management-system/
├── *.DBF    # Database and business data files
├── *.PRG    # Application programs and processing logic
├── *.RP1    # Report-writer definitions
└── README.md
```

*Note: This is an illustrative structure. Actual filenames, directories, and additional files may vary depending on the original project.*

## Project Purpose

This repository preserves a legacy business application that was developed to address practical operational requirements in the distribution industry.

The project may be useful for:

- Understanding legacy FoxPro application architecture.
- Studying distribution business workflows.
- Examining traditional file-based data management.
- Analyzing legacy business software for maintenance or modernization.
- Evaluating potential migration to modern database and application platforms.

## Legacy System Considerations

As a legacy FoxPro application, the system may require a compatible FoxPro environment to run, maintain, or modify its original program and report files.

Modernization or migration may involve:
- Reviewing existing business rules and transaction-processing logic.
- Mapping DBF files and their relationships.
- Analyzing sales, purchase, inventory, and cash collection workflows.
- Reproducing existing reports and daily closing procedures.
- Migrating business data to a modern database platform.

## License and Ownership

The licensing and usage terms for this project should be established by the repository owner.

Unless otherwise specified, no license to use, modify, distribute, or commercially exploit this software should be assumed solely from its availability in this repository.

---

**Project Type:** Legacy Business Management Software  
**Industry:** Distribution and Wholesale Operations  
**Technology:** FoxPro, DBF, PRG, RP1  
**Primary Functions:** Sales, Purchases, Inventory, Salesman Cash Collection, Daily Closing
