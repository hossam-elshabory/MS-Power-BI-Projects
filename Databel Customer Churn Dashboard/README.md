# Databell Customer Churn Dashboard<img src="..\_assets\power-bi.png" align="right" width="80" /><!-- omit in toc -->


# Table Of Content<!-- omit in toc -->
- [Dashboard](#dashboard)
- [Dataset](#dataset)
    - [Dataset Metadata](#dataset-metadata)
- [Solution](#solution)
  - [Overview Page](#overview-page)
  - [Age Group Page](#age-group-page)
- [Conclusion](#conclusion)

# Dashboard

<div style="display: flex; justify-content: center;">
  <div style="margin-right: 20px;">
    <img src="Assets\Overview_page.png" width="800">
  </div>
  <div>
    <img src="Assets\Age_group_page.png" width="800">
  </div>
</div>


# [Dataset](https://github.com/hossam-elshabory/MS-Power-BI-Projects/tree/main/Databel%20Customer%20Churn%20Dashboard/Dataset)
The Databell dataset is a fictional dataset that includes information on customer demographics, usage data, and churn status for a telecom company.

The goal of this dataset is to provide insights into customer churn rates and identify strategies to reduce churn. The dataset is well-structured and easy to work with in Power BI, and includes features such as customer demographics, service usage data, and churn status.

By analyzing these data points, the resulting report pages will provide valuable insights into customer churn and allow the telecom company to take targeted actions to improve customer retention rates.

### Dataset Metadata
<details>
  <summary>Click to View Dataset MetaData</summary>

#### Customer Status:<!-- omit in toc -->
| Field Name  | Description                                            |
|-------------|--------------------------------------------------------|
| Customer ID | The unique ID that identifies a customer               |
| Churn Label | Contains “Yes” or “No” to indicate if a customer churned |
| Churn Reason| The particular reason why the customer ended the contract |
| Churn Category | Groups multiple churn reasons together for analysis purposes |
| Under 30 | Indicates if the customer is under 30 with “Yes” or “No” |
| Senior | Indicates if the customer is 65 or above with “Yes” or “No” |
| Age | The age of the customer |
| Gender | The gender of the customer, indicated by “Male”, “Female” or “Prefer not to say” |

#### Contract Information:<!-- omit in toc -->
| Field Name        | Description                                                |
|-------------------|------------------------------------------------------------|
| Group Contract    | Indicates if the customer is part of a group contract. A group contract offers advantages and is generally cheaper. Contains “Yes” or “No” |
| Number of customers in a group | Number of customers part of the group |
| Group Phone Number | Phone number of the group |
| State | The code of the state where the customer lives |
| Payment Method | Preferred payment method of the customer indicated with “Credit Card”, “Direct Debit” or “Paper Check |
| Contract Type | Contains “Month to Month”, “One Year” or “Two Year” |

#### Subscription Types & Charges:<!-- omit in toc -->
| Column Name | Description |
| --- | --- |
| Customer ID | The unique ID that identifies a customer |
| Account Length (in months) | The number of months the customer has been with Databel |
| Local Calls | Amount of local (within the US) calls from the customer |
| Intl Calls | Amount of international (outside the US) calls from the customer |
| Intl Mins | The number of minutes spent calling internationally |
| Intl Plan | Intl Active: Indicates if the customer called internationally with a “Yes” or “No” |
| Extra International Charges | Contains the extra charges for international calls for customers who are not on an international plan |
| Customer Service Calls | The number of calls made to customer service |
| Avg Monthly GB Download | Contains the average monthly download volume in gigabytes |
| Unlimited Data Plan | Indicates if the customer has free unlimited download capacity with “Yes” or “No”. This premium is reflected in the amount of the monthly charge |
| Extra Data Charges | Contains the extra charges for data downloads for customers who are not on an unlimited plan |
| Monthly Charges | Average of all Monthly Charges to the customer |
| Total Charges | Sum of all monthly charges |

</details>

****

# Solution

Data bell Customer Churn dashboard solution is a two-page Power BI report.

## Overview Page

<details>
<summary>Click To View The Page</summary>

<div style="text-align:center"><img src="Assets\Overview_page.png" /></div>

</details>

The main overview page of the Data Bell customer churn report presents a comprehensive view of the customer churn data. It provides key metrics such as the total number of customers, churn rate, and the number of customers who churned. Additionally, it includes a map that displays the churn rate by state in the United States.

The page also features a bar graph that shows the reasons why customers churned, providing insights into the most common reasons behind customer churn. This information can be used to identify areas for improvement and develop strategies to reduce churn.

Furthermore, two doughnut charts are included on the page. The first chart displays customers by contract type, providing insight into the types of contracts that are most popular among customers. The second doughnut chart shows the churn rate by category of churn reasons, providing further insights into why customers are leaving.

Overall, the main overview page of the Data Bell customer churn report provides a comprehensive view of the customer churn data, making it easy for stakeholders to understand the key metrics and take targeted actions to reduce churn.

## Age Group Page

<details>
<summary>Click To View The Page</summary>

<div style="text-align:center"><img src="Assets\Age_group_page.png" /></div>
</details>

The Age Group page of the Data Bell Customer Churn Power BI report provides valuable insights into customer behavior and churn rates by age group. 

The page includes a line graph showing the churn rate by account length in months, allowing stakeholders to identify trends in customer churn over time. 

A bar and line chart display the average monthly charge and churn rate by customers in group subscriptions, enabling decision-makers to evaluate the impact of group contracts on customer retention rates.
Another bar and line chart provide insights into the churn rate by age groups, allowing stakeholders to identify age-related patterns in customer churn.

The page also includes a filter to change the account length in months, providing stakeholders with a more granular view of customer churn rates. 

Overall, the Age Group page of the Data Bell Customer Churn Power BI report is a valuable tool for stakeholders seeking to improve customer retention rates and reduce churn.

****

# Conclusion
Based on the analysis of the Data Bell customer churn report, the stockholders should take the following actions to retain more customers and lower churn rate:

- Implement strategies to encourage customers to stay longer by providing incentives for long-term contracts, as customers tend to churn less as account length increases.

- Promote group contracts to customers, as they tend to have lower churn rates, which could be achieved by offering discounts or benefits to customers who switch to group contracts.

- Take steps to reduce competition and retain customers by improving customer service, providing better pricing options, and offering personalized packages to meet individual customer needs.

- Focus marketing efforts on customers in the 25 to 35 age group, as they tend to have lower churn rates.

- Address the high churn rate in California, which is over 60%, by conducting a more in-depth analysis to understand the reasons behind it and developing targeted strategies to address them.

- Encourage customers who are making international calls and not on an international plan to upgrade their subscription plans, as these customers tend to pay more and have a higher churn rate. By taking these steps, Data Bell can retain more customers and lower churn rate, which would lead to increased profitability and growth.
