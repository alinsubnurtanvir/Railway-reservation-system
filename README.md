

#  Railway Reservation System

A database-focused course project developed for **CSE 321 – Database Systems** at **International Standard University (ISU)**. This project designs and documents a Railway Reservation System to manage train schedules, passenger records, ticket booking, and payment information efficiently.

---

##  Project Information

* **Project Title:** Railway Reservation System
* **Course Code:** CSE 321
* **Course Name:** Database Systems
* **Submitted By:** Al Insub Nur Tanvir
* **Student ID:** 096221005101004
* **Batch:** 6th
* **Submitted To:** Md. Wahiduzzaman
* **Submission Date:** 30 June 2024

---

## Objective

Bangladesh Railways is one of the most important transportation systems in the country. With rapid economic growth and a large number of passengers, manual ticketing systems became inefficient.
This project aims to design and develop a **computerized Railway Reservation System** that allows passengers to:

* Search available trains by source and destination
* Book and cancel tickets
* Check ticket status
* Manage passenger, train, and seat records

The system mainly focuses on **database design** to support online reservation and improve service efficiency.

---

##  Scope of Work

The project focuses on designing a **relational database system** for railway reservations. It includes:

* Entity Relationship (ER) Diagram
* Relational Database Schema
* Table structures with constraints
* Passenger, train, ticket, and payment management

### Key Features

*  Train schedule and seat availability checking
*  Online ticket booking and cancellation
* Payment processing (online/offline)
*  User and passenger information management

---

##  Database Tables Description

### 1. Customer

Stores passenger information such as name, date of birth, mobile number, and email.

* **Primary Key:** `doc_id`

### 2. Book

Manages ticket reservations and booking status.

* **Primary Key:** `book_no`
* **Foreign Key:** `doc_no`

### 3. Ticket

Stores ticket details including journey date and class.

* **Primary Key:** `ticket_no`

### 4. Train Status

Manages train seat availability, booked seats, and waiting list.

* **Primary Key:** `status_no`
* **Foreign Key:** `trn_no`, `tamta_no`

### 5. Train

Contains train information such as train number and name.

* **Primary Key:** `trn_no`
* **Foreign Key:** `status_no`

### 6. Time

Stores journey timing details including departure and destination.

* **Primary Key:** `tamta_no`
* **Foreign Key:** `station_no`, `trn_no`

### 7. Station

Stores station information.

* **Primary Key:** `station_no`

### 8. Payment

Stores payment transaction details such as card number, bank, and amount.

* **Primary Key:** `transaction_no`

---

##  ER Diagram & Schema Design

The project includes:

* Entity Relationship Diagram (ERD)
* Relational Database Schema
* Proper use of **Primary Keys** and **Foreign Keys**
* Normalized table design

(ER diagram and schema are documented in the project report.)

---

##  Conclusion

This project demonstrates how a well-designed database can significantly improve railway reservation services. The system reduces manual errors, improves booking efficiency, and enhances customer experience.
Future improvements may include expanding the system by adding more stations and real-time notification services.


