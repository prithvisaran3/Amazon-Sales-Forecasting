# Amazon Sales Forecasting

Time-series forecasting project using the *Predict Future Sales* Kaggle dataset.  
Preprocessed data, engineered lag/rolling features; trained Linear Regression, KNN, and XGBoost models. Evaluated with RMSE and visualized sales trends. Built for GWU Machine Learning course.


---

## 📊 Dataset
- **Name:** Predict Future Sales (Kaggle)  
- **Description:** Time-series data of product sales from many shops across months and product categories.  
- **How to obtain:** Download separately from Kaggle; it is not included here due to size.

---

## ⚙️ Methods & Features
- Data cleaning: missing values, outliers, scaling  
- Feature engineering: lag features, rolling window statistics  
- Models used: Linear Regression, K-Nearest Neighbors (KNN), XGBoost  
- Evaluation metric: Root Mean Squared Error (RMSE)

---

## 🚀 How to Run
//bash
git clone https://github.com/prithvisaran3/Amazon-Sales-Forecasting.git
cd amazon-sales-forecasting

# install dependencies
pip install -r requirements.txt

# open the notebook
jupyter notebook notebooks/amazon_sales_forecasting.ipynb
# or open in Colab
📈 Results

RMSE scores for each model

Visualizations: sales over time; comparison of predictions vs actuals

Insights on top performing shops / categories

💡 Highlights & Takeaways

Feature engineering combined with XGBoost produced the best forecasts

Addressed challenges like overfitting, seasonal effects, and data sparsity

Provided actionable insights for optimizing product focus and shop performance

⚖️ License

This project is licensed under the MIT License.

📬 Contact

Developed by Prithvi Saran Sathyasaran
GitHub: prithvisaran3

LinkedIn: Your LinkedIn Profile
