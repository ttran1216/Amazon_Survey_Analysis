# 📊 Amazon Data Analysis Project

## 📌 Background
This project analyzes Amazon.com purchase behaviors of 5,027 users in the U.S. from 2018 to 2022. It includes purchase history, demographic data, and survey responses collected through an online survey. The data provides insights into consumer spending patterns, shopping preferences, and potential correlations with demographic factors.

## 🎯 Motivation
With the growing e-commerce industry, understanding consumer behavior on Amazon is crucial for businesses, marketers, and researchers. This analysis aims to answer key questions such as:
- Which states have the highest Amazon spending per shopper?
- How do major life changes (e.g., job loss, moving) influence spending habits?
- What demographic groups are the most frequent Amazon shoppers?
- How does income level impact online shopping behavior?

## 🔍 Summary of Findings

### 1. Shopping Frequency by Age Group
<p align="center">
  <img alt="Shopping Frequency by Age Group" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Shopping%20Frequency%20by%20Age%20Group.png">
  <br>
  <em>Figure: Shopping Frequency by Age Group.</em>
</p>

- **Key Insight**: Younger individuals, especially those between the ages of 25 and 34, tend to shop the most frequently. A large number of people in this group shop more than 10 times a month.
- **Trend**: As people get older, their shopping frequency decreases. Those aged 65 and older shop the least.
- **Conclusion**: Overall, most people across all age groups shop fewer than 5 times a month.

### 2. Shopping Frequency by Education Level
<p align="center">
  <img alt="Shopping Frequency by Education Level" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Shopping%20Frequency%20by%20Education%20Level.png">
  <br>
  <em>Figure: Shopping Frequency by Education Level.</em>
</p>

- **Key Insight**: People with a Bachelor's degree are the most frequent shoppers compared to other education groups.
- **Trend**: Those with a high school diploma or GED also tend to shop quite frequently.
- **Conclusion**: On the other hand, individuals with only some high school education or less tend to shop much less often.

### 3. Total Spending by State
<p align="center">
  <img alt="Total Spending by State" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Total%20Spending%20by%20State.png">
  <br>
  <em>Figure: Total Spending by State.</em>
</p>

- **Key Insight**: California, Texas, and Florida are the top three states where people spend the most on Amazon.
- **Trend**: Larger states and those on the West Coast generally have higher overall spending on Amazon, while smaller states show lower levels of total spending.
- **Conclusion**: The pattern suggests that there might be a connection between the size of the state’s population and the overall amount spent on Amazon.

### 4. Major Life Changes and Shopping Behavior
<p align="center">
  <img alt="Major Life Changes and Shopping Behavior" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Major%20Life%20Changes%20and%20Shopping%20Behavior.png">
  <br>
  <em>Figure: Major Life Changes and Shopping Behavior.</em>
</p>

- **Key Insight**: The most commonly reported life change is moving to a new residence, followed by job loss.
- **Trend**: Major life events such as having a child or becoming pregnant also seem to have an influence on shopping behavior.
- **Conclusion**: These significant life events have a noticeable impact on shopping habits, leading to changes in how frequently individuals shop.

### 5. Willingness to Sell Personal Data by Education Level
- **Key Insight**: People with a Bachelor's degree are more likely to be willing to sell their personal data compared to those with lower education levels.
- **Trend**: Those with a high school diploma or GED show a slightly lower willingness to sell their personal data, and the willingness is even lower among those with only some high school education or less.
- **Conclusion**: Education level seems to play a role in whether or not individuals are willing to sell their personal data, with higher education leading to a greater likelihood of agreeing to such offers.
This is how you can structure the content in a markdown or raw format.

---

This summary provides a concise interpretation of the dataset, highlighting key trends in Amazon shopping behavior based on demographic factors and life changes.

## Code

This repository contains one Malloy code file:

- [`amazon_transaction.malloynb`](amazon_transaction.malloynb), performs the analysis on Amazon purchase data, exploring spending patterns, shopping frequency, and the impact of major life changes on consumer behavior.

## Data Sources
The dataset consists of the following files:
- **amazon-purchases.csv** – Detailed purchase history of users, including order date, product category, price, and quantity.
- **survey.csv** – Demographic and behavioral data collected from survey responses.
- **fields.csv** – Description of columns in `survey.csv`, linking responses to survey questions.
- **Survey Instrument** – Documentation of the survey methodology and question formats.

**Data Source:** [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YGLYDY)  
The dataset was collected with informed consent, and personally identifiable information (PII) was removed before sharing.

## Licensing
This dataset and project materials are released under the **Apache License 2.0**. You are free to use, modify, and distribute the code and analysis, provided that proper attribution is given.

**Dataset License:** The dataset is provided under the **Creative Commons CC0 1.0 Universal Public Domain Dedication**.  
**Code License:** All scripts, queries, and analysis reports created by **Thien Huong Tran** for the **MSBA-622-01 Data Science for Business (Spring 2025)** course at **Gonzaga University Graduate School of Business** are released under the **Apache License 2.0**. The analysis and code in this repository are shared under the **Apache License 2.0**.

For more details on the dataset licensing, see: [CC0 1.0 License](https://creativecommons.org/publicdomain/zero/1.0/)  
For more details on the code licensing, see: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)


