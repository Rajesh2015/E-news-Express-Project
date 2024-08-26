# A/B Testing Analysis for E-news Express

## Business Context
E-news Express, a prominent online news portal, aims to increase its subscriber base. The portal's management has noticed a decline in the number of new monthly subscribers compared to the previous year. They attribute this decline to the current landing page, which may not be optimally designed in terms of layout and recommended content, potentially failing to engage users effectively.

To address this issue, the design team at E-news Express has developed a new landing page with a refreshed outline and more relevant content. The objective is to test the effectiveness of this new landing page in converting visitors into subscribers.

## Objective
The main objective of this analysis is to determine whether the newly designed landing page performs better in terms of user engagement and conversion rates compared to the existing landing page. The key questions to be answered through statistical analysis are:

1. **Time Spent on Page:** Do users spend more time on the new landing page compared to the existing one?
2. **Conversion Rate:** Is the conversion rate (proportion of users who subscribe) higher for the new landing page compared to the old one?
3. **Language and Conversion:** Does the conversion status depend on the user's preferred language?
4. **Language and Time Spent:** Is the time spent on the new landing page the same across different language users?

## Dataset Description
The dataset used for this analysis contains the following columns:

- **user_id:** Unique identifier for each user visiting the website.
- **group:** Indicates whether the user belongs to the control group (existing landing page) or the treatment group (new landing page).
- **landing_page:** Specifies whether the landing page viewed is new or old.
- **time_spent_on_the_page:** The amount of time (in minutes) the user spent on the landing page.
- **converted:** Indicates whether the user subscribed to the news portal or not.
- **language_preferred:** The language chosen by the user to view the landing page.

## Statistical Analysis
The analysis will be conducted at a 5% significance level. The following tests will be used to answer the research questions:

1. **Comparison of Means (Time Spent on Page):** 
   - Hypothesis testing (e.g., t-test) to compare the average time spent on the old vs. new landing page.

2. **Proportion Test (Conversion Rate):**
   - A/B testing using a Z-test to compare conversion rates between the two landing pages.

3. **Chi-Square Test (Language and Conversion):**
   - A Chi-square test to evaluate if there is a dependency between the preferred language and conversion status.

4. **ANOVA (Time Spent and Language):**
   - ANOVA to determine if the time spent on the new landing page varies significantly across different languages.

## Conclusion
The findings from these statistical tests will help E-news Express make informed decisions regarding the deployment of the new landing page. If the new page shows a statistically significant improvement in user engagement and conversion rates, it will be rolled out as the default landing page for all users.

## Usage
This repository contains the code and datasets necessary to replicate the analysis. To get started, simply clone the repository and follow the instructions in the Jupyter notebooks provided.

---

**Author:** [Rajesh Kumar Dash]  
**Date:** [25-08-2024]

