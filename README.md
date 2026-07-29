# 📡 Telecom Analysis – ConnectaTel Customer Behavior Analysis

## 📌 Project Overview

This project analyzes customer behavior for **ConnectaTel**, a telecommunications company in Latin America. The objective is to clean, explore, and analyze customer and service usage data to identify consumption patterns, detect outliers, segment customers, and generate business recommendations.

---

## 🎯 Project Objective

The main objectives of this project are:

- Clean and preprocess the datasets.
- Identify and handle missing values and invalid data.
- Explore customer behavior using descriptive statistics.
- Detect outliers in customer usage.
- Segment customers by age and usage level.
- Visualize customer behavior through charts.
- Generate executive insights and business recommendations.

---

## 📂 Datasets

The analysis uses the following datasets:

| Dataset | Description |
|----------|-------------|
| **plans.csv** | Information about current plans, including monthly price, included minutes, data allowance, and extra usage costs. |
| **users_latam.csv** | Customer information such as age, city, registration date, subscribed plan, and churn status. |
| **usage.csv** | Historical customer usage records, including calls, call duration, and text messages. |

---

## 📊 Analysis Workflow

The project follows these main stages:

1. **Data Loading**
   - Import datasets using Pandas.
   - Initial inspection of the data.

2. **Data Exploration**
   - Review data types.
   - Identify missing values.
   - Detect invalid values and inconsistencies.

3. **Data Cleaning**
   - Replace sentinel values.
   - Handle missing values.
   - Correct invalid dates.
   - Validate MAR (Missing At Random) variables.

4. **Feature Engineering**
   - Aggregate usage information by customer.
   - Create customer profile dataset.
   - Create age and usage segments.

5. **Exploratory Data Analysis (EDA)**
   - Summary statistics.
   - Histograms.
   - Boxplots.
   - Outlier detection using the IQR method.

6. **Customer Segmentation**
   - Age segmentation.
   - Usage segmentation.

7. **Executive Insights**
   - Business findings.
   - Customer behavior analysis.
   - Recommendations for improving service plans.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

---

## ▶️ How to Run the Notebook

### Option 1: Google Colab (Recommended)

1. Open the notebook in **Google Colab**.
2. Upload the datasets (`plans.csv`, `users_latam.csv`, and `usage.csv`) or mount your Google Drive.
3. Run the notebook from the first cell to the last.

### Option 2: Jupyter Notebook

1. Clone this repository:

```bash
git clone https://github.com/your-username/telecom-analysis.git
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run all cells in order.

---

## 🔄 Reproducibility Guide

To reproduce the analysis:

1. Clone or download this repository.
2. Place the datasets inside the project folder (or update the dataset paths).
3. Install the required Python libraries.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Execute all notebook cells sequentially.
6. Review the visualizations, customer segmentation, and executive insights.

---

## 📈 Key Results

- Improved data quality through cleaning and preprocessing.
- Identified customer segments based on age and usage.
- Detected meaningful outliers representing high-value customers.
- Generated visualizations to understand usage behavior.
- Produced executive recommendations to optimize ConnectaTel service plans.

---

## 👤 Author

**Jose Luis Torres**

Electronic Engineer | Data Analytics Student | Python • SQL • Power BI • Telecommunications
