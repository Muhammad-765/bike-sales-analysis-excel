# 🚲 Customer Demographic & Bike Purchase Behavior Analysis

## 📊 Project Overview

This project analyzes **customer demographic, financial, geographic, and behavioral data** to identify patterns associated with bicycle purchasing behavior.

Using **Microsoft Excel**, the project transforms raw customer data into a structured analytical dataset and interactive dashboard. The analysis focuses on customer characteristics such as:

* Income
* Age
* Gender
* Marital status
* Education
* Occupation
* Commute distance
* Region
* Home ownership
* Number of cars
* Number of children
* Bike purchase status

The goal is to understand which customer segments demonstrate stronger bicycle purchasing behavior and identify patterns that could support **targeted marketing, customer segmentation, and business decision-making**.

---

## 🎯 Business Objectives

The analysis was designed to answer practical business questions such as:

* What percentage of customers purchased a bike?
* Does income differ between purchasers and non-purchasers?
* Which age groups have the highest purchase rates?
* How does commute distance relate to bike purchase behavior?
* Which regions have the highest purchase rates?
* How do marital status, education, and occupation relate to purchasing behavior?
* Which demographic combinations represent potential high-value customer segments?
* How can customer characteristics be used to improve targeted marketing?
* Where are potential opportunities to improve bike purchase conversion?

---

## 📌 Executive Summary

The analysis identified several notable patterns in customer bike purchasing behavior.

### 🔑 Key Findings

* **481 out of 1,000 customers** purchased a bike, resulting in an overall purchase rate of **48.1%**.
* Bike purchasers recorded a higher average income than non-purchasers.
* The **Middle-Age (31–54)** segment recorded the highest observed purchase rate at **54.6%**.
* Customers with a **2–5 mile commute** recorded the highest purchase rate at **58.6%**.
* Customers commuting more than **10 miles** recorded the lowest purchase rate at **29.7%**.
* The **Pacific region** recorded the highest purchase rate at **58.9%**.
* **Professional** customers recorded the highest purchase rate among occupation groups at **54.3%**.
* Gender showed relatively limited differentiation compared with variables such as commute distance, age, and marital status.
* Single customers recorded a higher purchase rate than married customers.

> **Note:** These findings represent observed associations within the dataset and should not be interpreted as evidence of causation.

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

## 📊 Dataset Summary

| Metric | Value |
| :--- | ---: |
| Records analyzed | 1,000 |
| Bike purchasers | 481 |
| Non-purchasers | 519 |
| Overall purchase rate | 48.1% |
| Average income | $56,360 |
| Average age | 44.16 |
| Average children | 1.90 |
| Average cars | 1.44 |

---

## 🛠️ Data Preparation & Analytical Methodology

The project followed a structured Excel analytics workflow:

``text 
Raw Customer Dataset
        ↓
Data Cleaning & Standardization
        ↓
Feature Engineering
        ↓
PivotTable Analysis
        ↓
Customer Segmentation
        ↓
Interactive Dashboard
        ↓
Business Insights
        ↓
Strategic Recommendations

## 🧹 Data Cleaning & Standardization

The raw customer dataset was prepared for analysis through:

* Duplicate identification and removal
* Data standardization
* Categorical value normalization
* Marital status standardization
* Gender standardization
* Data structuring for PivotTable analysis

Examples of standardized categorical values included:

M → Male
F → Female

M → Married
S → Single

## 🧩 Feature Engineering

Custom age brackets were created using Excel IF logic to make demographic comparisons easier.

| Age Group      | Age Range |
| -------------- | --------: |
| **Young**      |      < 31 |
| **Middle-Age** |     31–54 |
| **Old**        |       55+ |

These categories were then used throughout the analysis to compare purchasing behavior across different customer age segments.

## 📊 Dynamic Analytics

The analysis used PivotTables and Slicers to create dynamic cross-tabulations for:

* Purchase conversion rates
* Income levels
* Age groups
* Commute distances
* Education
* Occupation
* Gender
* Marital status
* Geographic regions

# 📈 Key Findings
## 🚲 1. Overall Purchase Behavior

Out of the 1,000 customers analyzed:

* 481 customers purchased a bike
* 519 customers did not purchase a bike
* Overall purchase rate: 48.1%

This provides a relatively balanced dataset for comparing purchaser and non-purchaser characteristics.

### 💼 Business Interpretation

The relatively balanced split allows meaningful comparison between customers who purchased a bike and those who did not.

## 💰 2. Income & Bike Purchase
<img width="867" height="341" alt="purchase behavior" src="https://github.com/user-attachments/assets/df25cb6b-8f52-47f4-bb10-3597c51acf26" />


Average income among customers who purchased a bike was approximately $57,962.58, compared with $54,874.76 among customers who did not purchase one.

This represents an observed difference of approximately $3,088 in average income.

### 💼 Business Interpretation

Bike purchasers showed somewhat higher income levels than non-purchasers.

This may make income useful as part of customer segmentation, although the observed difference should be interpreted as an association rather than a causal relationship.

## 👥 3. Gender Analysis

Purchase rates were relatively similar between genders:

| Gender     | Purchase Rate |
| ---------- | ------------: |
| **Female** |         48.9% |
| **Male**   |         47.4% |

### 💼 Business Interpretation

The relatively small difference suggests that gender alone is not a major differentiating factor in this dataset.

Marketing segmentation should therefore consider multiple customer characteristics rather than relying solely on gender.

## 💍 4. Marital Status Analysis

A more noticeable difference appears when comparing marital status:

| Marital Status | Purchase Rate |
| -------------- | ------------: |
| **Single**     |         54.1% |
| **Married**    |         42.9% |

Single customers recorded a noticeably higher observed bike purchase rate than married customers.

### 💼 Business Interpretation

Marital status may provide additional value as one variable within a broader customer segmentation strategy.

## 🛣️ 5. Commute Distance Analysis
<img width="836" height="307" alt="Commute Distance" src="https://github.com/user-attachments/assets/3b4532f4-f04b-4147-9ec9-70e24efea384" />


Commute distance produced one of the clearest patterns in the analysis.

| Commute Distance       | Purchase Rate |
| ---------------------- | ------------: |
| **0–1 Miles**          |         54.6% |
| **1–2 Miles**          |         45.6% |
| **2–5 Miles**          |     **58.6%** |
| **5–10 Miles**         |         39.6% |
| **More than 10 Miles** |     **29.7%** |

The 2–5 mile group recorded the highest purchase rate at 58.6%, while customers commuting more than 10 miles had the lowest purchase rate at 29.7%.

### 💼 Business Interpretation

Commute distance appears to be one of the strongest differentiating variables in the dataset.

Purchase rates decline considerably among customers commuting more than 5 miles, suggesting an opportunity to investigate alternative transportation preferences among longer-distance commuters.

Note: The results demonstrate an observed relationship between commute distance and purchase behavior, not a causal threshold.

## 🌎 6. Regional Analysis
| Region            | Purchase Rate |
| ----------------- | ------------: |
| **Pacific**       |     **58.9%** |
| **Europe**        |         49.3% |
| **North America** |         43.3% |

The Pacific region had the highest observed purchase rate at 58.9%, while North America recorded the lowest at 43.3%.

### 💼 Business Interpretation

Regional differences suggest that geographic segmentation may be useful when allocating marketing resources and evaluating potential market opportunities.

## 🎂 7. Age Analysis
<img width="862" height="321" alt="Customer segmentation" src="https://github.com/user-attachments/assets/808a8676-60a1-4886-bd5b-bc040c71a6c8" />


The dataset was segmented into three age brackets.

| Age Group              | Purchase Rate |
| ---------------------- | ------------: |
| **Middle-Age (31–54)** |     **54.6%** |
| **Young (<31)**        |         35.5% |
| **Old (55+)**          |         31.2% |

The Middle-Age segment had the highest purchase rate at 54.6%.

### 💼 Business Interpretation

The Middle-Age customer segment may represent an attractive target for bicycle marketing campaigns within this dataset.

## 💼 8. Occupation Analysis
| Occupation         | Purchase Rate |
| ------------------ | ------------: |
| **Professional**   |     **54.3%** |
| **Clerical**       |         49.7% |
| **Manual**         |         46.2% |
| **Skilled Manual** |         45.1% |
| **Management**     |         42.2% |

Professionals recorded the highest purchase rate among the occupation groups at 54.3%.

### 💼 Business Interpretation

Occupation can provide useful context when combined with income, age, and commute distance to identify customer segments with stronger purchasing behavior.

## 🔍 Customer Segmentation

The analysis demonstrates that customer behavior becomes more informative when multiple characteristics are evaluated together.

Potential segmentation variables include:

Age
  +
Income
  +
Occupation
  +
Commute Distance
  +
Region
  +
Marital Status
        ↓
Customer Segment
        ↓
Purchase Behavior

### 🎯 Potential Customer Persona

The strongest observed patterns suggest that a potentially attractive customer segment may include customers who are:

* Middle-Age
* Higher income
* Professional
* Living or working within a short-to-moderate commuting distance
* Located in stronger-performing geographic markets

These characteristics should be treated as targeting hypotheses, not guaranteed predictors of purchase behavior.

## 💡 Key Business Insights
### 1. 🛣️ Commute Distance Is a Strong Differentiator

Customers with a 2–5 mile commute recorded the highest purchase rate, while customers commuting more than 10 miles recorded the lowest.

This could support targeted campaigns focused on practical commuting and short-distance mobility.

### 2. 💍 Single Customers Show Higher Purchase Rates

Single customers had a 54.1% purchase rate, compared with 42.9% among married customers.

Marital status may therefore be useful as one component of customer segmentation.

### 3. 🌎 Regional Differences Are Visible

The Pacific region recorded a substantially higher purchase rate than North America.

This suggests potential differences in market characteristics, customer preferences, or transportation behavior.

### 4. 🎂 Middle-Age Customers Are the Strongest Age Segment

The Middle-Age group recorded a 54.6% purchase rate, significantly higher than the Young and Old segments.

### 5. 👥 Gender Is Not a Major Differentiator

Male and female purchase rates were relatively close.

This suggests that segmentation based solely on gender may provide limited differentiation.

### 6. 💰 Purchasers Have Slightly Higher Average Income

Bike purchasers had a higher average income than non-purchasers.

However, the difference should be interpreted as an observed association rather than evidence of causation.

## 📊 Interactive Dashboard
<img width="840" height="571" alt="demographic analysis" src="https://github.com/user-attachments/assets/e735aa91-a60d-47e5-b542-dd4067ad0d49" />


The final Microsoft Excel dashboard presents the analysis in a visual and interactive format designed to make customer purchasing patterns easier to understand.

Dashboard Components
* 🚲 Bike Purchase KPIs
* 💰 Income Analysis
* 🎂 Age Analysis
* 👥 Gender Comparison
* 💍 Marital Status Analysis
* 🛣️ Commute Distance Analysis
* 🌎 Regional Comparison
* 💼 Occupation Analysis
* 📊 Purchase Rate Comparisons
* 🎛️ Interactive Filters / Slicers

The dashboard is supported by analytical worksheets containing:

* Cleaned customer data
* Calculated age brackets
* PivotTable analysis
* Purchase segmentation
* Demographic comparisons
* Commute-distance analysis
* Regional analysis

## 💼 Strategic Business Recommendations
### 1. 🎯 Target Short-Commute Customers

Customers with shorter commutes demonstrated stronger purchase rates.

Recommendation: Focus digital marketing and local campaigns on customers living or working within approximately 2 miles of major commercial or business areas.

### 2. 🛣️ Address Long-Commute Drop-Off

Purchase rates declined considerably among customers commuting more than 5 miles.

Recommendation: Test whether e-bikes, commuter-focused products, financing options, or promotional pricing can improve conversion among longer-distance commuters.

### 3. 💼 Focus on Professional Customer Segments

Professional customers demonstrated the highest purchase rate among the occupation groups analyzed.

Recommendation: Explore targeted campaigns and corporate partnerships with professional workplaces and organizations.

### 4. 🌎 Prioritize High-Performing Regions

The Pacific region recorded the highest observed purchase rate.

Recommendation: Consider regional campaign optimization and investigate whether infrastructure, cycling culture, transportation patterns, or other market conditions contribute to the difference.

### 5. 🎂 Target the Middle-Age Segment

The Middle-Age group recorded the highest purchase rate.

Recommendation: Develop campaigns focused on practical commuting, recreation, health, and lifestyle benefits for customers within this age segment.

### 6. 💰 Consider Income-Based Segmentation

Purchasers demonstrated somewhat higher average income levels than non-purchasers.

Recommendation: Test differentiated product positioning and promotional strategies across income segments.

### 7. 👥 Avoid Gender-Only Targeting

Gender showed relatively small differences in purchase rates.

Recommendation: Prioritize behavioral and contextual characteristics such as commute distance, age, occupation, income, and region over gender-only targeting.

## 📚 Skills Demonstrated
### 📊 Data Analytics

Data Cleaning · Data Preparation · Data Transformation · Feature Engineering · Customer Segmentation · Exploratory Data Analysis · Comparative Analysis · Business Insights

### 📗 Microsoft Excel

PivotTables · Calculated Columns · IF Logic · Data Categorization · Data Visualization · Dashboard Development · Slicers · Spreadsheet Analysis

### 💼 Business Analytics

Customer Segmentation · Purchase Behavior Analysis · Demographic Analysis · Geographic Analysis · Behavioral Pattern Identification · Market Prioritization · Marketing Analytics · Business Recommendations

## 🛠️ Tools & Technologies
Tool / Technology	Purpose
Microsoft Excel	Data preparation, analysis, visualization, and dashboard development
PivotTables	Aggregation and customer segmentation
Slicers	Interactive filtering
Excel Formulas	Feature engineering and categorization
Charts & Visualizations	Communicating analytical findings
## 📁 Workbook Structure

```text
bike-sales-analysis-excel/
│
├── data/
│   └── bike_buyers.xlsx
│
├── analysis/
│   └── pivot_tables.xlsx
│
├── dashboard/
│   └── bike_sales_dashboard.xlsx
│
├── screenshots/
│   ├── dashboard_preview.png
│   ├── income_analysis.png
│   ├── commute_analysis.png
│   └── age_analysis.png
│
├── README.md
└── .gitignore
```


## ▶️ How to Run
### 1. Open the Workbook

```bash
Open the Excel workbook in Microsoft Excel.
```

### 2. Review the Working Sheet

```bash
Explore the cleaned and structured customer dataset.
```

### 3. Review the Analytical Worksheets
```text
Navigate through the PivotTables and supporting calculations used to analyze:
```

* Demographics
* Income
* Age
* Occupation
* Commute distance
* Region
* Purchase behavior

### 4. Explore the Dashboard

Use the interactive dashboard and available slicers to filter customer segments and observe how purchase rates change.

## 💼 Business Applications

The analysis could support decisions related to:

* 🎯 Customer segmentation
* 📢 Targeted marketing
* 🌎 Regional campaign planning
* 🚴 Commuter-focused product positioning
* 👤 Customer profiling
* 📍 Market prioritization
* 💰 Promotional strategy
* 🏢 Corporate wellness partnerships

For example, businesses could investigate whether customers with short-to-moderate commutes and professional occupations represent an attractive segment for bicycle-focused campaigns.

## 🚀 Future Development

The Excel analysis can be extended into a more advanced Business Intelligence solution using Power BI.

### Potential Enhancements
* Interactive Power BI dashboard
* Dynamic customer segmentation
* Geographic visualizations
* Advanced KPI tracking
* Drill-down analysis
* Automated data refresh
* Cross-filtering across demographic segments
* Purchase-propensity analysis
### 🔄 Future Analytics Pipeline

```text
Raw Customer Data
        ↓
Excel Data Preparation
        ↓
Exploratory Analysis
        ↓
Interactive Excel Dashboard
        ↓
Power BI Dashboard
        ↓
Advanced Customer Segmentation
        ↓
Decision Support
```

## 📌 Project Outcome

This project demonstrates how Microsoft Excel can be used as a complete business analytics tool, from raw customer data preparation to interactive visualization and strategic recommendations.

The project transforms:

Raw Customer Data → Data Cleaning → Feature Engineering → PivotTable Analysis → Customer Segmentation → Interactive Dashboard → Business Insights

The analysis highlights how combining demographic, financial, geographic, and behavioral variables can provide a more meaningful understanding of customer purchase behavior than analyzing individual characteristics in isolation.

## 👨‍💻 Author

### Muhammad

Business Data Analytics Student | Excel | SQL | Power BI | Data Analysis
