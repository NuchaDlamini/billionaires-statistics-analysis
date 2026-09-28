# billionaires-statistics-analysis
Excel data analysis project exploring billionaire wealth, demographics, industries, and country-level statistics.

# Billionaires Statistics Analysis

## Project Overview

This project is an Excel data analysis project exploring statistics about billionaires around the world.

The analysis uses an Excel dataset containing information about billionaire rankings, net worth, industries, countries, gender, self-made status, sources of wealth, and additional country-level economic indicators.

---

## Problem Statement

The goal of this project was to explore the billionaire dataset and identify patterns related to wealth, industries, countries, and personal characteristics.

The analysis looks at questions such as:

* Who are the highest-ranked billionaires in the dataset?
* Which individuals have the highest net worth?
* Which industries are represented among the wealthiest individuals?
* What countries are represented in the dataset?
* What is the age of individuals in the dataset?
* How does self-made status vary among billionaires?
* What other characteristics can be explored from the available data?

---

## Tools Used

* **Microsoft Excel**
* **Pivot Tables**
* **Excel Formulas**
* **Charts & Data Visualization**
* **Data Cleaning & Preparation**

---

## Dataset

The dataset contains **475 billionaire records** and includes fields such as:

* Rank
* Category
* Person Name
* Country
* City
* Source of Wealth
* Industry
* Self-Made Status
* Gender
* First Name
* Last Name
* Net Worth
* Birth Year
* Birth Month
* Birth Day
* Country CPI
* Country GDP
* Life Expectancy
* Tax Revenue
* Total Tax Rate
* Country Population

This combination of individual and country-level information allows the dataset to be explored from several different perspectives.

---

## Project Workflow

### 1. Data Preparation

The original dataset was organized into an Excel data table for analysis.

Additional calculated fields were created, including:

* **Age**
* **Current Date**
* **Birth Date**

The age calculation uses the billionaire's birth date and the current date.

Example formula:

```excel
=YEARFRAC(X2,W2,1)
```

The birth date was created from the separate birth year, month, and day fields:

```excel
=DATE(M2,N2,O2)
```

---

### 2. Pivot Table Analysis

Pivot tables were used to summarize the dataset and make it easier to identify patterns.

One of the analyses focused on the **Top 10 Rich List**, using billionaire names and their corresponding net worth.

The analysis also included an age-based summary to explore the distribution of ages within the dataset.

---

### 3. Data Visualization

A bar chart titled **"Top 10 Rich List"** was created to visually compare the net worth of the highest-ranked individuals.

This makes it easier to compare billionaire wealth than looking at individual records in the raw dataset.

---

## Key Analysis

### Top 10 Rich List

The dataset's highest-ranked individuals include:

| Rank | Billionaire               | Net Worth |
| ---: | ------------------------- | --------: |
|    1 | Bernard Arnault & family  |     $211B |
|    2 | Elon Musk                 |     $180B |
|    3 | Jeff Bezos                |     $114B |
|    4 | Larry Ellison             |     $107B |
|    5 | Warren Buffett            |     $106B |
|    6 | Bill Gates                |     $104B |
|    7 | Michael Bloomberg         |    $94.5B |
|    8 | Carlos Slim Helu & family |      $93B |
|    9 | Mukesh Ambani             |    $83.4B |
|   10 | Steve Ballmer             |    $80.7B |

The dataset records net worth in millions, so the values above are presented in billions for easier interpretation.

---

## Industries Represented

The dataset contains billionaires from a wide range of industries, including:

* Technology
* Fashion & Retail
* Finance & Investments
* Automotive
* Media & Entertainment
* Telecom
* Food & Beverage
* Diversified industries

This allows the data to be explored to see how billionaire wealth is distributed across different sectors.

---

## Analysis Features

The workbook includes:

* 📊 Top 10 Rich List visualization
* 📋 Pivot table analysis
* 👤 Billionaire demographic information
* 💰 Net worth analysis
* 🌍 Country-level information
* 🏢 Industry/category information
* 🎂 Age calculations
* 📈 Data summaries

---

## Key Skills Demonstrated

Through this project, I practiced:

* Excel data analysis
* Data preparation
* Pivot Tables
* Excel formulas
* Data visualization
* Working with large datasets
* Identifying trends and patterns
* Presenting analytical findings

---

## Author

**Nucha Dlamini**

Aspiring Data Analyst interested in using data analysis and visualization to transform raw data into meaningful insights.
