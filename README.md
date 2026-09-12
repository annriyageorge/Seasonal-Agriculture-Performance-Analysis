# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

**Seasonal Agriculture Performance Analysis** is a data analysis project that studies agricultural performance across different **seasons, crops, and Indian states**.

The project uses Python-based data analysis and visualization techniques to understand patterns in **crop yield, production, resource usage, environmental conditions, water efficiency, revenue, cost, and profit**.

The analysis focuses on identifying seasonal trends, comparing crops and regions, examining relationships between agricultural factors, detecting unusual observations, and providing data-driven recommendations for agricultural planning.

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze agricultural performance across **Kharif, Rabi, and Zaid** seasons.
* Compare crop performance across different seasons.
* Study seasonal environmental conditions such as rainfall, temperature, humidity, sunlight, and soil moisture.
* Analyze resource usage including fertilizers, nutrients, pesticides, and water.
* Evaluate agricultural **yield, production, revenue, cost, and profit**.
* Study water usage and water-use efficiency.
* Examine relationships between agricultural and economic variables using correlation analysis.
* Compare agricultural performance across different Indian states.
* Identify unusual patterns and outliers.
* Perform statistical analysis to determine whether seasonal differences are significant.
* Provide recommendations for better agricultural planning and resource management.

---

## 📊 Dataset

The dataset contains **4,000 records and 28 variables** related to agricultural activities.

### Major attributes include:

* Farm ID
* State
* District
* Crop
* Season
* Farm Area
* Rainfall
* Average Temperature
* Humidity
* Sunlight Hours
* Soil pH
* Soil Moisture
* Nitrogen
* Phosphorus
* Potassium
* Irrigation Method
* Fertilizer Usage
* Pesticide Usage
* Seed Quality
* Yield
* Production
* Market Price
* Total Cost
* Revenue
* Profit
* Water Used
* Water Efficiency
* Disease/Pest Risk

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **SciPy** – Statistical analysis
* **Google Colab** – Development environment

---

## 🔍 Data Cleaning

The dataset was checked for missing values before performing the analysis.

Missing values were found in:

* Rainfall
* Soil Moisture
* Yield

Median-value imputation was used to handle these missing values.

After cleaning:

**Total missing values: 0**

**Dataset size: 4,000 rows × 28 columns**

---

## 📈 Analysis Performed

### 1. Seasonal Analysis

The performance of the three agricultural seasons was compared:

* Kharif
* Rabi
* Zaid

Metrics analyzed include:

* Average yield
* Production
* Revenue
* Profit
* Water usage
* Water efficiency

### 2. Environmental Analysis

The project examines how environmental conditions vary between seasons, including:

* Rainfall
* Temperature
* Humidity
* Sunlight
* Soil moisture
* Soil pH

### 3. Resource Analysis

Resource usage was compared across seasons using:

* Nitrogen
* Phosphorus
* Potassium
* Fertilizer
* Pesticides
* Water

### 4. Economic Analysis

Economic performance was evaluated using:

* Market price
* Total cost
* Revenue
* Profit

### 5. Correlation Analysis

Correlation analysis was used to study relationships between yield/profit and other variables.

Some important observations include:

* Yield and production showed a strong positive relationship.
* Revenue and profit showed a strong positive relationship.
* Production and profit showed a positive relationship.
* Water usage showed a moderate positive relationship with yield.
* Market price showed a moderate negative correlation with yield in this dataset.

Correlation indicates association and does **not necessarily imply causation**.

### 6. Statistical Analysis

ANOVA was performed to test whether seasonal differences were statistically significant.

**Yield ANOVA:**

* F-statistic ≈ 1.458
* p-value ≈ 0.233

This indicates that the difference in average yield between seasons was **not statistically significant at the 5% level**.

**Profit ANOVA:**

* F-statistic ≈ 34.29
* p-value < 0.001

This indicates a **statistically significant difference in profit across seasons**.

### 7. Crop-wise Analysis

Crop performance was compared across seasons.

The analysis showed that:

* **Sugarcane** had the highest yield and profit among the crops analyzed.
* **Chilli** remained profitable across all three seasons.
* Several crops performed better economically during Kharif.
* Several crops recorded losses during Rabi and Zaid.
* High yield does not always guarantee high profit.

### 8. State-wise Analysis

Agricultural performance was compared across eight states:

* Andhra Pradesh
* Gujarat
* Karnataka
* Madhya Pradesh
* Maharashtra
* Punjab
* Tamil Nadu
* Telangana

**Punjab** showed the highest average yield and strong average profit.

**Karnataka** recorded the highest average water usage.

**Punjab** also showed the highest average water-use efficiency.

### 9. Outlier Analysis

IQR-based outlier detection was performed for:

* Yield
* Profit
* Water efficiency

Outliers were not automatically removed because many extreme values were associated with differences between crops, particularly crops such as sugarcane that naturally have a different production scale.

---

## 💡 Key Findings

* **Kharif showed the strongest overall economic performance.**
* **Zaid had the lowest average yield, water efficiency, and profit.**
* Zaid also had the **highest average water usage**.
* Market prices were relatively similar across seasons, while production and cost differences contributed more strongly to profit differences.
* Environmental conditions varied considerably between seasons.
* Kharif had the highest rainfall and soil moisture.
* Zaid had the lowest rainfall and soil moisture and the highest average temperature.
* Sugarcane was the strongest crop in terms of yield and profit.
* Chilli remained profitable across all seasons.
* Some high-yield crops still produced losses, showing that **yield alone is not sufficient to evaluate agricultural performance**.
* Punjab showed strong overall state-level performance.
* Seasonal yield differences were not statistically significant according to ANOVA, while seasonal profit differences were statistically significant.

---

## 🌱 Recommendations

Based on the analysis:

1. **Prioritize suitable crops for each season** based on historical yield and profitability.
2. Improve **water management**, especially during Zaid where water usage was high but efficiency was comparatively low.
3. Consider both **yield and profitability** when selecting crops.
4. Promote efficient irrigation and resource management.
5. Monitor production costs because high production does not always result in higher profit.
6. Use regional and seasonal performance patterns to support agricultural planning.
7. Investigate unusually high or low observations before making decisions based on them.
8. Encourage data-driven crop and resource planning using historical agricultural data.

---

## 📂 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── dataset.csv
└── README.md
```

---

## ▶️ How to Run

### Using Google Colab

1. Download or clone this repository.
2. Open the `.ipynb` file in **Google Colab**.
3. Upload the dataset if required.
4. Run the notebook cells from top to bottom.

### Using Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

Then open:

```text
Seasonal_Agriculture_Performance_Analysis.ipynb
```

and run the cells sequentially.

---

## 📌 Conclusion

The analysis provides a comparative view of agricultural performance across seasons, crops, and states.

Overall, **Kharif demonstrated the strongest economic performance**, while **Zaid showed lower profitability and water efficiency**. The analysis also demonstrates that agricultural success depends on multiple factors, including production, resource usage, environmental conditions, and costs.

The findings can help support **seasonal crop planning, resource management, water conservation, and profitability-oriented agricultural decision-making**.

---

## 👩‍💻 Author

**Ann Riya George**

B.Tech Computer Science and Engineering – Data Science
Christ College of Engineering (Autonomous), Irinjalakuda

---

## ⭐ Project Highlights

* 📊 Exploratory Data Analysis
* 🌾 Seasonal Agricultural Analysis
* 🌱 Crop-wise Comparison
* 📍 State-wise Analysis
* 💧 Water Efficiency Analysis
* 💰 Profitability Analysis
* 📈 Correlation Analysis
* 📐 ANOVA Statistical Testing
* 🔎 Outlier Detection
* 💡 Data-driven Recommendations
