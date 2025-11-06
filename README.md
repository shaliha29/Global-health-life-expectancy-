# Global-health-life-expectancy-
Exploratory Data Analysis on Global Health and Life Expectancy (2000–2015)

# 🌍 Global Health and Life Expectancy Analysis   
This project analyzes global health data from the World Health Organization (WHO) to identify how socio-economic, health, and lifestyle factors influence life expectancy across countries over several years. The analysis includes data cleaning, exploration, visualization, and deriving key insights.

---

## 🎯 Project Overview
The analysis focuses on understanding:
-To explore the global trends in life expectancy from 2000 to 2015.
-To examine how factors such as GDP, schooling, health expenditure, and disease prevalence influence life expectancy.
-To compare the life expectancy patterns between developed and developing countries.
-To identify the strongest predictors of life expectancy using statistical and visual analysis.
-To derive actionable insights that can help policy makers improve global health outcomes.

---

## 📁 Dataset Summary

| Attribute | Description |
|------------|-------------|
| **Country** | Name of the country |
| **Year** | Year of observation (2000–2015) |
| **Status** | Classification of the nation (Developed / Developing) |
| **Life expectancy** | Average life expectancy (in years) |
| **Adult Mortality** | Probability of dying between ages 15 and 60 per 1000 population |
| **infant deaths** | Number of infant deaths per 1000 population |
| **Alcohol** | Alcohol consumption (litres per capita) |
| **percentage expenditure** | Expenditure on health as a percentage of GDP per capita |
| **Hepatitis B** | Immunization coverage (% of one-year-olds) |
| **Measles** | Reported measles cases per 1000 population |
| **BMI** | Average Body Mass Index of the population |
| **under-five deaths** | Number of deaths of children under age five per 1000 |
| **Polio** | Polio immunization coverage (% of one-year-olds) |
| **Total expenditure** | Government health expenditure as % of total government expenditure |
| **Diphtheria** | DPT immunization coverage (% of one-year-olds) |
| **HIV/AIDS** | Deaths per 1000 population due to HIV/AIDS (0–49 years) |
| **GDP** | Gross Domestic Product per capita (in USD) |
| **Population** | Country’s population |
| **thinness 1–19 years** | % of thin children/adolescents (ages 10–19) |
| **thinness 5–9 years** | % of thin children (ages 5–9) |
| **Income composition of resources** | Human Development Index (HDI) component |
| **Schooling** | Average number of years of schooling |

### 🧮 Derived / Engineered Columns
| Derived Column | Description | Formula |
|----------------|-------------|---------|
| **mortality_ratio** | Measures the relative child mortality compared to adult mortality | under-five deaths / Adult Mortality |
| **Health_Efficiency** | Indicates how effectively a country's GDP contributes to life expectancy | Life expectancy / GDP |
| **Vaccination_Coverage** | Average immunization coverage combining Polio and Diphtheria | (Polio + Diphtheria) / 2 |

---


## 🧹 Data Cleaning
- Removed duplicates and handled missing values using mean/median/mode.
- Renamed inconsistent column names for clarity.
- Derived new columns for deeper insights.
- Detected and removed outliers using the IQR method(life expectancy in the  year **2013** contain many 0 values which were outliers)

---

## 📊 Data Visualization & Analysis
- **Distribution Analysis:** KDE plots for variables like Alcohol, and GDP.  
- **Comparative Analysis:** Bar charts comparing vaccination rates (Developed vs Developing).  
- **Correlation Analysis:** Heatmap to identify relationships among variables.  
- **Trend Analysis:** Line plots showing life expectancy changes over years.  
- **Scatter Analysis:** Exploring GDP, Schooling, and BMI vs Life Expectancy.

---

## 🔍 Key Insights
- Life expectancy has increased globally but disparities remain.
- Developed countries like **Japan**,**Sweden**,**Iceland** have higher life expectancy and vaccination coverage.
- GDP, education, and healthcare access strongly influence longevity.
- Reducing adult mortality and improving immunization programs are crucial for developing nations.
- Continuous investment in education, healthcare, and vaccination is essential to improve global longevity.

---

## 🧩 Conclusion
Economic growth, education, and healthcare improvements are major drivers of longer, healthier lives.  
Although progress is global, developing nations like **Sierra Leone,Central African Republic,Lesotho** still need stronger public health initiatives to close the life expectancy gap.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**
  
---

## 📁 Project Structure
global-health-life-expectancy

-  global_lifeexpectancy.ipynb # Main notebook
-  README.md # Project documentation 
-  Life Expectancy Data # Dataset file

---

## 📈 Results Preview
Visualizations include:
- GDP vs Life Expectancy  
- Schooling vs Life Expectancy  
- BMI and Alcohol distribution  
- Vaccination comparison bar chart  
- Correlation heatmap

---

## 💡 Author
**Shaliha Salim**
[LinkedIn](https://https://www.linkedin.com/in/shaliha-salim-870039375/) 
