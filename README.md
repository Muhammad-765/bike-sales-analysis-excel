# 🚲 Bike Sales Analysis & Customer Purchase Dashboard

## 📊 Project Overview

This project analyzes customer demographic, financial, geographic, and behavioral data to identify patterns associated with bicycle purchases.

Using Microsoft Excel, the project transforms raw customer data into a structured analytical dataset and interactive dashboard. The analysis focuses on customer characteristics such as income, age, gender, marital status, education, occupation, commute distance, region, home ownership, number of cars, and number of children.

The goal was to understand which customer segments show stronger bicycle purchasing behavior and identify patterns that could support targeted marketing and business decisions.

---

## 🎯 Business Objective

The primary objective was to analyze customer characteristics and answer questions such as:

* What percentage of customers purchased a bike?
* Does income differ between purchasers and non-purchasers?
* Which age groups are more likely to purchase a bike?
* How does commute distance relate to purchase behavior?
* Which regions have the highest purchase rates?
* How do marital status, education, and occupation relate to purchasing behavior?
* Are there noticeable differences in purchasing behavior based on household characteristics?

---

## 🗂️ Dataset Overview

The original dataset contains **1,026 records**.

After data preparation and structuring, **1,000 records** were used for the main analysis.

The analytical dataset contains information about:

* Customer demographics
* Income
* Education
* Occupation
* Marital status
* Gender
* Age
* Number of children
* Number of cars
* Home ownership
* Commute distance
* Region
* Bike purchase status

---

## 📌 Dataset Summary

| Metric                |   Value |
| --------------------- | ------: |
| Records analyzed      |   1,000 |
| Bike purchasers       |     481 |
| Non-purchasers        |     519 |
| Overall purchase rate |   48.1% |
| Average income        | $56,360 |
| Average age           |   44.16 |
| Average children      |    1.90 |
| Average cars          |    1.44 |

---

## 🛠️ Tools & Techniques

### Microsoft Excel

* Data cleaning and preparation
* Data standardization
* Categorization
* Calculated columns
* PivotTables
* Pivot-based analysis
* Dashboard development
* Data visualization
* Segmentation
* Comparative analysis

---

## 📈 Key Findings

### 🚲 Overall Purchase Behavior

Out of the 1,000 customers analyzed:

* **481 customers purchased a bike**
* **519 customers did not purchase a bike**
* Overall purchase rate: **48.1%**

This provides a relatively balanced dataset for comparing purchaser and non-purchaser characteristics.

---

### 💰 Income & Bike Purchase
<img width="867" height="341" alt="Screenshot 2026-08-04 023401" src="https://github.com/user-attachments/assets/4e87572a-7ab0-4361-9b47-5c6c8844eb9b" />



Average income among customers who purchased a bike was approximately **$57,962.58**, compared with **$54,874.76** among customers who did not purchase one.

This represents an observed difference of approximately **$3,088** in average income.

The result suggests a potential relationship between income and purchase behavior, although the analysis does not establish causation.

---

### 👥 Gender Analysis

Purchase rates were relatively similar between genders:

| Gender | Purchase Rate |
| ------ | ------------: |
| Female |         48.9% |
| Male   |         47.4% |

The small difference suggests that gender alone was not a major differentiating factor in this dataset.

---

### 💍 Marital Status

A larger difference appears when comparing marital status:

| Marital Status | Purchase Rate |
| -------------- | ------------: |
| Single         |         54.1% |
| Married        |         42.9% |

Single customers had a noticeably higher bike purchase rate than married customers in the analyzed dataset.

---

### 🛣️ Commute Distance
<img width="836" height="307" alt="image_2026-08-04_023824194" src="https://github.com/user-attachments/assets/bc5f6adf-4c40-48a1-b6a6-6970ad992436" />


Commute distance produced one of the clearest patterns in the analysis.

| Commute Distance   | Purchase Rate |
| ------------------ | ------------: |
| 0–1 Miles          |         54.6% |
| 1–2 Miles          |         45.6% |
| 2–5 Miles          |         58.6% |
| 5–10 Miles         |         39.6% |
| More than 10 Miles |         29.7% |

The **2–5 mile group recorded the highest purchase rate at 58.6%**, while customers commuting more than 10 miles had the lowest purchase rate at 29.7%.

The results suggest that commute distance may be an important variable for understanding bicycle purchase behavior.

---

### 🌎 Regional Analysis

| Region        | Purchase Rate |
| ------------- | ------------: |
| Pacific       |         58.9% |
| Europe        |         49.3% |
| North America |         43.3% |

The Pacific region had the highest observed purchase rate at **58.9%**, while North America had the lowest at **43.3%**.

---

### 🎂 Age Analysis
<img width="862" height="321" alt="Screenshot 2026-08-04 023427" src="https://github.com/user-attachments/assets/f6ff9e01-9009-4bb9-914f-14f5145ce3db" />


The dataset was segmented into three age brackets.

| Age Bracket | Purchase Rate |
| ----------- | ------------: |
| Middle age  |         54.6% |
| Adolescence |         35.5% |
| Old         |         31.2% |

The **Middle age** segment had the highest purchase rate at **54.6%**.

---

### 💼 Occupation Analysis

| Occupation     | Purchase Rate |
| -------------- | ------------: |
| Professional   |         54.3% |
| Clerical       |         49.7% |
| Manual         |         46.2% |
| Skilled Manual |         45.1% |
| Management     |         42.2% |

Professionals recorded the highest purchase rate among the occupation groups at **54.3%**.

---

## 🔍 Key Business Insights

### 1. Commute distance is a strong differentiator

Customers with a **2–5 mile commute** had the highest purchase rate, while customers commuting more than 10 miles had the lowest.

This could be useful when designing targeted marketing campaigns around practical commuting distances.

### 2. Single customers show higher purchase rates

Single customers had a **54.1% purchase rate**, compared with **42.9% among married customers**.

This suggests marital status could be useful as one variable within customer segmentation.

### 3. Regional differences are visible

The Pacific region had a substantially higher purchase rate than North America, suggesting potential differences in market characteristics or customer behavior.

### 4. Middle-aged customers are the strongest age segment

The Middle age group recorded a **54.6% purchase rate**, significantly higher than the Adolescence and Old segments.

### 5. Gender is not a major differentiator

Male and female purchase rates were relatively close, suggesting that marketing segmentation based solely on gender may provide limited differentiation.

### 6. Purchasers have slightly higher average income

Bike purchasers had a higher average income than non-purchasers, although the difference should be interpreted as an association rather than a causal relationship.

---

## 📊 Dashboard
<img width="840" height="571" alt="Screenshot 2026-08-04 023324" src="https://github.com/user-attachments/assets/2706d45f-0f32-4621-a50e-baf44b8323ef" />


The final Excel dashboard presents the analysis in a visual format designed to make customer purchasing patterns easier to understand.

The dashboard is supported by analytical worksheets containing:

* Cleaned customer data
* Calculated age brackets
* PivotTable analysis
* Purchase segmentation
* Demographic comparisons
* Commute-distance analysis
* Regional analysis

---

## 📁 Workbook Structure

```text
bike_buyers
    Original customer dataset

Working sheet
    Cleaned and structured analytical dataset

Pivot table
    PivotTable-based analysis

Dashboard
    Final visual dashboard
```

---

## 💼 Business Applications

The analysis could support decisions related to:

* Customer segmentation
* Targeted marketing
* Regional campaign planning
* Commuter-focused product positioning
* Customer profiling
* Market prioritization
* Promotional strategy

For example, businesses could investigate whether customers with **2–5 mile commutes** represent a particularly attractive segment for bicycle-focused campaigns.

---

## 📚 Skills Demonstrated

### Data Analytics

Data cleaning · Data preparation · Data transformation · Segmentation · Exploratory analysis · Comparative analysis · Business insights

### Microsoft Excel

PivotTables · Calculated columns · Data categorization · Data visualization · Dashboard development · Spreadsheet analysis

### Business Analytics

Customer segmentation · Purchase behavior analysis · Demographic analysis · Geographic analysis · Behavioral pattern identification

---

## 🚀 Project Outcome

The project transformed a raw customer dataset into a structured Excel analysis and dashboard that highlights the characteristics associated with bicycle purchasing behavior.

The analysis demonstrates how Excel can be used to move from **raw customer data → structured analysis → visual insights → business recommendations**.

The project also demonstrates the importance of comparing customer segments rather than relying on a single demographic variable when analyzing purchase behavior.
