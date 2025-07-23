#  Advertising Channel Impact Analysis

##  Project Objective
To analyze how different advertising channels affect product sales and provide data-driven recommendations on optimizing marketing spend.

##  Dataset Information
- File: `Advertising_Data.csv`
- Source: [Kaggle Notebook – Sales Prediction for Future by Navjot Singh](https://www.kaggle.com/code/singhnavjot2062001/sales-prediction-for-future/input)
- Description: Dataset includes advertising spend across various marketing channels such as TV, Billboards, Google Ads, Social Media, Influencer Marketing, and Affiliate Marketing, along with corresponding sales.
- Format: CSV
- Size: ~15 KB

##  Tools & Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

##  Methodology
1. Data Cleaning & Exploration
2. Correlation Analysis & Feature Selection
3. Linear Regression Modeling
4. Train/Test Split & Model Evaluation

##  Results & Insights
- TV and  Billboards showed the strongest correlation with sales.
- Social Media and Influencer Marketing had moderate influence.
- Model achieved an R² score of **0.82** *(update this to your actual result)*

##  Business Recommendation
Reallocate budget from low-performing channels like Newspaper toward high-performing platforms like TV, Google Ads, and Social Media to maximize marketing ROI and increase sales.

##  Limitations & Next Steps
- Include time-based or regional data for deeper segmentation.
- Experiment with other regression techniques like Ridge and Lasso.
- Analyze ROI per channel if conversion or cost data becomes available.

## Visuals
Visuals (e.g., correlation heatmap) are saved in the `/visuals/` folder for local use and illustration of insights.

## How to Run
1. Clone the repository
2. Install libraries from `requirements.txt`
3. Open `notebooks/Advertising_Analysis.ipynb`
4. Run all cells to view results and insights

---

**Note:** This dataset was sourced from a public Kaggle notebook and used for educational analysis. All code, modeling, and insights in this repository were created by Skyla Maharjan.
