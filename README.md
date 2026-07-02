GlobalMart Customer Segmentation
RFM Analysis & K-Means Clustering | Self Project · Nov 2024 – Dec 2024

Overview
Segment retail customers based on purchasing behaviour to identify high-value customer groups and support targeted marketing strategies.

The project uses a real-world transactional dataset (~540K records) from a UK-based online retail store and applies both a rule-based RFM scoring approach and unsupervised K-Means clustering to uncover actionable customer segments.


Techniques Used
RFM Analysis — Recency, Frequency, Monetary metrics per customer
K-Means Clustering — data-driven segmentation with sklearn
Elbow Method — optimal k selection via inertia plot
Silhouette Score — cluster quality evaluation
PCA — 2D visualisation of high-dimensional clusters


Project Structure
globalmart-customer-segmentation/

├── notebooks/

│   └── GlobalMartAnalysis.ipynb   # Main analysis notebook

├── data/

│   └── .gitkeep                   # Place data.csv here (see Dataset section)

├── requirements.txt

├── .gitignore

└── README.md


Dataset
This project uses the Online Retail Dataset from the UCI Machine Learning Repository.

Source: UCI ML Repository – Online Retail
Records: ~540,000 transactions
Period: Dec 2010 – Dec 2011

Download Online Retail.xlsx, convert to data.csv, and place it in the data/ folder.


Setup & Installation
# 1. Clone the repository

git clone https://github.com/priyamvadakw-sketch/globalmart-customer-segmentation.git

cd globalmart-customer-segmentation

# 2. Install dependencies

pip install -r requirements.txt

# 3. Add dataset

#    Place data.csv inside the data/ folder

# 4. Launch Jupyter

jupyter notebook notebooks/GlobalMartAnalysis.ipynb


Results
Segment
Avg Recency
Avg Frequency
Avg Monetary
Action
Champions
Low
High
High
Reward & retain
Loyal Customers
Medium
Medium
Medium
Upsell & nurture
At-Risk
High
Medium
Medium
Win-back campaigns
Lost / Hibernating
Very High
Low
Low
Re-engage or suppress


Key finding: a small group of Champions drives a disproportionate share of total revenue — prioritising their retention has the highest business ROI.


Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn


Author
Priyamvada Wahatule · GitHub

