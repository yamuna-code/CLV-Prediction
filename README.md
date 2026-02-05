# 🚀 AI-Driven Customer Lifetime Value (CLV) Prediction & Segmentation

## 📌 Project Overview
This project implements a high-accuracy machine learning pipeline to predict Customer Lifetime Value (CLV) and automate Behavioral Segmentation. By combining a Random Forest Regressor with an interactive Power BI Dashboard, this tool enables businesses to identify high-value "Champions" and mitigate "At Risk" customer churn.

### [Click here to view the Dashboard Screenshot]

---

## 🚀 Key Results
* **Model Accuracy ($R^2$ Score):** 91.33%
* **Mean Absolute Error (MAE):** $257.54
* **Segmentation Logic:** RFM (Recency, Frequency, Monetary) Analysis
* **Segments Identified:** Champions (Top 10%), Loyalists, and At-Risk customers.
* **Key Drivers:** Average Order Value (AOV) and Frequency were identified as the strongest predictors of future value.

---

## 🛠️ Tech Stack & Skills
* **Language:** Python 3.8+
* **Machine Learning:** Scikit-Learn (Random Forest Regressor)
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Power BI Desktop, Seaborn, Matplotlib
* **Data Modeling:** DAX (Data Analysis Expressions) for Power BI measures

---

## 📊 Dashboard Key Features
* **Geographic Distribution:** Interactive map showing customer clusters by **City**.
* **Segment Analysis:** Stacked charts visualizing product preferences across **Customer Tiers**.
* **Temporal Trends:** Line charts tracking revenue behavior over the **Order Date** timeline.
* **Category Analysis:** Identifying product preferences across different customer segments.
* **Dynamic Slicers:** Real-time filtering by **Segment** and **Product Category**.

---

## 📂 Project Structure
* `Project_Notebook.ipynb` — Full Python pipeline (EDA, Training, Evaluation).
* `clv_rf_model.pkl` — Saved Random Forest model for deployment.
* `Final_Leaderboard.csv` — Enriched 10-column dataset for BI tools.
* `Customer_Insights.pbix` — Power BI dashboard file.
* `requirements.txt` — List of necessary Python libraries.

---

## 🚀 Deployment & Future Scope
* **Current:** Batch processing via scheduled Python scripts.
* **Future:** Deployment as a REST API using **FastAPI** for real-time customer scoring and integration with CRM systems like Salesforce for automated email triggers.

---

## 📝 How to Use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the notebook to generate the latest predictions.
4. Open the `.pbix` file to interact with the visual analytics.
