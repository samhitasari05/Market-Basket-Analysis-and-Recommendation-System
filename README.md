# Market-Basket-Analysis-and-Recommendation-System
Conducted market research to segment product categories, identify cross-selling opportunities, and develop a recommendation system using Nearest Neighbors and Annoy.

**Overview**

This project performs Market Basket Analysis on an online retail dataset to uncover cross-selling opportunities and recommend products using machine learning techniques. It includes exploratory data analysis (EDA), frequent itemset mining, and recommendation algorithms based on Nearest Neighbors and Annoy (Approximate Nearest Neighbors).

**Key Features**

Data Cleaning and Preprocessing: Removed missing values, duplicates, and invalid transactions, and added meaningful features (e.g., categories and normalized prices).
Exploratory Data Analysis (EDA):
Top-selling items
Hourly and weekly sales trends
Revenue analysis and customer segmentation
Recommendation System Development:
Implemented Nearest Neighbors for accurate recommendations.
Enhanced recommendations using Annoy for faster approximate nearest-neighbor searches.
Comparison of algorithms with cosine similarity metrics.

**Dataset**

The dataset contains transactions from an online retailer, with the following columns:
BillNo: Transaction ID
Itemname: Purchased item
Quantity: Number of units sold
Date: Date and time of purchase
Price: Price per unit
CustomerID: Unique customer ID
Country: Country of the customer

**Installation Instructions**

To run this project locally, follow these steps:

1-Clone the repository: git clone https://github.com/yourusername/Market-Basket-Analysis-and-Recommendation-System.git
cd Market-Basket-Analysis-and-Recommendation-System

2-Install dependencies: Create a virtual environment (optional but recommended): python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

**Key Visualizations and Results**

1. Top 10 Selling Items:
2. Hourly Transactions Heatmap:
3. Recommendation Output Example:
Baseline Nearest Neighbors Recommendations:
WHITE HANGING HEART T-LIGHT HOLDER
GIRLS ALPHABET IRON ON PATCHES
PAPER CRAFT, LITTLE BIRDIE
ASSTD DESIGN 3D PAPER STICKERS
SMALL CHINESE STYLE SCISSOR
Annoy Approximate Nearest Neighbors Recommendations:
WHITE HANGING HEART T-LIGHT HOLDER
HEART OF WICKER SMALL
JUMBO BAG RED RETROSPOT
PARTY BUNTING
VICTORIAN GLASS HANGING T-LIGHT

**Future Enhancements**

Add personalized recommendations based on customer purchase history.
Include sentiment analysis from customer reviews (if available).
Optimize hyperparameters for improved performance.

**Acknowledgments**

The dataset used is a public dataset for academic purposes taken from Kaggle.
Special thanks to the Python libraries pandas, scikit-learn, seaborn, and Annoy for their contributions to data science workflows.
