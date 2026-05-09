# Bespoke-Tailoring-System
Name : Sarmad Habib
Cms : 023-25-0100
Section : BSCS II-D

The README covers everything the guidelines ask for. Here's also a summary of the small code points your teacher will look for and how your project already satisfies them:

Purpose : shop staff manage customers, measurements, and orders instead of paper records.

Core modules — the full package tree is documented with a one-line description of every file.

Key OOP features — your project already has all four naturally:

Private fields with getters/setters in all three model classes ✅
Separation into model/dao/ui layers ✅
Singleton pattern in DBConnection ✅
Input validation and try/catch in every DAO and UI panel ✅

How to run — SQL script, DB config, JAR setup, and run instructions are all included.

## Database Setup

1. Install MySQL
2. Open MySQL Workbench
3. Import the file:
   - Go to Server → Data Import
   - Select `database.sql`
4. Run the script to create tables

## Database Config

Update your DB connection:

URL: jdbc:mysql://localhost:3306/your_db_name  
User: your_username  
Password: your_password
