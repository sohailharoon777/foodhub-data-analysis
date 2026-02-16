# FoodHub Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on transactional order data from a food delivery platform (FoodHub). The objective is to extract actionable insights related to customer behavior, cuisine demand, revenue patterns, and operational efficiency.

The analysis demonstrates core Data Analyst / Data Scientist skills including data cleaning, statistical analysis, multivariate exploration, and business insight generation using Python.

---

## Business Objective

To support data-driven decision-making by analyzing:

- Customer ordering behavior
- Revenue distribution and commission impact
- Cuisine-level demand trends
- Restaurant performance via ratings
- Operational efficiency (food preparation & delivery time)
- Weekday vs weekend performance differences

---

## Dataset Description

The dataset contains order-level information including:

- `order_id` – Unique order identifier  
- `customer_id` – Customer identifier  
- `restaurant_name` – Restaurant name  
- `cuisine_type` – Cuisine category  
- `cost_of_the_order` – Order price  
- `day_of_the_week` – Weekday or weekend  
- `rating` – Customer rating (1–5 scale)  
- `food_preparation_time` – Time taken by restaurant (minutes)  
- `delivery_time` – Time taken for delivery (minutes)  

---

## Key Analysis Performed

- Data inspection and cleaning
- Univariate analysis (distribution plots, count plots, boxplots)
- Revenue distribution analysis
- Customer segmentation analysis (repeat customers)
- Cuisine demand analysis
- Weekday vs weekend comparison
- Multivariate relationship analysis
- Insight-driven business recommendations

---

## Key Insights

- Majority of orders fall within the $10–$30 range.
- Higher-value orders significantly increase revenue due to percentage-based commission.
- A small number of repeat customers contribute disproportionately to total order volume.
- American, Japanese, and Mexican cuisines dominate demand.
- Weekend delivery times differ from weekdays, indicating operational variation.
- Higher-rated restaurants consistently maintain strong performance.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter / Google Colab

---

## Repository Structure

FoodHub-Data-Analysis/
│
├── data/
│ └── foodhub_orders.csv
│
├── notebooks/
│ └── FoodHub_Data_Analysis.ipynb
│
├── reports/
│ └── FoodHub_Data_Analysis.html
│
├── README.md
└── requirements.txt


---

## How to Run the Project

1. Clone the repository:
git clone https://github.com/<your-username>/foodhub-data-analysis.git

2. Install dependencies:
pip install -r requirements.txt

3. Open the notebook in Jupyter or Colab.

Alternatively, open the HTML report directly:
reports/FoodHub_Data_Analysis.html


---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Business-oriented data interpretation
- Statistical reasoning
- Data visualization & storytelling
- Revenue and customer behavior analysis
- Insight-to-recommendation translation

---

## Author

Sohail Haroon  
Data Analytics | AI/ML | Business Intelligence
