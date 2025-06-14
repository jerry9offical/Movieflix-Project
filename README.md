# 🎬 MovieFlix SQL Data Analysis Project

This project explores the **MovieFlix** DVD rental database using SQL to extract business insights related to customer behavior, movie rentals, and revenue patterns.

## 🔍 Project Overview

**MovieFlix Rentals** is a fictional DVD rental service managing customer data, movie inventory, and payment transactions. This analysis helps answer key business questions using SQL, improving data-driven decision-making.

---

## 📊 Objectives

- Retrieve key information on movies, rentals, and customers
- Analyze revenue generated per staff and per store
- Classify customers by spending behavior
- Identify top-performing movies and employees
- Discover store performance and operational efficiency

---

## 🧰 Technologies Used

- PostgreSQL
- SQL (JOIN, GROUP BY, CASE, WHERE, etc.)
- PgAdmin (optional)
- PowerPoint (for presentation)
- GitHub (documentation)

---

## 📁 Database Schema (Core Tables)

- `film`: movie catalog
- `customer`: customer details
- `payment`: transaction details
- `rental`: rental activity
- `inventory`: stock info
- `staff`: employee data

---

## 📌 Key SQL Tasks

| Task | Description |
|------|-------------|
| Movies | List all movies, rental durations, ratings |
| Revenue | Revenue per staff, store, and late fees |
| Customer Insights | Spending tiers (low, mid, high) |
| Rentals | Top 10 most rented movies |
| Integrity Check | Payments with no rentals |
| Store Ops | Avg rental duration per store |

---

## 📈 Insights & Outcomes

- Most customers are **low spenders (< $70)** – potential upselling opportunity.
- Staff revenue varies – some outperform others significantly.
- Certain stores have **longer average rental durations** – insight into customer behavior.
- 10 movies dominate rentals – opportunity to promote similar genres.

---

## 🚀 How to Run

1. Restore the MovieFlix database into PostgreSQL
2. Open the `.sql` script provided
3. Run queries using your preferred SQL editor
4. Use insights for visualization (PowerPoint/BI tools)

---

## ✅ Future Improvements

- Integrate with Power BI or Tableau
- Build stored procedures for frequent reports
- Create dashboards for staff/store-level monitoring

---

## 🧠 Author

Amadi Jerry Godspower – Data Scientist  
