# 🎬 Sakila DVD Rental Data Analysis (Python + SQLite)

## 📌 Project Overview

This project explores the **Sakila DVD Rental database** using **Python
and SQLite** to analyze customer behavior, film performance, revenue
trends, and operational efficiency in a fictional DVD rental business.

The goal is to demonstrate **practical SQL querying**, **data analysis
in Python**, and **business-oriented insights** using a well-structured
relational database.

------------------------------------------------------------------------

## 🎯 Objectives

-   Understand the structure and relationships of the Sakila database
-   Analyze **rental frequency and customer behavior**
-   Identify **top-performing films and categories**
-   Evaluate **revenue patterns over time**
-   Assess **staff and store performance**
-   Produce **clear visualizations and insights**

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Python**
-   **SQLite**
-   **Pandas**
-   **Matplotlib**
-   **Jupyter Notebook**

------------------------------------------------------------------------

## 🗂️ Project Structure

    sakila-analysis/
    │
    ├── data/
    │   └── sakila.sqlite
    │
    ├── notebooks/
    │   ├── 01_database_exploration.ipynb
    │   ├── 02_customer_analysis.ipynb
    │   ├── 03_film_category_analysis.ipynb
    │   ├── 04_revenue_analysis.ipynb
    │   ├── 05_staff_store_performance.ipynb
    │   └── 06_insights_and_recommendations.ipynb
    │
    ├── visuals/
    │   └── charts/
    │
    └── README.md

------------------------------------------------------------------------

## 🧩 Database Overview

The Sakila database models a **DVD rental business** and contains
entities such as: - Films, categories, actors, and languages -
Customers, rentals, and payments - Inventory, staff, and stores -
Geographic data (address, city, country)

The database consists of **16 tables**, with normalized relationships
supporting complex analytical queries.

------------------------------------------------------------------------

## 📊 Key Analyses Performed

### 1️⃣ Database Exploration

-   Table inspection and schema understanding
-   Identification of primary keys and relationships

### 2️⃣ Customer Analysis

-   Rental frequency per customer
-   Top customers by number of rentals
-   Customer distribution by country

### 3️⃣ Film & Category Analysis

-   Number of films per category
-   Most rented films
-   Category popularity based on rentals

### 4️⃣ Revenue Analysis

-   Total revenue generated
-   Monthly revenue trends
-   Revenue distribution by category and store

> ⚠️ *Note:* The Sakila database does **not** include payment method
> information. Therefore, payment method distribution analysis is not
> supported.

### 5️⃣ Staff & Store Performance

-   Revenue generated per staff member
-   Number of rentals handled by staff
-   Performance comparison between stores

### 6️⃣ Insights & Recommendations

-   Identification of high-value customers
-   Popular categories for inventory optimization
-   Operational insights for staffing and store performance

------------------------------------------------------------------------

## 📈 Example Visualization

-   Rental frequency distribution (histogram)
-   Number of films per category (horizontal bar chart)
-   Monthly revenue trends (line chart)

------------------------------------------------------------------------

## 🧠 Key Insights

-   A small group of customers accounts for a large proportion of
    rentals
-   Certain film categories consistently outperform others
-   Revenue shows clear monthly patterns
-   Staff and store performance varies significantly

------------------------------------------------------------------------

## 🚀 How to Run This Project

1.  Clone the repository:

    ``` bash
    git clone https://github.com/your-username/sakila-analysis.git
    ```

2.  Install required libraries:

    ``` bash
    pip install pandas matplotlib
    ```

3.  Open Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

4.  Run notebooks in numerical order for best understanding

------------------------------------------------------------------------

## 📚 Learning Outcomes

-   Writing complex SQL queries with multiple JOINs
-   Combining SQL and Pandas effectively
-   Performing exploratory and business-driven analysis
-   Creating clear, interpretable visualizations
-   Documenting a complete data analytics project

------------------------------------------------------------------------

## 🔄 Possible Extensions

-   Customer segmentation (RFM analysis)
-   Rental seasonality analysis
-   Dashboard creation using Power BI or Tableau
-   Predictive modeling on rental behavior
-   Synthetic payment method simulation (for learning only)

------------------------------------------------------------------------

## 👤 Author

**Olaoluwa Isaac**\
Data Analyst \| SQL & Python Tutor

------------------------------------------------------------------------

## 📄 License

This project is for **educational and portfolio purposes**.
