# 🌌 Celestial Bodies Database

This project is part of the **freeCodeCamp Relational Database Certification**.

It is a PostgreSQL database that models celestial bodies such as galaxies, stars, planets, and moons, with proper relationships and constraints.

---

## 🚀 Project Description

The goal of this project is to build a relational database using **PostgreSQL** that represents the universe structure.

It includes:

- Galaxies
- Stars
- Planets
- Moons

Each table has:
- Primary keys
- Foreign keys
- Constraints (UNIQUE, NOT NULL)
- Different data types (INT, TEXT, BOOLEAN, NUMERIC)

---

## 🧱 Database Structure

### Tables:
- galaxy
- star
- planet
- moon
- galaxy_type (extra table to satisfy project requirements)

---

## 🔗 Relationships

- A galaxy can have many stars
- A star can have many planets
- A planet can have many moons
- Each relationship is enforced using foreign keys

---

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- freeCodeCamp environment
- Git & GitHub

---

## 📁 File Included

- `universe.sql` → database dump used to rebuild the full database

---

## 📌 How to Rebuild the Database

Run the following command:

```bash
psql -U postgres < universe.sql
