# 📞 Maven Telecom Churn Report <img src="..\_assets\power-bi.png" align="right" width="80" /><!-- omit in toc -->

# 📝 Table Content<!-- omit in toc -->
- [📊 Dashboard](#-dashboard)
- [🗃️ Dataset](#️-dataset)
- [🔄 Data Preprocessing](#-data-preprocessing)
- [🛠️ Solution](#️-solution)
  - [💰 Revenue Summary Page](#-revenue-summary-page)
  - [💸 Monthly Charge Summary Page](#-monthly-charge-summary-page)
- [🖋 Conclusion](#-conclusion)
- [🙏 Acknowledgements](#-acknowledgements)

# 📊 Dashboard

<div style="display: flex; justify-content: center;">
  <div style="margin-right: 20px;">
    <img src="Assets\Maven Telecom Churn Report_page-1.jpg" width="800">
  </div>
  <div>
    <img src="Assets\Maven Telecom Churn Report_page-2.jpg" width="800">
  </div>
</div>

# 🗃️ [Dataset](https://mavenanalytics.io/challenges/maven-churn-challenge/6)

The Maven Communications Churn Dataset provides detailed insights into customer demographics, service usage, and churn status in the telecom sector. Designed for use with Power BI, it supports analysis aimed at identifying churn patterns and developing retention strategies.

# 🔄 Data Preprocessing

The raw dataset was preprocessed using Python in Google Colab to clean the data and engineer new features to better understand customer churn. This included:

### 🔬📐 Feature Engineering | Customer Value Metric (CVM)<!-- omit in toc -->

➡ Aligning with the Challenge Objective:

You've been hired to help the company improve retention by identifying high-value customers and churn risks. Present your findings to the CMO in a single-page report or dashboard.

While the dataset lacks a direct customer value metric, such as "Customer Lifetime Value" (CLV) we'll create one through feature engineering, leveraging existing data.

### 🧮 Calculating the (CVM) Customer Value Metric<!-- omit in toc -->

To Calculate the (CVM), we'll use a correlation matrix to assess relationships between each column and the Customer Status column. This matrix provides correlation coefficients, uncovering potential indicators of customer value.

Using these coefficients, we identify columns strongly linked to customer status. Further analysis will help reveal and examine patterns aligning with high customer value or churn risks.

### 🏃‍♂️ Churn Metric Risk Calculation<!-- omit in toc -->

The Churn Risk Metric utilizes a deviation approach to assess the risk associated with customer churn. The calculation involves a series of steps to determine the impact of various variables on the likelihood of customer churn.

1. Calculate the Baseline Churn Ratio (Total Churn Ratio):
   - Determine the initial churn ratio among customers to establish a baseline for subsequent analysis.

2. Variable Selection:

   - Identify and select relevant variables that may influence customer churn. This step is critical for understanding the factors contributing to churn risk.

3. Deviation Calculation (From the Total Churn Ratio):

   - Calculate the deviation of each variable from the baseline churn ratio. This enables the assessment of the individual impact of each variable on customer churn.

4. Churn Risk Rating Calculation:

   - Compute the Churn Risk Rating by aggregating the deviations from each variable. This step quantifies the overall churn risk associated with the selected variables.

5. Churn Risk Rating Normalization:

   - Normalize the Churn Risk Rating for consistency and comparability. This standardization ensures a uniform rating across different variables.

6. Re-categorizing Customer Status:

   - Based on the Churn Risk Rating, re-categorize customer status to reflect the level of churn risk. This categorization facilitates strategic decision-making and targeted interventions.

**The preprocessed dataset was then loaded into Power BI for analysis and dashboard creation.**

> [!IMPORTANT]
> See the [Data Preprocessing Notebook](https://colab.research.google.com/drive/1y6FjBDC6MfQq_59otNqam2S9e3yPox9W?usp=sharing) for the full data preparation code.
> 
> [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hossam-elshabory/MS-Power-BI-Projects/blob/main/Maven%20Telecom%20Churn%20Dashboard%20(Report)/Maven_Telecom_Churn_Analysis_Data_Preprocessing.ipynb)

# 🛠️ Solution

> [!NOTE]
> The Maven Communications Churn dashboard solution is a two-page Power BI report.

## 💰 Revenue Summary Page

<details>
<summary>Click To View The Page</summary>

<div style="text-align:center"><img src="Assets\Maven Telecom Churn Report_page-1.jpg" /></div>

</details>

The **Maven Telecom Churn Report** is a comprehensive Power BI analysis of customer churn data for a telecom company in California. It intricately breaks down the revenue lost, retained, and gained from various customer segments, unveiling that **26.54%** of customers churned, resulting in a substantial loss of **$3.68M** in revenue.

The report meticulously compares the impact of different offers and contract lengths on customer retention, revealing notably high churn rates associated with **Offer E** and **Month-to-Month** contracts. Moreover, it identifies competition, dissatisfaction, and attitude as the primary reasons for customer departure and provides strategic recommendations to augment customer loyalty.

## 💸 Monthly Charge Summary Page

<details>
<summary>Click To View The Page</summary>

<div style="text-align:center"><img src="Assets\Maven Telecom Churn Report_page-2.jpg" /></div>
</details>

This report page shows that **Maven Telecom's customer churn** is related to the **monthly charge**, as customers who left paid more than the average for their account type. It also identifies some accounts that are still with Maven Telecom but have similar characteristics to the churned ones, and suggests they are at **risk of churning**.

****

# 🖋 Conclusion 

- **Improve/discontinue Offer E** - This offer has the highest churn rate and does not retain customers well.

- **Ensure all customers receive promotional offers** - Customers without offers are more likely to leave. Promotions incentivize loyalty.

- **Promote longer 1 & 2 year contracts** - These contracts have higher retention rates and lower churn rates.

- **Reduce churn of Month-to-Month contracts** - This contract has the highest churn rate and needs more strategies to improve customer retention.

- **Address competition, dissatisfaction, poor attitude as top churn drivers** - These are the main reasons why customers leave and cause revenue loss.

# 🙏 Acknowledgements 

This Power BI project was inspired by various project submissions for the [Maven Telecom Churn Analysis Challenge](https://mavenanalytics.io/challenges/maven-churn-challenge/6).

The following links showcase project submissions that served as inspiration for this project:

- [Gerard Duggan Blog Project Blog Post](https://dg-analysis.com/2022/08/06/telecoms-churn-maven-challenge/).
- [shruti bhagi's Maven Challenge Submission](https://mavenanalytics.io/project/7119).
- [Lucia Stefanuto's Maven Challenge Submission](https://mavenanalytics.io/project/378).