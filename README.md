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
## Summary of Findings

### 1. Shopping Frequency by Age Group
<p align="center">
  <img alt="Shopping Frequency by Age Group" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Shopping%20Frequency%20by%20Age%20Group.png">
  <br>
  <em>Figure: Shopping Frequency by Age Group.</em>
</p>

- Younger age groups (25-34 years) have the highest shopping frequency, with many shopping more than 10 times per month.
- Shopping frequency gradually decreases with age, with those 65 and older shopping the least.
- The majority of shoppers across all age groups shop less than 5 times per month.

### 2. Shopping Frequency by Education Level
<p align="center">
  <img alt="Shopping Frequency by Education Level" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Shopping%20Frequency%20by%20Education%20Level.png">
  <br>
  <em>Figure: Shopping Frequency by Education Level.</em>
</p>

- Individuals with a **Bachelor's degree** have the highest shopping frequency compared to other education levels.
- Those with a **high school diploma or GED** also exhibit relatively frequent shopping behavior.
- Shopping frequency is significantly lower among individuals with only **some high school education or less**.

### 3. Total Spending by State
<p align="center">
  <img alt="Total Spending by State" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Total%20Spending%20by%20State.png">
  <br>
  <em>Figure: Total Spending by State.</em>
</p>

- **California, Texas, and Florida** are the top three states with the highest total spending.
- The **West Coast and larger states** tend to have higher Amazon spending, while smaller states have lower total spending.
- This distribution suggests a correlation between population size and overall Amazon purchases.

### 4. Major Life Changes and Shopping Behavior
<p align="center">
  <img alt="Major Life Changes and Shopping Behavior" width="65%" 
  src="https://github.com/ttran1216/Amazon_Survey_Analysis/blob/main/image/Major%20Life%20Changes%20and%20Shopping%20Behavior.png">
  <br>
  <em>Figure: Major Life Changes and Shopping Behavior.</em>
</p>

- The most common life change reported was **moving to a new residence**, followed by **job loss**.
- Significant life events, such as **having a child or becoming pregnant**, also appear to influence shopping behavior.
- These insights suggest that major life changes might lead to shifts in consumer purchasing patterns.

---

This summary provides a concise interpretation of the dataset, highlighting key trends in Amazon shopping behavior based on demographic factors and life changes.



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


