# Kazanci Holding Auditing Database Project

## Overview
This repository contains the project report and implementation details for the Kazanci Holding Auditing Database Project. The project was undertaken by Group 4 for the Management of Organizational Data course, taught by Professor Yang in Fall Module 1. The primary goal was to design and implement a normalized database for the Kazanci Holding Auditing Department to store and manage audit-related data systematically.

## Project Team
- Liana Simopoulos
- Harshraj Jadeja
- Ridvan Kanca
- Sahana Reddy
- Anton De Franco
- Cole Wesley

## Table of Contents
1. [Background](#background)
2. [Data](#data)
3. [Goals and Objectives](#goals-and-objectives)
4. [Conceptual Data Model](#conceptual-data-model)
5. [Relational Data Model](#relational-data-model)
6. [Database Implementation](#database-implementation)
7. [Conclusion](#conclusion)

## Background
Kazanci Holding is a global energy conglomerate headquartered in Turkey, with over 10,000 employees and operations across four continents. The company’s auditing department conducts internal audits across all its facilities and sectors. This project aims to design a database to store audit results more systematically, improving the efficiency and effectiveness of the auditing process.

## Data
The data for this project comes directly from Kazanci Holding, ensuring high accuracy and relevance. Due to a Non-Disclosure Agreement (NDA) signed with the company, the specific data and company details cannot be shared publicly. The database includes information on auditors, audit reports, audit findings, processes, sub-processes, and timesheets submitted by employees. Accurate data collection is crucial in the energy sector to identify and mitigate potential risks effectively.

## Goals and Objectives
The primary objective is to create a normalized database to minimize data redundancy and optimize the reporting process for the auditing department. This database will provide a robust, centralized, and secure platform for data management and analysis, enhancing decision-making, operational efficiency, and regulatory compliance. The goals include reducing data redundancy, minimizing costs, and increasing ROI by providing insights into auditor performance and audit findings.

## Conceptual Data Model
The database design includes six main tables and two associative tables to link data and minimize redundancy. The main tables are Auditor, Audit_Report, Finding, Process, Sub_Process, and Timesheet. The associative tables are Auditor_Report and Audit_Process. This design ensures efficient data storage and retrieval, supporting comprehensive audit analysis.

## Relational Data Model
The relational data model, derived from the conceptual data model, demonstrates the linkages between tables. Primary keys uniquely identify each row, while foreign keys link data across tables. The database adheres to the Third Normal Form (3NF), ensuring data integrity and minimizing redundancy.

## Database Implementation
The implementation involved creating tables using DDL statements, cleaning and formatting data with Tableau Prep, and loading data into the database. The SQL file `Group#4CreateTables.sql` contains the DDL statements, and `Group#4queries.sql` contains queries for data analysis. The database was designed to ensure efficient data management and support complex queries needed by the auditing department.

## Conclusion
The project successfully created a normalized database with minimal data redundancy, allowing Kazanci Holding to efficiently query and analyze audit data. The optimized database and SQL queries enhance the auditing department’s capabilities, supporting better-informed business decisions and improving overall efficiency.

For more detailed information, refer to the [project report](Group%204%20Project%20Report.pdf).
