# 📦 E-Commerce Sales Forecasting & Analytics

A robust end-to-end data pipeline for e-commerce platforms, covering data collection, preprocessing, feature engineering, and machine learning-based forecasting. The analytical results are complemented by an interactive Power BI dashboard to support business decision-making.

---

## 📌 Project Overview

The objective is to analyze historical transaction data to forecast monthly sales and derive actionable insights into customer behavior, seller performance, and regional trends across product categories.

---

## 🚀 Key Features

- **Data Collection**: Comprehensive extraction and integration of e-commerce transactional data
- **Advanced Feature Engineering**: Monthly aggregations, lag variables, and rolling averages to capture temporal dynamics
- **Predictive Modeling**: Comparison of ensemble regression models—Random Forest, XGBoost, and LightGBM—to forecast `sales_amount`
- **Interactive Dashboard**: Power BI dashboard visualizing key performance indicators (KPIs) such as revenue, order volume, and geographic distribution

---

## 📊 Data Pipeline & Modeling

The project follows a structured analytical workflow:

### 1️⃣ Data Preparation
- Handled missing values (e.g., delivery dates) and filtered out promotional anomalies

### 2️⃣ Monthly Aggregation
- Transactions aggregated by `customer_state` and `product_category_name`

### 3️⃣ Feature Engineering
- **Temporal features**: Year, Month, Quarter
- **Normalization**: Adjusted sales values to account for varying numbers of days per month
- **Lag & Rolling Features**: Incorporated historical sales patterns while preventing data leakage

### 4️⃣ Model Training
- Tree-based ensemble models (Random Forest, LightGBM, and XGBoost) were employed to learn complex, non-linear patterns and improve predictive performance

---

## 📂 Project Structure

```
e-commerce-forecasting/
│
├── Notebooks/
│   ├── milestone 1 - Data Preprocessing.ipynb
│   └── milestone 2 - EDA.ipynb
│
├── datasets.docx                                      # Dataset download links
├── Presentation - Sales Data Analysis_compressed.pdf  # Project presentation
├── Full_dashboard.pbix                                # Power BI dashboard
├── requirements.txt                                   # Python dependencies
└── README.md                                          # Project documentation
```

---

## 📥 Dataset Access

The datasets used in this project are available in the following file:

```
datasets.docx
```

---

## 📈 Power BI Dashboard

The repository includes a `Full_dashboard.pbix` file featuring:

- **Sellers Overview**: Comprehensive seller performance metrics and analytics
- **Sales Overview**: Detailed sales trends, patterns, and KPIs
- **Specials**: Special promotions, events, and their impact on sales

---

## 🛠️ Installation & Setup

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Power BI Desktop (for dashboard viewing)

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Samaa111/-Sales-Forecasting-and-Optimization
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the datasets**
   - Open `datasets.docx` for dataset download links
   - Download and place datasets in the appropriate directory

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Run the notebooks in order**
   - First: `Notebooks/milestone 1 - Data Preprocessing.ipynb`
   - Then: `Notebooks/milestone 2 - EDA.ipynb`

---

## 💻 Usage

### Running the Analysis

1. **Open the preprocessing notebook**
   ```
   Notebooks/milestone 1 - Data Preprocessing.ipynb
   ```
   Run all cells to clean and prepare the data

2. **Open the EDA notebook**
   ```
   Notebooks/milestone 2 - EDA.ipynb
   ```
   Run all cells to explore data patterns and train models

3. **View the presentation**
   ```
   Presentation - Sales Data Analysis_compressed.pdf
   ```
   Review project findings and insights

4. **Explore the dashboard**
   Open `Full_dashboard.pbix` in Power BI Desktop to interact with visualizations

---

## 🤖 Machine Learning Models

This project implements and compares three ensemble regression models:

| Model | Description |
|-------|-------------|
| **Random Forest** | Ensemble of decision trees with bagging |
| **XGBoost** | Gradient boosting with regularization |
| **LightGBM** | Fast gradient boosting framework |

All models are trained to forecast monthly `sales_amount` based on engineered features.

---

## 📊 Results & Insights

The models provide forecasts for monthly sales with the following capabilities:

- Time series forecasting with temporal patterns
- Regional sales predictions by state
- Category-specific sales trends
- Feature importance analysis

---

## 📄 Additional Resources

- **Project Presentation**: `Presentation - Sales Data Analysis_compressed.pdf`
- **Dataset Links**: Available in `datasets.docx`

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📧 Contact

For questions or suggestions, feel free to reach out or open an issue in this repository.


---

## 🙏 Acknowledgments

This project was developed as part of a data science and AI initiative.

---

<p align="center">
  <i>⭐ If you find this project helpful, please consider giving it a star!</i>
</p>
