# AOZORA Bank Customer Churn – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of bank customer data to understand customer attrition patterns and explore the characteristics associated with customers leaving the bank.

The analysis examines customer demographics, account-related attributes, card categories, income groups, and other available variables to identify patterns and generate meaningful business insights.

## 🎯 Objectives

- Understand customer churn patterns in the banking dataset.
- Analyze customer demographics and account-related characteristics.
- Explore the relationship between customer attributes and attrition.
- Perform univariate and bivariate analysis.
- Use statistical summaries and visualizations to identify trends.
- Develop data-driven insights that may support customer retention strategies.

## 📂 Repository Contents

| File | Description |
|---|---|
| `Bank Churn Data EDA.ipynb` | Jupyter Notebook containing data exploration, analysis, and visualizations |
| `DS1_C6_S1_BankChurn_Data_Concept.csv` | Dataset used for the analysis |
| `README.md` | Project documentation |

## 🛠️ Technologies and Libraries

- **Python** – Programming and data analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Tabulate** – Formatting tabular output
- **Jupyter Notebook** – Interactive development environment

## 🔍 Analysis Performed

### 1. Data Inspection
- Displayed initial and final records.
- Examined dataset structure, columns, and data types.
- Checked for missing values.

### 2. Univariate Analysis
- Explored individual customer attributes.
- Examined categorical variables such as gender, education, income category, and card category.
- Used statistical summaries and visualizations to understand distributions.

### 3. Bivariate Analysis
- Compared customer attrition status with selected demographic and account-related attributes.
- Explored attrition patterns across gender, education, income category, card category, and dependent count.
- Used visualizations to compare customer groups.

### 4. Correlation Analysis
- Examined relationships among numerical variables using correlation analysis and a heatmap.

### 5. Data Visualization
- Created charts to understand customer distributions and compare attrition patterns across different categories.

## 📊 Key Areas of Investigation

The analysis explores:

- Customer attrition distribution.
- Differences in attrition patterns across customer groups.
- Relationships between customer characteristics and attrition.
- Potential patterns that could help guide customer retention efforts.

The conclusions should be interpreted from the actual charts and numerical results in the notebook. This project focuses on exploratory analysis and does not claim that the observed relationships establish causation.

## 💡 Business Applications

The findings from this analysis may help banking organizations:

- Identify customer groups with comparatively higher attrition rates.
- Understand customer characteristics associated with churn.
- Investigate areas that may require further customer satisfaction analysis.
- Develop data-informed customer retention strategies.

These are potential applications of the analysis, not claims that specific retention strategies were implemented or tested.

## ▶️ How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn tabulate jupyter
```

### Steps

1. Clone or download this repository.
2. Ensure the CSV dataset and notebook are in the same directory.
3. Open a terminal in the project directory.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Bank Churn Data EDA.ipynb`.
6. Run the notebook cells sequentially.

**Note:** The dataset filename in the notebook must match the actual CSV filename in the repository.

## 📁 Dataset

The dataset is provided in this repository for use with the notebook. It contains customer-related attributes used to explore banking customer churn.

Please refer to the dataset source and its licence or usage terms before redistributing the data.

## 👩‍💻 Author

**Apurva Kadam**

GitHub: [@apurva0210](https://github.com/apurva0210)

## 📝 Conclusion

This project demonstrates practical skills in Python programming, data manipulation, exploratory data analysis, statistical exploration, and data visualization. It uses customer data to investigate patterns associated with bank customer attrition and explore insights relevant to customer retention.

---

*This project was developed for learning and practice in Data Analysis and Exploratory Data Analysis.*
