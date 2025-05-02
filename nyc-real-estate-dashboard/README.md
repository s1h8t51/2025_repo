# 🏙️ NYC Real Estate Dashboard (2024)

This dashboard uses public sales data from the **NYC Department of Finance** to visualize and predict real estate trends across Manhattan neighborhoods. Built using Python, Dash, and machine learning — this project is a zero-cost proof of concept designed for investor insights, urban planning, and development strategy.

---

## 🔍 Features

- 📊 Interactive visualizations (Plotly Dash)
- 🧠 Predictive modeling (Random Forest & Linear Regression)
- 📈 Neighborhood insights: liquidity, repositioning, affordability
- 📁 Static exports (Seaborn/Matplotlib)
- 🧩 Lightweight — no external hosting required

---

## 🛠️ Technologies Used

- Python 3.9+
- Dash + Plotly
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (RandomForest, LinearRegression)
- OpenPyXL (Excel reader)

---

## 🗂️ Dataset Source

**NYC Department of Finance – Rolling Sales Data**  
🔗 https://www.nyc.gov/site/finance

> Dataset includes:
> - Neighborhood, Borough, Building Class
> - Sale Price, Number of Sales
> - Minimum/Maximum/Average/Median sale values

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone https://github.com/yourusername/nyc-real-estate-dashboard.git
cd nyc-real-estate-dashboard

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
