# Instacart Data Analysis 🛒📊

This project explores and analyzes data from **Instacart**, a grocery delivery platform where customers can place grocery orders and receive them at home, similar to Uber Eats or iFood. The dataset was originally released for a Kaggle competition in 2017 and has been modified for educational purposes.

## 🧠 Project Goal

The main objective is to clean, process, and analyze the data to gain insights into Instacart customers' purchasing habits. The analysis is performed using a Jupyter Notebook, including visualizations and markdown summaries.

## 🗂️ Dataset Overview

The dataset consists of five main CSV files:

### `instacart_orders.csv`
Each row represents a grocery order placed through the app.
- `order_id`: unique identifier for each order
- `user_id`: unique identifier for each customer
- `order_number`: number of the order in the user's sequence
- `order_dow`: day of the week the order was placed (0 = Sunday)
- `order_hour_of_day`: hour of the day the order was placed
- `days_since_prior_order`: days since the previous order by the customer

### `products.csv`
Each row represents a unique product available for purchase.
- `product_id`: unique product ID
- `product_name`: name of the product
- `aisle_id`: aisle category ID
- `department_id`: department category ID

### `order_products.csv`
Each row represents an item included in an order.
- `order_id`: order ID
- `product_id`: product ID
- `add_to_cart_order`: the order in which items were added to the cart
- `reordered`: 0 if the product is new to the user, 1 if reordered

### `aisles.csv`
Aisle categories in the store.
- `aisle_id`: unique aisle ID
- `aisle`: name of the aisle

### `departments.csv`
Department categories in the store.
- `department_id`: unique department ID
- `department`: name of the department

## 🔍 Tasks Performed

- **Data Cleaning**: removal of duplicates and handling of missing values.
- **Exploratory Data Analysis (EDA)**: examining key variables and their relationships.
- **Visualizations**: all graphs include titles, labeled axes, legends (if needed), and are displayed using `plt.show()`.
- **Insights**: markdown cells summarize findings and interpretations.

## 📊 Sample Questions Answered

- What are the most common order days and times?
- Which products are most frequently reordered?
- Which departments and aisles have the highest sales volume?
- Are there patterns between reorder frequency and product types?

## 💻 Technologies Used

- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

## 📎 Data Source

This is a modified version of the dataset originally provided by Instacart for a [Kaggle competition](https://www.kaggle.com/competitions/instacart-market-basket-analysis). The dataset has been reduced in size and includes missing values and duplicates to enhance data wrangling practice.

## ▶️ Conclusions

Answered in the notebook.
