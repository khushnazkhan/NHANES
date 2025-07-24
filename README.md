# 📊 NHANES Body Measurement Analysis Project

## 📝 Project Overview

This project involves analyzing adult body measurement data from the **National Health and Nutrition Examination Survey (NHANES)**. Using Python tools such as NumPy, Matplotlib, and Seaborn, we performed descriptive statistics, visualization, correlation analysis, and body ratio calculations.

The goal was to compare male and female body metrics, compute health indicators like **BMI (Body Mass Index)**, **Waist-to-Height Ratio**, and **Waist-to-Hip Ratio**, and understand their distributions and relationships.

---

## 📂 Dataset Description

We used two datasets:

- `nhanes_adult_male_bmx_2020.csv`
- `nhanes_adult_female_bmx_2020.csv`

Each file contains the following **7 columns**:

1. **Weight** (kg)  
2. **Standing Height** (cm)  
3. **Upper Arm Length** (cm)  
4. **Upper Leg Length** (cm)  
5. **Arm Circumference** (cm)  
6. **Hip Circumference** (cm)  
7. **Waist Circumference** (cm)

---

## 🔧 Tools & Libraries Used

- **Python**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔍 Project Tasks

### ✅ 1. Data Loading
- Loaded male and female datasets into NumPy matrices.

### ✅ 2. Histogram Visualization
- Plotted male and female weight distributions using subplots.
- Maintained consistent x-axis limits for comparison.

### ✅ 3. Boxplot of Weights
- Compared male and female weights using side-by-side boxplots.
- Observed differences in median and spread.

### ✅ 4. Descriptive Statistics
- Computed:
  - Mean
  - Median
  - Standard deviation
  - Min, Max
  - Skewness
- Interpreted statistical differences between male and female weights.

### ✅ 5. BMI Calculation
- Computed **BMI** for all female participants:
  \[
  BMI = \frac{\text{weight (kg)}}{(\text{height (m)})^2}
  \]

### ✅ 6. Z-Score Normalization
- Standardized all columns of the female dataset using Z-scores.
- Created `zfemale` matrix for further correlation analysis.

### ✅ 7. Pairplot & Correlation
- Visualized relationships between standardized:
  - Weight
  - Height
  - Waist Circumference
  - Hip Circumference
  - BMI
- Calculated **Pearson** and **Spearman** correlation coefficients.

### ✅ 8. Body Ratio Calculations
- Added two ratios for both male and female datasets:
  - **Waist-to-Height Ratio**
  - **Waist-to-Hip Ratio**

### ✅ 9. Boxplot Comparison of Ratios
- Plotted 4 boxplots to compare body ratios across genders.

### ✅ 10. Extreme BMI Analysis
- Identified top 5 lowest and highest BMI participants from female dataset.
- Printed standardized body measurements for these individuals.

### ✅ 11. Discussion
- Discussed the pros and cons of BMI, WHtR, and WHR as health indicators.

---

## 📊 Key Insights

- **Males** showed higher weights and more variability.
- **Females** had slightly higher **waist-to-hip ratios**.
- **BMI** alone may not be sufficient; combining it with **waist-based ratios** provides better health insights.
- **Strong correlations** were found between BMI and waist/hip circumferences.

---

## ✅ Conclusion

This project showcased how statistical and visual analysis can be applied to real-world health data to extract meaningful insights. Using Python and NumPy, we were able to standardize features, derive new indicators, and visualize gender-based differences effectively.

---

## 📁 Repository Structure

NHANES_Project/
├── NHANES_Project.ipynb # Jupyter notebook with full analysis
├── NHANES_Summary_Report.pdf # Summary report for presentation
├── README.md # Project summary file (this file)
├── /data # Contains CSV data files

yaml
Copy
Edit

---

## 🧠 Future Improvements

- Extend analysis to more years or age groups
- Train a classifier to predict obesity or health risk groups
- Deploy a dashboard with Streamlit for interactive analysis

---

## 🙋‍♀️ Author

**Khushnaz Khan**  
Email: khushnazkhan0786@gmail.com  
