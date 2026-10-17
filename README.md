
# 🏆 Sports Tournament Management System

## 📌 Project Overview

The **Sports Tournament Management System (STMS)** is a database-driven project developed to organize and manage sports tournament activities efficiently. It provides a structured approach to handling users, roles, teams, players, tournaments, matches, and match results through an Oracle database.

The project focuses on maintaining organized tournament information, managing relationships between database entities, and implementing database operations using SQL and PL/SQL.

This project was developed as part of the **Advanced Database Management System (ADBMS)** course.

---

## 🎯 Project Objectives

The main objectives of this project are:

- To centralize tournament-related information within a database.
- To reduce manual work and minimize data entry errors.
- To maintain data accuracy, consistency, and integrity.
- To implement role-based user management.
- To organize team and player information.
- To manage team registrations for tournaments.
- To organize match schedules and related information.
- To store and manage match results.
- To demonstrate database design and SQL/PLSQL implementation.
- To provide documentation of the system through diagrams and project reports.

---

## 👥 User Roles

The system is designed around the following user roles:

| Role | Responsibilities |
| :--- | :--- |
| **System Administrator** | Manages users and organizers. |
| **Tournament Organizer** | Creates and manages tournament information. |
| **Team Captain** | Manages team and player information. |
| **Viewer** | Views tournament match results. |

---

## ⚙️ Key Features

### 🔐 User and Role Management
- User registration and management.
- Role-based user organization.
- Support for multiple phone numbers associated with a user.

### 🏆 Tournament Management
- Creation and management of tournament information.
- Storage of tournament start and end dates.
- Association of organizers with tournaments.

### 👥 Team Management
- Creation and maintenance of team profiles.
- Assignment of team captains.
- Storage of team coach information.
- Registration of teams for tournaments.

### ⚽ Player Management
- Management of player information.
- Association of players with their respective teams.
- Maintenance of structured player records.

### 📅 Match Management
- Management of tournament matches.
- Storage of match dates, times, and venues.
- Tracking of match status.
- Association of matches with participating teams and tournaments.

### 🥇 Result Management
- Storage of home-team and away-team scores.
- Maintenance of match result information.
- Association of results with their respective matches.
- Support for viewing match results.

---

## 🗄️ Database Architecture and Design

The project uses an Oracle database to organize tournament-related data and their relationships.

### Main Entities

- `Role`
- `Users`
- `UserPhone`
- `Tournament`
- `Team`
- `Player`
- `Match`
- `Result`

### Relationship Tables

- `Organize`
- `Register`
- `Play`
- `Views`

### Key Database Relationships

- **Role and Users:** One role can be assigned to multiple users.
- **Users and UserPhone:** A user can have multiple phone numbers.
- **Organize:** Connects organizers with the tournaments they manage.
- **Register:** Represents team registrations for tournaments.
- **Team and Player:** A team can contain multiple players.
- **Tournament and Match:** A tournament can consist of multiple matches.
- **Play:** Represents the relationship between matches and participating teams.
- **Match and Result:** Match results are associated with their respective matches.
- **Views:** Represents the relationship between viewers and match results.

---

## 🛠️ Technologies Used

- **Database Management System:** Oracle Database
- **Query Language:** SQL
- **Procedural Database Language:** PL/SQL
- **Database Concepts:** Relational Database Design, Entity Relationships, and Data Integrity
- **Documentation:** Markdown and PDF
- **Version Control:** Git and GitHub

---

## 📊 System Diagrams

The `diagrams/` directory contains the visual documentation of the system:

- **Class Diagram** — illustrates the system's classes and their relationships.
- **Use Case Diagram** — represents the system's users and their interactions.
- **Activity Diagram** — illustrates the flow of system activities.
- **ER Diagram** — represents the database entities and their relationships.
- **Schema Diagram** — presents the database schema and table relationships.

### Available Diagrams

- [Class Diagram](<diagrams/class diagram.png>)
- [Use Case Diagram](<diagrams/Use case diagram.png>)
- [Activity Diagram](<diagrams/Activitydiagram.png>)
- [ER Diagram](<diagrams/ER Diagram (3).png>)
- [Schema Diagram](<diagrams/Schemadiagram.png>)

---

## 📑 Project Reports

The `report/` directory contains the project's academic documentation.

- **Final Term Project Report:** [ADBMS_FinalTermProject_Group4.pdf](report/ADBMS_FinalTermProject_Group4.pdf)
- **Midterm Project Report:** [ADMS_MidTermProject_Group4.pdf](report/ADMS_MidTermProject_Group4.pdf)

The reports provide supporting documentation for the project, while the diagrams illustrate the system design and database structure.

---

## 📂 Repository Structure

```text
Sports-Tournament-Management-System-Oracle/
│
├── README.md
├── LICENSE
│
├── diagrams/
│   ├── Activitydiagram.png
│   ├── class diagram.png
│   ├── ER Diagram (3).png
│   ├── Schemadiagram.png
│   └── Use case diagram.png
│
├── queries/
│   └── STMS_PL_SQL_Queries.txt
│
└── report/
    ├── ADBMS_FinalTermProject_Group4.pdf
    └── ADMS_MidTermProject_Group4.pdf
```

---

## 🚀 Getting Started

To explore the project:

1. Clone or download this repository from GitHub.
2. Open the project folder in Visual Studio Code or another suitable editor.
3. Review the `README.md` file to understand the project overview and design.
4. Explore the `diagrams/` directory to examine the system and database diagrams.
5. Open `queries/STMS_PL_SQL_Queries.txt` to review the SQL and PL/SQL queries.
6. Open the `report/` directory to access the final-term and midterm project reports.

To execute the database queries, configure an Oracle Database environment and run the relevant SQL/PLSQL statements using a compatible Oracle database tool.

---

## 🎓 Academic Information

**Project Title:** Sports Tournament Management System  
**Course:** Advanced Database Management System (ADBMS)  
**Project Group:** Group 4

---

## 📜 License

This project is distributed under the MIT License. Refer to the [`LICENSE`](LICENSE) file for the license terms.
