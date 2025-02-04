# 🛍️ Black Friday Sales Analysis

## 📖 Project Overview
Black Friday is one of the busiest shopping events of the year, with retailers offering **deep discounts** and **special deals** on a wide range of products. This project aims to analyze a **Black Friday sales dataset** containing **537,578 rows and 12 columns**, uncovering valuable insights into **consumer behavior, purchasing trends, and market patterns**.

By exploring the dataset and conducting **various analyses**, we can **extract key findings** that will help companies make **data-driven decisions** to improve their marketing and sales strategies.

---

## 📊 Objectives
The **main goal** of this project is to conduct an **exploratory data analysis (EDA)** and derive insights about:
✔️ **Customer Demographics** – Age, gender, and marital status distributions.  
✔️ **Purchasing Behavior** – Understanding which products are selling the most.  
✔️ **Multi-Column Correlations** – Finding patterns between different variables.  
✔️ **Occupation & Product Analysis** – Identifying which occupations spend the most.  
✔️ **Visual Representation** – Using **Seaborn** and **Matplotlib** to visualize trends.

---

## 🛠️ Prerequisites

Before running this project, ensure you have the following **Python libraries installed**:

```bash
pip install pandas numpy seaborn matplotlib
📂 Dataset Overview
The dataset contains 537,578 rows and 12 columns. However, two columns—Product_Category_2 and Product_Category_3—contain a large number of missing values, so they are dropped to maintain data quality.

Columns in the Dataset:
User_ID – Unique identifier for customers.
Product_ID – Unique identifier for products.
Gender – Customer gender (Male/Female).
Age – Age group of customers.
Occupation – Customer occupation category.
City_Category – City classification (A, B, or C).
Stay_In_Current_City_Years – Number of years a customer has stayed in their current city.
Marital_Status – Whether the customer is married or unmarried.
Product_Category_1 – Main product category.
Product_Category_2 – Secondary product category (contains null values).
Product_Category_3 – Additional product category (contains null values).
Purchase – Purchase amount spent by the customer.
🔎 Data Analysis Breakdown
We divided our analysis into 7 key sections:

1️⃣ Dataset Walkthrough
Explored the dataset using .info() and .describe().
Identified missing values and dropped Product_Category_2 & Product_Category_3 to avoid data loss.
Verified data types and unique values.
2️⃣ Analyzing Columns
Used .nunique() and .unique() to check unique values in each column.
Found the total number of customers and total unique products.
3️⃣ Analyzing Gender
Discovered that males made more purchases than females.
Used groupby() and aggregation functions to analyze gender-based spending patterns.
Visualized results using pie charts and bar plots.
4️⃣ Analyzing Age & Marital Status
Identified the age group with the highest purchases.
Analyzed the purchase distribution across different age groups.
Found that 60% of customers were unmarried, while 40% were married.
Represented results using pie charts and bar plots.
5️⃣ Multi-Column Analysis
Combined multiple columns for deeper insights.
Used Seaborn for data visualization.
Explored correlations between Gender, Age, and Purchase.
6️⃣ Occupation and Products Analysis
Used count plots and bar charts to:
Identify the most common occupations of customers.
Find the top-selling products in different categories.
Analyze which products generated the most revenue.
7️⃣ Combining Gender & Marital Status
Performed a combined analysis of Gender and Marital_Status.
Used Seaborn's countplot() to visualize gender-based purchase trends among married and unmarried individuals.
📈 Key Insights
🟢 Male customers dominate Black Friday sales, making up the majority of purchases.
🟢 Young adults (26-35 years) have the highest spending rate.
🟢 Unmarried individuals purchase more than married individuals (60% vs. 40%).
🟢 Some product categories are purchased significantly more than others, indicating demand variations.
🟢 Occupation plays a major role in spending behavior—some professions spend more than others.

🖥️ Visualizations & Charts
We used Seaborn and Matplotlib to generate multiple charts: 1️⃣ Pie Charts – Show distribution of gender, age groups, and marital status.
2️⃣ Bar Graphs – Display purchase trends and occupation-wise spending.
3️⃣ Seaborn Countplots – Analyze relationships between multiple columns.
4️⃣ Histograms – Show spending distribution among different categories.

🚀 How to Run the Project
1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/black-friday-sales-analysis.git
cd black-friday-sales-analysis
2️⃣ Install required libraries:

bash
Copy
Edit
pip install pandas numpy seaborn matplotlib
3️⃣ Run the Jupyter Notebook or Python script:

bash
Copy
Edit
jupyter notebook
or

bash
Copy
Edit
python analysis.py
🛡️ Security & Best Practices
✔️ Handle missing values properly—avoid excessive data loss.
✔️ Use visualizations to present insights more effectively.
✔️ Optimize groupby operations for better performance in large datasets.
✔️ Ensure data privacy by not exposing personal user information.

📌 Future Scope
🔹 Predictive Modeling – Use Machine Learning (ML) to predict purchase amounts.
🔹 Deeper Segmentation – Analyze spending behavior across different city categories.
🔹 Customer Retention Strategies – Identify trends for targeted marketing campaigns.
