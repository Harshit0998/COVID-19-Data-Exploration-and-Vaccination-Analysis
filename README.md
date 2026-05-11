Here’s a clean, professional **README.md** you can paste directly into your GitHub repo for your **COVID-19 Data Exploration using SQL** project.

---

# 🦠 COVID-19 Data Exploration using SQL

This project explores global COVID-19 data using **SQL** to extract meaningful insights about cases, deaths, infection rates, and vaccination trends across countries and continents.

The goal of this project is to demonstrate practical SQL skills including:

* Joins
* CTEs (Common Table Expressions)
* Temporary Tables
* Window Functions
* Aggregate Functions
* Views
* Data Type Conversions

---

## 📂 Dataset Used

The data used in this project comes from publicly available COVID-19 datasets containing:

* Total cases
* New cases
* Total deaths
* Population
* Vaccination data
* Country and continent information
* Dates of records

Tables used:

* `CovidDeaths`
* `CovidVaccinations`

---

## 🛠️ Tools & Technologies

* SQL Server
* SQL Server Management Studio (SSMS)
* SQL Queries
* GitHub

---

## 📌 Key Analysis Performed

This project answers important analytical questions such as:

### 🌍 Global Overview

* Total cases and deaths worldwide
* Death percentage across the globe
* Infection rate compared to population

### 🏳️ Country-Level Analysis

* Countries with the highest infection rate
* Countries with the highest death count
* Death percentage per country

### 🗺️ Continent-Level Analysis

* Death count by continent
* Infection spread across continents

### 💉 Vaccination Analysis

* Rolling number of vaccinated people
* Percentage of population vaccinated
* Use of Window Functions for cumulative calculations

---

## 🧠 SQL Concepts Demonstrated

| Concept              | Usage in Project                        |
| -------------------- | --------------------------------------- |
| Joins                | Joining deaths and vaccination tables   |
| CTEs                 | Creating reusable result sets           |
| Temp Tables          | Storing intermediate results            |
| Window Functions     | Rolling vaccination totals              |
| Aggregate Functions  | SUM, MAX, COUNT                         |
| Views                | Storing final queries for visualization |
| Data Type Conversion | Ensuring correct calculations           |

---

## 📜 Sample Query

```sql
Select Location, date, total_cases, new_cases, total_deaths, population
From PortfolioProject..CovidDeaths
Where continent is not null
order by 3,4;
```

---

## 📊 Insights Extracted

* Identified countries most affected by COVID-19
* Compared death rates across nations
* Measured vaccination progress relative to population
* Observed trends over time using date-wise data

---

## 📁 Project Structure

```
COVID-19-Data-Exploration/
│
├── COVID 19 Data Exploration.sql
└── README.md
```

---

## 🚀 How to Use

1. Download the dataset tables into SQL Server.
2. Open the `.sql` file in SSMS.
3. Run queries step by step to reproduce the analysis.
4. Modify queries to explore additional insights.

---

## 🎯 Learning Outcome

This project is ideal for anyone who wants to:

* Practice real-world SQL analysis
* Understand how SQL is used in data analytics
* Build a strong SQL portfolio project

---

## 🤝 Contributing

Feel free to fork this repository, improve the queries, or add visualizations using Power BI/Tableau.

---

## ⭐ If you found this useful

Give this repo a star ⭐ and feel free to connect!
