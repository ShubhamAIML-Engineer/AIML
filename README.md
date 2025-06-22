📊 Acquisition Insights & Forecasting using Prophet
This project is an end-to-end solution for analyzing and forecasting tech acquisitions using interactive visualizations and the Prophet forecasting model. It helps explore acquisition trends, detect outliers, visualize heatmaps, and generate future forecasts for acquisition counts and total prices per company.

📁 Features
📈 Interactive bar and line charts for year-wise acquisition counts

💰 Outlier detection in acquisition prices

🔥 Heatmap of acquisition presence across years and companies

📦 Boxplots with and without outliers

🏆 Top 10 acquirers and Top 5 costliest acquisitions

📅 Month-wise average acquisition prices

🔮 Forecasting acquisition count and prices using Facebook Prophet

🧪 Evaluation metrics (MAE, RMSE, MAPE)

🧾 Auto-generated Excel with forecast + evaluation results

🛠️ Setup Instructions
1. Install Required Libraries
bash
Copy
Edit
pip install prophet pandas matplotlib openpyxl plotly scikit-learn
If you're using Google Colab, the first cell handles this automatically.

📂 Input
Upload a .csv or .xlsx file containing acquisition data with at least the following columns:

Parent_Company: Name of acquiring company

Acquired_Company: Name of acquired company

Acquisition_Year: Year of acquisition (numeric)

Acquisition_Price: Acquisition price (numeric)

Acquisition_Month: Month of acquisition (e.g., Jan, Feb, etc.)

🧠 Key Steps in the Notebook
✅ Data Cleaning
Converts data types

Handles missing values

Filters out invalid entries

📊 Visualizations
Dropdown-based acquisition trends (bar + line)

Price outliers per year and company

Binary acquisition occurrence heatmap

Boxplots for price distributions

🏅 Rankings
Top 10 companies by acquisition volume

Top 5 acquisitions by price

🔍 Forecasting
Filters eligible companies (minimum data threshold)

Forecasts both:

Acquisition count per year

Total acquisition price per year

Evaluation using MAE, RMSE, MAPE

📤 Output
Excel file Forecast_Results.xlsx with:

Forecasted values (counts + prices)

Evaluation metrics

📥 Output Files
Forecast_Results.xlsx

Sheet 1: Forecasts (per company and year)

Sheet 2: Evaluation Metrics

💡 Example Use Cases
M&A teams tracking acquisition performance

Market analysts monitoring consolidation trends

Data scientists forecasting future acquisition activities

Product teams evaluating market movement for competitors

👨‍💻 Author
Shubham Goyal
ML/Data Scientist | Forecasting | Python | Plotly | Prophet
