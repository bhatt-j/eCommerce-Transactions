# eCommerce-Transactions: Data Analysis and Modeling
This project analyzes an eCommerce dataset using exploratory data analysis (EDA), clustering techniques, and a lookalike model to extract actionable insights and predict customer behavior.

Table of Contents
- Overview
- Dataset Description
- Tasks
    - Task 1: Exploratory Data Analysis (EDA)
    - Task 2: Lookalike Model
    - Task 3: Customer Segmentation / Clustering
- How to Run

### Overview
This project involves the analysis and modeling of eCommerce data to derive business insights, predict customer behavior, and group customers based on spending and transactional patterns. The project focuses on:

- Understanding customer demographics and product performance.
- Recommending similar customers using a lookalike model.
- Segmenting customers into clusters.

### Data Description
- Customers.csv: Contains customer profile details (CustomerID, CustomerName, Region, SignupDate).
- Products.csv: Contains product details (ProductID, ProductName, Category, Price).
- Transactions.csv: Contains transaction history (TransactionDate, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, Price).

### Tasks
Task 1: Exploratory Data Analysis (EDA)<br>
EDA is performed to identify trends, patterns, and insights from the dataset.

Task 2: Lookalike Model <br>
A lookalike model was built to recommend three similar customers for a given customer ID based on their transaction history and profile.

Task 3: Customer Segmentation / Clustering <br>
Performed customer segmentation using K-Means clustering to group customers based on their total revenue, transaction count, and purchase quantity.

### How to Run
- Clone this repository:
**git clone <repository_url>**

- Install the required libraries:
**pip install pandas matplotlib seaborn scikit-learn**

- Run the Jupyter Notebook:
**_eda.ipynb,
_lookalike_model.ipynb,
_Clustering.ipynb**
