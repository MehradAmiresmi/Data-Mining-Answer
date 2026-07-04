# 📊 Data Mining Project – Data Understanding Phase

> This repository contains the **Data Understanding phase** of a data mining project, following the CRISP-DM methodology.

---

## 📌 Overview

In this phase, we focus on gaining a deep understanding of the dataset before moving to modeling.
The goal is to explore data characteristics, identify patterns, and detect potential issues such as imbalance, skewness, and missing values.

---

## 🎯 Objectives

* Understand the structure of the dataset
* Analyze distributions of features
* Detect class imbalance
* Identify skewness and central tendencies (mean, median)
* Explore relationships between variables

---

## 🔍 Data Understanding Steps

### 1. Data Exploration

* بررسی نوع داده‌ها (numerical / categorical)
* بررسی تعداد رکوردها و ستون‌ها

### 2. Statistical Analysis

* محاسبه شاخص‌های آماری:

  * Mean (میانگین)
  * Median (میانه)
  * بررسی چولگی (Skewness)

### 3. Data Visualization

We used various plots to understand distributions and relationships:

* Histogram → بررسی توزیع داده
* Countplot → بررسی فراوانی
* Boxplot → تشخیص outlier
* KDE Plot → بررسی شکل توزیع

### 4. Class Balance Analysis

* بررسی اینکه دیتاست متعادل است یا نه
* تحلیل تعداد نمونه‌های هر کلاس در ستون Target

### 5. Insights Extraction

* شناسایی ویژگی‌های مهم
* بررسی ویژگی‌های skewed
* تاثیر outlierها روی داده

---

## 🛠 Tools & Libraries

* jupyter notebook
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 🔮 Next Step

The next phase of the project will be:

➡️ **Data Preparation**

* Handling missing values
* Feature scaling
* Encoding categorical variables

---

# ❤️ Heart Disease Data Analysis – Data Understanding Phase

---

## 📊 Dataset Overview

The dataset contains medical attributes used to predict the presence of heart disease in patients.

### 🔑 Key Features

* `age` → Age of the patient
* `sex` → Gender (0 = female, 1 = male)
* `cp` → Chest pain type
* `trestbps` → Resting blood pressure
* `chol` → Cholesterol level
* `thalach` → Maximum heart rate achieved
* `oldpeak` → ST depression
* `target` → Presence of heart disease (0 = No, 1 = Yes)

---

## 🔍 Exploratory Data Analysis (EDA)

### 📌 1. Distribution Analysis

* Most features show approximately normal distributions
* Some features such as `chol` and `oldpeak` exhibit noticeable **skewness**
* The `thalach` feature appears relatively normally distributed

---

### 📌 2. Central Tendency (Mean vs Median)

* In skewed features, there is a clear difference between mean and median
* This indicates the presence of **outliers**

👉 **Insight:** Median is more reliable for skewed distributions.

---

### 📌 3. Outlier Detection

Using boxplots:

* Features such as `chol` and `trestbps` contain outliers
* Outliers may negatively affect model performance

---

### 📌 4. Class Balance Analysis

* The target variable shows slight imbalance:

  * Class 0 (No Disease): fewer samples
  * Class 1 (Disease): more samples

👉 **Insight:**

* The dataset is slightly imbalanced

---

### 📌 5. Feature Relationships

* Strong relationships observed between:

  * `cp` (chest pain type) and target
  * `thalach` (maximum heart rate) and target

* Patients with:

  * specific chest pain types
  * higher heart rates
    → tend to have a higher probability of heart disease


---

## 📈 Key Insights

* Presence of skewness in several important features
* Existence of outliers in numerical variables
* Slight imbalance in the target variable
* Certain features have strong predictive power

---

## 🧠 Conclusion

The dataset provides valuable patterns for predicting heart disease.
However, proper preprocessing (handling outliers, scaling, and balancing) is essential before moving to the modeling phase.

---
