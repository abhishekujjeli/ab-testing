# ab-testing
# A/B Testing Analysis Project

## Project Overview
This project performs an end-to-end A/B Testing analysis to compare the performance of two marketing campaign groups:

- Control Group
- Test Group

The objective is to determine whether the new campaign strategy (Test Group) performs better than the existing campaign (Control Group) using statistical analysis and business metrics.

---

# Dataset Information

The dataset contains the following variables:

| Column | Description |
|---|---|
| Impression | Number of ad views |
| Click | Number of clicks |
| Purchase | Number of purchases |
| Earning | Revenue generated |

The dataset is divided into:
- Control Group
- Test Group

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

# Project Workflow

## 1. Data Loading and Exploration
- Imported datasets
- Checked dataset structure
- Examined missing values and data types

## 2. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Distribution analysis
- Outlier inspection

## 3. Business Metric Calculations

### Click Through Rate (CTR)

```math
CTR = \frac{Clicks}{Impressions} \times 100
```

### Conversion Rate (CR)

```math
CR = \frac{Purchases}{Clicks} \times 100
```

### Lift Analysis

```math
Lift = \frac{Test - Control}{Control} \times 100
```

---

# Statistical Testing

## Assumption Tests
- Shapiro-Wilk Test (Normality)
- Levene Test (Variance Homogeneity)

## Hypothesis Tests
- Independent Sample t-test
- Mann-Whitney U Test

---

# Visualizations

The project includes:
- CTR comparison bar chart
- CR comparison bar chart
- Purchase distribution boxplot
- Histogram distribution plots

---

# Key Results

| Metric | Control Group | Test Group |
|---|---|---|
| CTR | 5.01% | 3.29% |
| CR | 10.80% | 14.67% |

## Lift Results

- CTR Lift: -34.33%
- CR Lift: +35.83%

---

# Final Conclusion

The Control group generated a higher Click Through Rate (CTR), indicating stronger click engagement from users.

However, the Test group achieved a significantly higher Conversion Rate (CR), showing better conversion efficiency and higher-quality traffic.

The Test campaign demonstrated a positive CR lift of 35.83%, suggesting improved purchase performance despite lower CTR.

Based on the statistical analysis and business metrics, the Test campaign may be preferred if the business goal is maximizing conversions rather than clicks.

---

# Project Structure

```text
├── ab_testing_project.ipynb
├── ab_testing_dataset.xlsx
├── README.md
```
---

# Author

Abhishek Ujjeli
```
