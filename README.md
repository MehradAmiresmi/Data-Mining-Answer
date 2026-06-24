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

