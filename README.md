# Marketing A/B Test Analysis Dashboard

## 📖 Overview

This Power BI project analyzes the results of a **Marketing A/B Test** by comparing an **Advertisement (Ad)** group against a **Public Service Announcement (PSA)** control group. The dashboard evaluates campaign effectiveness, user conversion behavior, advertisement exposure, and optimal ad timing to support data-driven marketing decisions.

---

## 🎯 Business Problem

Marketing teams frequently conduct A/B tests to determine whether advertisements significantly improve conversion rates compared to a control group. This dashboard helps answer the following questions:

* Was the marketing campaign successful?
* How much of the success can be attributed to advertisements?
* Which ad exposure levels maximize conversions?
* What are the best days and hours to display advertisements?

---

## 📁 Dataset

This project uses the **Marketing A/B Testing** dataset from **Kaggle**.

The dataset compares two user groups:

* **Ad Group:** Users who were shown advertisements.
* **PSA Group:** Users who were shown a Public Service Announcement instead of an advertisement.

### Data Dictionary

| Column            | Description                                                               |
| ----------------- | ------------------------------------------------------------------------- |
| **user id**       | Unique identifier for each user                                           |
| **test group**    | Indicates whether the user belongs to the Ad or PSA group                 |
| **converted**     | Indicates whether the user purchased the product                          |
| **total ads**     | Total number of advertisements viewed by the user                         |
| **most ads day**  | Day on which the user viewed the highest number of advertisements         |
| **most ads hour** | Hour of the day when the user viewed the highest number of advertisements |

---

## 📊 Dashboard Pages

### 1. Campaign Performance

Provides a high-level overview of campaign effectiveness using key performance indicators and interactive visualizations.

**Features**

* Total Users
* Ad Group vs. Control Group Conversion Rate
* Conversion Rate Lift
* Average Ads Seen
* Conversion Rate by Exposure Bucket
* Average Ads Seen vs. Conversion Rate Analysis
* Key Business Insights

---

### 2. Ad Timing Optimizer

Analyzes user engagement across different days and hours to identify the most effective advertisement timing.

**Features**

* Best Hour
* Best Day
* Best Performing Time Slot
* Overall Conversion Rate
* Hourly Conversion Trends
* Daily Conversion Comparison
* Day & Hour Heatmap
* Weekday vs. Weekend Analysis

---

## 💡 Key Business Insights

* The advertisement campaign outperformed the PSA control group.
* The Ad group achieved a **2.55% conversion rate**, compared to **1.79%** for the Control group.
* The campaign achieved a **43.09% conversion rate lift** over the Control group.
* Users exposed to **101–250 advertisements** recorded the highest conversion rate.
* **4 PM** was identified as the highest-performing hour.
* **Monday** generated the highest overall conversion rate.
* Conversion rates generally increased with higher advertisement exposure.

---

## 🛠️ Tools Used

* Microsoft Power BI
* DAX (Data Analysis Expressions)
* Power Query
* Microsoft Excel
* Data Modeling

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Measures
* KPI Development
* Interactive Dashboard Design
* Marketing Analytics
* A/B Test Analysis
* Business Intelligence
* Data Visualization

---

## 📂 Repository Structure

```text
marketing-ab-test-analysis/
│
├── Marketing AB Test.pbix
├── dataset/
│   └── marketing_ab_test.xlsx
├── screenshots/
│   ├── campaign-performance.png
│   └── ad-timing-optimizer.png
└── README.md
```

---

## 🖼️ Dashboard Preview

### Campaign Performance

<img width="1168" height="656" alt="Campaign Performance Dashboard" src="https://github.com/user-attachments/assets/e59896ee-8ec9-43b6-8bf2-d05ef9ddd504" />

### Ad Timing Optimizer

<img width="1169" height="654" alt="Ad Timing Optimizer Dashboard" src="https://github.com/user-attachments/assets/54ed9d38-eaf9-4ed0-a44c-190881c8e0a4" />

---

## 👩‍💻 Author

**Varnika**

* GitHub: https://github.com/VarnikaGithub
* LinkedIn: https://www.linkedin.com/in/varnika-v-n-22j
