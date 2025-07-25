📘 SQL Projects: Hospital & Sports Tournament Management
🚀 Overview
This repository contains two SQL-based database projects designed for educational and practical purposes:

Hospital Management System – A database solution for managing patients, doctors, visits, billing, and reporting.

Sports Tournament Management – A database for managing teams, players, matches, stats, and leaderboards.

Both projects are compatible with MySQL 5.x and older versions (no window functions used), making them suitable for students and institutions with legacy database systems.

🧠 Purpose & Motivation
To demonstrate real-world database design with normalized tables.

Help students understand queries, triggers, views, stored procedures, and aggregate functions.

Provide sample datasets and ready-to-use analytical queries for reporting.

📋 Project Structures
1. Hospital Management System
Tables:

Patients – Patient information.

Doctors – Doctor details and specialization.

Visits – Appointment and diagnosis data.

Bills – Billing, charges, and payment status.

Key Features:

Stored procedures for billing calculations.

Triggers for auto-updating visit status upon payment.

Queries for appointments, payments, and revenue reports.

2. Sports Tournament Management
Tables:

Teams – Team information.

Players – Player details linked to teams.

Matches – Match results with scores and winners.

Stats – Player performance per match.

Key Features:

Views for player leaderboards and team points.

Aggregate queries for runs, wickets, and averages.

Export match data and team points to CSV files.

⚙ Setup Instructions
Initialize a new MySQL database for each project.

Run the respective CREATE DATABASE and table creation scripts from:

project1.sql – Hospital Management System.

project2.sql – Sports Tournament Management.

Insert sample data using the provided INSERT INTO statements.

Execute analytical queries and views for reporting.

✅ Features & Highlights
Hospital Project: Appointment management, billing automation, and visit reports.

Sports Project: Leaderboards, team rankings, and player performance summaries.

Sample queries, triggers, and procedures for automation and analytics.

Legacy-friendly SQL (MySQL < 8.0 compatible).

📦 Tools & Technologies
Component	Details
SQL Version	MySQL 5.x or earlier
Client Tools	MySQL Workbench, DBeaver, phpMyAdmin
Output	CSV, PDF, or Word for reports

🎯 Target Audience
Students learning SQL and database fundamentals.

Institutions needing a lightweight result/management system.

Developers exploring stored procedures, triggers, and views.

🧱 Project Contents
project1.sql – Hospital Management SQL script.

project2.sql – Sports Tournament SQL script.

Sample data inserts and queries for analytics.

README (this document).

📈 Future Enhancements
Hospital: Advanced reporting and appointment scheduling UI.

Sports: Support for tournaments with knockout/league structures.

Integration with web dashboards or analytics visualization tools.

📝 Notes & Contributing
Follows SQL best practices (naming conventions, formatting).

Contributions (e.g., additional queries, dashboards) are welcome.

📄 License & Credits
Open-source (MIT or GPL recommended).

Acknowledge contributors or educational affiliations.
