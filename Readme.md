Hospital Management System

Project Overview

The Hospital Management System is a real-life scenario-based desktop
application developed for the CSC2210: Object Oriented Programming 2
course at American International University–Bangladesh (AIUB).

The project demonstrates the use of C#, a Graphical User Interface
(GUI), and database integration to manage different activities of
a hospital.

Academic Information

• University: American International University–Bangladesh (AIUB)
• Department: Computer Science
• Course: CSC2210: Object Oriented Programming 2
• Semester: Summer 2025–2026
• Section: R
• Group: 0012
• Project: Hospital Management System
• Supervisor: Dr. Md. Iftekharul Mubin

Group Members

1. S M Taj Ahmed — 24-59219-3
2. MD.Shaiyan Bean Omar — 24-60126-3
3. Redwan Mohd Mukles — 24-60102-3

Main Objectives

The project is designed to:

• Demonstrate a real-life OOP-based application.
• Provide a graphical user interface for hospital-related operations.
• Integrate application forms with a database.
• Manage patients, doctors, nurses, receptionists, pharmacists,
cashiers, rooms, beds, bills, and payments.
• Provide role-based access after login.
• Support data validation, verification, and database operations.

User Roles

The report identifies the following roles:

• Admin
• Doctor
• Nurse
• Receptionist
• Pharmacist
• Lab Technician
• Accountant
• Patient

Main Functionalities

According to the project report, the system supports the following
functions:

1. Users can log in and access the system according to their role.
2. Patients can register and manage their personal information.
3. Patients can book, cancel, or reschedule appointments with available
doctors.
4. Doctors can view patients and medical history, add diagnoses,
prescribe medicines, and request laboratory tests.
5. Laboratory technicians can receive test requests and enter test
results.
6. Pharmacists can manage medicines and stock and dispense medicines
according to prescriptions.
7. Nurses can manage admitted patients, including vital signs,
medication administration, and nursing notes.
8. The system can manage hospital admissions, rooms, and beds.
9. Accountants can generate bills and manage payments for hospital
services.
10. Patients can view medical records, prescriptions, laboratory
results, appointments, bills, and payment history.
11. Admin can manage users, doctors, staff, patients, departments,
rooms, medicines, appointments, and hospital records.
12. Admin can deactivate or remove users, doctors, staff, or other
records when necessary.

Database

The report contains database tables for:

• System_User
• Admin
• Patient
• Doctor
• Doctor_Patient
• Receptionist
• Nurse
• Cashier
• Pharmacist
• Rooms
• Beds
• Bills
• Payment

Important relationships include:

• Doctor_Patient connects doctors and patients.
• Receptionist references Patient.
• Beds references Rooms.
• Bills references Patient.
• Payment references both Bills and Cashier.

The report’s SQL uses database definitions such as primary keys, foreign
keys, unique constraints, and data types.

Database Query Examples

The report includes verification queries such as:

```sql
SELECT * FROM System_User;
SELECT * FROM Doctor;
SELECT * FROM Patient;
SELECT * FROM Room;
SELECT * FROM Bed;
```

GUI

The project report includes a login interface and role-selection
interfaces. After selecting the staff option, users can select a role
such as Doctor, and an Admin option is also available.

The GUI is intended to provide a simple and user-friendly way to access
the hospital management functions.

Project Structure in the Report

The report is organized into the following chapters:

1. Chapter 01 — Introduction
2. Chapter 02 — User Story
3. Chapter 03 — Functionality
4. Chapter 04 — SQL Queries
5. Chapter 05 — ER Diagram
6. Chapter 06 — Login Interface

Learning Outcomes

This project demonstrates the course requirements related to:

• Real-life project development
• Object-Oriented Programming
• C# GUI development
• Database representation and integration
• Data validation
• Data verification
• Functional requirement implementation
• ER diagram and relational database concepts
