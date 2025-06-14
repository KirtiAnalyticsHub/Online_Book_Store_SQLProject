
# 📚 Online Bookstore SQL Project

This project simulates a mini online bookstore database using PostgreSQL. It includes table creation, data import (CSV), and 25+ practical SQL queries ranging from beginner to advanced.

## 📂 Project Structure

- `online_bookstore.sql`: Contains the full SQL script to create and query the database.

## 🧱 Database Schema

- **Books**: Stores book details
- **Customers**: Stores customer details
- **Orders**: Tracks customer purchases

## ✅ Features

- Create and manage bookstore tables
- Import data using `COPY`
- Filter, aggregate, and join data
- Get insights like:
  - Most ordered book
  - Top-spending customer
  - Remaining stock after sales

## 🚀 How to Use

1. Create the database:
   ```sql
   CREATE DATABASE OnlineBookstore;
   \c OnlineBookstore;
   ```
2. Run the script from `online_bookstore.sql` in your PostgreSQL client.

3. (Optional) Import CSVs using the `COPY` commands if data files are available.

## 📊 Sample Insights

- Total revenue generated
- Books sold per genre
- Customers with multiple orders

---
## Author - Kirti Analytics Hub
This project is part of my portfolio, showcasing the SQL skills essential for data analyst roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

Made with ❤️ for SQL practice and learning.
