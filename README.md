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
