# STA302 Final Project Report

## Project Overview
This project explores the dynamics that enhance profile attractiveness on dating apps. Using a multiple linear regression model, the study examines the impact of factors such as age, gender of interest, profile picture count, profile visit count, verification status, the number of languages spoken, and country of origin on the number of likes a dating app profile receives.

## Research Question
Can a linear regression model determine if the selected factors influence the number of likes on a dating app profile?

## Methodology
1. **Exploratory Data Analysis (EDA):** 
   - Analyzed the distribution of variables and identified skews in the data.
2. **Model Construction:**
   - Developed a multiple linear regression model.
   - Checked assumptions (linearity, constant variance, uncorrelated errors, and normality).
   - Applied transformations (e.g., Box-Cox) to address violations.
3. **Model Evaluation:**
   - Conducted ANOVA for overall model significance.
   - Performed Partial F-tests for variable reduction.
   - Assessed multicollinearity using Variance Inflation Factor (VIF).
4. **Final Model Selection:**
   - Compared models using metrics like Adjusted \(R^2\), AIC, AICc, and BIC.
5. **Validation:**
   - Split data into training and testing sets for validation.

## Results
- The final model includes four predictors: age, country population, profile visits, and verification status.
- Significant findings:
  - Profile visits had the strongest positive influence on likes.
  - Age and country population negatively impacted likes.
- The model was validated, demonstrating high predictive accuracy with low Mean Squared Error (MSE).

## Limitations
- High leverage and influential points in the dataset may have impacted results.
- Dataset collection methods introduced biases, particularly in gender preference representation.

## References
1. Castro, Á., Barrada, J. R., Ramos-Villagrasa, P. J., & Fernández-del-Río, E. (2020). Profiling dating apps users: Sociodemographic and personality characteristics. _International Journal of Environmental Research and Public Health_, _19_(3), 1575. [https://doi.org/10.3390/ijerph17103653](https://doi.org/10.3390/ijerph17103653)

2. Ellison, N., Heino, R., & Gibbs, J. (2006). Managing impressions online: Self-presentation processes in the online dating environment. _Journal of Computer-Mediated Communication_, _11_(2), 415-441. [https://doi.org/10.1111/j.1083-6101.2006.00020.x](https://doi.org/10.1111/j.1083-6101.2006.00020.x)

3. Hitsch, G. J., Hortaçsu, A., & Ariely, D. (2010). What makes you click? Mate preferences in online dating. _Quantitative Marketing and Economics_, _8_(4), 393-427. [https://doi.org/10.1007/s11129-010-9088-6](https://doi.org/10.1007/s11129-010-9088-6)

4. Kaggle dataset: Mabilama Jeffrey Mvutu. (2015). Dating App Lovoo User Profiles. Kaggle. [https://www.kaggle.com/datasets/jmmvutu/dating-app-lovoo-user-profiles](https://www.kaggle.com/datasets/jmmvutu/dating-app-lovoo-user-profiles)

5. Original source of the Kaggle dataset: Jfreex. (2015). Dating App User Profiles’ Stats - Lovoo v3. Data World. [https://data.world/jfreex/dating-app-user-profiles-stats-lovoo-v3](https://data.world/jfreex/dating-app-user-profiles-stats-lovoo-v3)

6. Population data: World Bank. (2024). Population, total (SP.POP.TOTL). [https://data.worldbank.org/indicator/SP.POP.TOTL?locations=1W](https://data.worldbank.org/indicator/SP.POP.TOTL?locations=1W)

## Authors
- Ebrahim Mohamud
- Raihan Amin
- Rebecca Li

## Institution
University of Toronto, STA302H1 - Methods of Data Analysis I

## Date
December 6, 2024
