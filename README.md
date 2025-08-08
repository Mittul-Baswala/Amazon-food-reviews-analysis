# 🍽️ Amazon Fine Food Reviews Analysis with Dask

*COMPANY NAME* : CODTECH IT SOLUTIONS 

*NAME*: MITTUL BASWALA

*INTERN ID*: CT06DZ2256

*DOMAIN*: DATA ANALYTICS

*MENTOR*: NEELA SANTOSH

# TASK DESCRIPTION

This project demonstrates scalable data analysis using **Dask** on the [Amazon Fine Food Reviews dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews). With over 500,000 reviews, this dataset provides a rich opportunity to explore customer sentiment, review behavior, and time-based trends—all while showcasing the power of parallel computing in Python.

## 📦 Dataset Overview

- **Source**: Kaggle  
- **File**: `Reviews.csv`  
- **Size**: ~500,000 rows  
- **Features**:
  - `ProductId`, `UserId`, `ProfileName`
  - `HelpfulnessNumerator`, `HelpfulnessDenominator`
  - `Score` (1–5 rating)
  - `Time` (Unix timestamp)
  - `Summary`, `Text` (review content)


## ⚙️ Tools & Technologies

- **Python 3.10+**
- **Dask** – for distributed data processing
- **Jupyter Notebook** – for interactive analysis
- **Matplotlib & Seaborn** – for visualizations


## 📊 Key Analyses

- **Score Distribution**  
  Visualized how customers rated products from 1 to 5 stars.

- **Review Length Analysis**  
  Measured the average length of review texts to understand verbosity.

- **Time-Based Trends**  
  Explored how review scores evolved over the years.

- **Helpfulness Metrics** *(optional)*  
  Investigated how helpfulness ratings relate to review quality.

## 🧠 Insights

- Majority of reviews are highly positive (4–5 stars)
- Longer reviews tend to be more helpful
- Review scores remained relatively consistent over time

## 🛠️ Why Dask?

Dask enables efficient processing of large datasets that may be slow or memory-intensive with Pandas. Benefits include:
- Lazy evaluation
- Parallel execution
- Real-time performance monitoring via Dask Dashboard.


## 📈 Visualizations

- Bar chart of score distribution  
- Line plot of average score by year
<img width="764" height="596" alt="Image" src="https://github.com/user-attachments/assets/ef843ad6-71c8-4768-96b8-f514f4976ac3" />
<img width="696" height="589" alt="Image" src="https://github.com/user-attachments/assets/ce11da1a-d683-4905-9f9e-1c2a122d1c92" />
