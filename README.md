# Exploring Customer Behavior in a Data Lake with Python

## Project Overview
This project focuses on analyzing customer behavior using Python. The dataset is a CSV file stored in a data lake, and the analysis involves tasks such as data retrieval, segmentation, and basic insights into customer preferences.

By completing this project, we gain valuable insights into customer demographics, purchasing trends, and age-group-based behavior.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tasks](#tasks)
  - [1. Data Retrieval](#1-data-retrieval)
  - [2. Data Exploration](#2-data-exploration)
  - [3. Customer Segmentation](#3-customer-segmentation)
  - [4. Basic Analysis](#4-basic-analysis)
  - [5. Age Group Analysis (Optional)](#5-age-group-analysis-optional)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Project Insights](#project-insights)
- [License](#license)

---

## Dataset
The dataset used in this project is named `customer_data.csv` and contains the following columns:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **ProductID**: Unique identifier for each product purchased.
- **PurchaseAmount**: Amount spent by the customer on a product.

### Sample Data:
| CustomerID | Gender | Age | ProductID | PurchaseAmount |
|------------|--------|-----|-----------|----------------|
| 1          | Female | 28  | 101       | 42.50          |
| 2          | Male   | 35  | 102       | 63.00          |
| ...        | ...    | ... | ...       | ...            |

---

## Tasks

### 1. Data Retrieval
- Connected to the data lake using Python and the `pandas` library.
- Loaded the dataset into a Pandas DataFrame for further analysis.

### 2. Data Exploration
- Displayed the first 5 rows of the dataset.
- Counted the total number of rows and columns.
- Identified the number of unique customers and products.

### 3. Customer Segmentation
- Created a filtered dataset containing only female customers.
- Calculated the average age of male and female customers separately.

### 4. Basic Analysis
- Calculated the total purchase amount in the dataset.
- Identified the most purchased product based on frequency.

### 5. Age Group Analysis (Optional)
- Categorized customers into age groups (e.g., 18-25, 26-35, etc.).
- Analyzed and visualized the average purchase amount for each group using a bar chart.

---

## Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Jupyter Notebook**: For executing and documenting code.

---

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/customer-behavior-analysis.git
