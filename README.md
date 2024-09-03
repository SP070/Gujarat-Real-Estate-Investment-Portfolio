# Gujarat-Real-Estate-Investment-Portfolio

# Real Estate Project in Gujarat: Analysis and Investment Recommendations

[Uploading Gujrat-Real-Estate.ipynb…]()


![1708191111682](https://github.com/user-attachments/assets/bcb80277-b297-4ddb-a2ea-0cd92d510996)


## Key Findings

1. **Data Preprocessing**: 
   - Original dataset shape: (10615, 16)
   - Handled missing values and encoded categorical variables
   - Removed outliers, resulting in a cleaned dataset of 10,615 entries

2. **Exploratory Data Analysis**:
   - Identified the distribution of project types and costs
   - Analyzed project durations, with the longest projects spanning around 2,900 days (approximately 8 years)

3. **Machine Learning Models**:
   - Implemented and compared multiple regression models
   - Random Forest Regressor performed the best with an R2 score of 0.6285
   - Key features influencing project cost (in order of importance):
     1. Number of units (49.16%)
     2. Registration fee (27.66%)
     3. Project type (11.41%)
     4. Duration (6.15%)
     5. District name (5.62%)

4. **Model Performance**:
   - Linear Regression: R2 = 0.4502
   - Polynomial Regression: R2 = 0.5160
   - Ridge Regression: R2 = 0.4502
   - Lasso Regression: R2 = 0.4250
   - Random Forest: R2 = 0.6285

5. **Best Random Forest Parameters**:
   - n_estimators: 200
   - min_samples_split: 5
   - min_samples_leaf: 4
   - max_depth: 10

## Investment Recommendations

1. Focus on projects with a higher number of units, as this is the most important feature in determining project cost and potential returns.
2. Consider the registration fee as a significant factor in project evaluation.
3. Pay attention to the project type, as it has a moderate influence on the project cost.
4. While duration and district name have less impact, they should still be considered in the decision-making process.
5. Utilize the Random Forest model for predicting project costs, as it outperformed other models in this analysis.

## Conclusion

The Random Forest model demonstrates the best performance in predicting project costs, explaining approximately 62.85% of the variance. This suggests that while the model is reasonably good at predicting costs, there are still other factors not captured in our dataset that influence project costs. Investors should use this model as a tool in their decision-making process but should also consider other qualitative factors and market trends when making investment decisions.

# Top 10 Projects to Invest in for the Next 5 Years

Based on the project cost, start date, and end date, here are the top 10 projects to consider for investment in the next 5 years:

1. **ANAMIKA HIGH POINT**
   - Project Cost: 14,583,900,000 INR
   - Start Date: 2023-11-07
   - End Date: 2030-06-30
   - Reason: High-value project with a long-term completion date

2. **SOBHA ELYSIA**
   - Project Cost: 11,525,900,000 INR
   - Start Date: 2024-03-22
   - End Date: 2030-12-31
   - Reason: Large-scale project starting in the near future with a long-term horizon

3. **AVADH MENORCA**
   - Project Cost: 7,764,510,000 INR
   - Start Date: 2024-04-09
   - End Date: 2029-12-31
   - Reason: Significant project value with a 5-year development timeline

4. **AVADH CLASSIMA**
   - Project Cost: 7,568,070,000 INR
   - Start Date: 2023-06-23
   - End Date: 2028-03-31
   - Reason: Ongoing project with substantial value and medium-term completion date

5. **IKEBANA**
   - Project Cost: 7,026,670,000 INR
   - Start Date: 2022-06-17
   - End Date: 2027-07-01
   - Reason: Ongoing project with high value and approaching mid-term completion

6. **AVADH MARTELLA**
   - Project Cost: 6,804,010,000 INR
   - Start Date: 2024-04-03
   - End Date: 2029-12-31
   - Reason: Future project with significant value and 5-year development plan

7. **RIVERA THE ATLANTIS PHASE-1**
   - Project Cost: 4,038,590,000 INR
   - Start Date: 2018-07-02
   - End Date: 2026-06-30
   - Reason: Ongoing high-value project with near-future completion date

8. **TITAN 54**
   - Project Cost: 3,608,474,000 INR
   - Start Date: 2019-06-10
   - End Date: 2024-06-30
   - Reason: Ongoing project nearing completion, potential for quick returns

9. **The Life**
   - Project Cost: 3,436,161,000 INR
   - Start Date: 2022-06-06
   - End Date: 2026-12-31
   - Reason: Recent high-value project with medium-term completion date

10. **UTSAV AALAYAM**
    - Project Cost: 3,421,456,000 INR
    - Start Date: 2020-10-19
    - End Date: 2026-06-30
    - Reason: Ongoing project with substantial value and approaching completion

Note: This list is based primarily on project cost and timeline. Investors should conduct further due diligence on factors such as location, developer reputation, market demand, and potential return on investment before making any investment decisions.

