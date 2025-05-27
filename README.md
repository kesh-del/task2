# task2Project Title:
---------------
Diamonds Dataset - Statistical Analysis and Visualization

Project Description:
---------------------
This project explores and visualizes the Diamonds dataset using Pandas, Matplotlib, Seaborn, and Plotly. The goal is to understand the relationships between diamond attributes such as carat, price, cut, and clarity using statistical summaries and visual representations.

Dataset:
---------
- Source: https://www.kaggle.com/datasets/shivam2503/diamonds
- File: diamonds.csv

Tools and Libraries Used:
--------------------------
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Plotly

Project Workflow:
------------------
1. Load Dataset using Pandas
2. Display top rows and dataset information
3. Check for missing values
4. Generate descriptive statistics for numerical features
5. Visualize:
   - Correlation heatmap (Seaborn)
   - Histogram of price distribution (Seaborn)
   - Boxplot of price vs cut (Seaborn)
   - Scatter plot of carat vs price by cut (Plotly)
   - Interactive histogram of price by cut (Plotly)

Important Notes:
-----------------
- Categorical features like `cut`, `color`, and `clarity` are not included in correlation heatmap unless encoded.
- Correlation heatmap uses only numeric columns.
- Plotly visualizations are interactive and rendered in Colab or Jupyter environments.

How to Run:
------------
1. Clone the repository or open the notebook in Google Colab.
2. Download and upload `diamonds.csv` or place it in your Jupyter directory.
3. Run the notebook cell by cell to perform data analysis and view visualizations.

File Included:
---------------
- task2.ipynb (Python notebook for statistical analysis and visualizations)

Author:
--------
Abhishek


