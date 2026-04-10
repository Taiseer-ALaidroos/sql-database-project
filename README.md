# 🏥 Hospital Database Management System (SQL Project)

## 📌 Description
This project is a **Relational Hospital Database System** developed using SQL (Oracle SQL syntax).

It simulates a real hospital environment including patients, physicians, nurses, appointments, rooms, departments, medical procedures, prescriptions, admissions (stays), and hospital infrastructure.

The project focuses on relational database design, entity relationships, foreign keys, and real-world data modeling.

---

## 👨‍💻 Author
**Taiseer Al-Aidrous**  
Artificial Intelligence Student | Database & Systems Developer 🚀  

---

## 🗄️ Database Overview
The system contains multiple interconnected tables representing a hospital environment:

- PATIENT → patient information and PCP physician  
- PHYSICIAN → doctors and their roles  
- NURSE → nurse details and registration status  
- ROOM → hospital rooms  
- BLOCK → hospital structure (floors & blocks)  
- STAY → patient admission records in rooms  
- PROCEDURE → medical procedures and costs  
- UNDERGOES → links patient, procedure, physician, nurse, and stay  
- PRESCRIBES → prescriptions issued by physicians  
- APPOINTMENT → scheduling between patient, nurse, and physician  
- DEPARTMENT → hospital departments  
- CONNECTION → physician-department relationships  
- ON_CALL_NURSE → nurse availability schedule  
- TRAINED_IN → physician certifications  
- MEDICATION → drugs and medications used in treatment  

---

## ⚙️ Features
- Relational database schema design  
- Strong use of primary and foreign keys  
- Composite primary keys for relationship tables  
- Many-to-many relationship modeling  
- Real hospital workflow simulation  
- Scalable database structure  
- Oracle SQL compatible implementation  

---

## 🧠 Database Concepts Used
- Entity Relationship Design (ERD)
- Primary Keys & Foreign Keys
- Composite Keys
- Referential Integrity
- One-to-Many Relationships
- Many-to-Many Relationships
- Database normalization principles

---

## 🏗️ Project Structure
hospital-database/
├── schema.sql
├── inserts.sql
├── queries.sql
└── README.md

---

## ▶️ How to Run
1. Open Oracle SQL Developer or any SQL tool  
2. Create a new database schema  
3. Run the SQL file in correct order due to foreign key dependencies  
4. Execute:
   @schema.sql

---

## ⚠️ Important Notes
- Table creation order is important because of foreign keys  
- Some DATE fields are stored as VARCHAR2 for simplicity  
- This project is designed for educational purposes  
- Focus is on relational design and database modeling  

---

## 🚀 Future Improvements
- Add ERD diagram (visual representation of schema)
- Convert VARCHAR2 dates to proper DATE type
- Add triggers and stored procedures
- Implement user roles (Admin / Doctor / Nurse)
- Convert to MySQL or PostgreSQL
- Build backend API using Java or Python

---

## ⭐ License
This project is for educational purposes only.
