# 🛍️E-commerce Sales Analysis using Python & Plotly
This project analyzes sales data from a fictional superstore to uncover trends in sales, profit, product categories, and customer segments. It uses Python and Plotly to create interactive visualizations that make the insights easy to understand.

# 📦 About the Dataset
- File Name: Sample - Superstore.csv
- Rows: 9,994
- Columns: 21
- Details Included:
- Order and shipping dates
- Customer info (name, segment, location)
- Product details (category, sub-category, name)
- Financial metrics (sales, quantity, discount, profit)

# 🧰 Tools Used
- Python 🐍
- pandas – for data cleaning and analysis
- Plotly – for interactive charts and graphs
- Jupyter Notebook – for running and displaying the analysis

## 📊 What’s Inside the Analysis
1. 🧼 Data Cleaning
- Converted date columns to proper datetime format
- Created new columns: Order Month, Order Year, Day of Week
# 2. 📈 Visualization
| Topic                      | Chart Type        | Description                                     |
|---------------------------|-------------------|--------------------------------------------------|
| Monthly Sales             | Line Chart        | Shows how sales change month by month            |
| Category Sales            | Donut Chart       | Compares sales across product categories         |
| Sub-Category Sales        | Bar Chart         | Highlights top-selling sub-categories            |
| Monthly Profit            | Line Chart        | Tracks profit trends over time                   |
| Category Profit           | Donut Chart       | Shows which categories are most profitable       |
| Sub-Category Profit       | Bar Chart         | Compares profit across sub-categories            |
| Segment Analysis          | Grouped Bar Chart | Shows sales and profit by customer segment       |
| Sales-to-Profit Ratio     | Table             | Measures how efficiently each segment converts   |
|                           |                   |   sales into profit                              |

# 📌 Key Insights
- Consumer segment has the highest sales but lower profit margins.
- Technology category is highly profitable.
- Chairs and Phones are top-selling sub-categories.
- Sales and profit vary significantly by month—seasonal trends are visible.

🚀 How to Run This Project
Step 1: Clone the Repository

Step 2: Install Required Libraries
pip install pandas plotly


Step 3: Open the Notebook
Use Jupyter Notebook or any Python IDE to open and run ecommerce_analysis.ipynb.

# 📁 Project Structure
ecommerce-sales-analysis/
│
├── Sample - Superstore.csv       # Dataset file
├── ecommerce_analysis.ipynb      # Jupyter notebook with full analysis
└── README.md                     # Project overview



💡 Future Improvements
- Add region-wise and city-wise analysis
- Build a dashboard using Streamlit or Dash
- Use machine learning to forecast future sales.
