# Health-Insurance-Data-Analysis---Parametric-Nonparametric-Statistical-Testing
This project analyzes a health insurance dataset using univariate and bivariate statistical analysis, followed by parametric (t-test) and nonparametric (Mann-Whitney U test) statistical tests.

# Health Insurance Data Analysis - Parametric & Nonparametric Statistical Testing

## Project Overview
This project explores a health insurance dataset to uncover trends in insurance charges and BMI distributions. The dataset contains information on individuals' demographic and health-related factors, including age, sex, BMI, number of children, smoking status, region, and insurance charges.

### Key Objectives:
1. Perform **univariate** and **bivariate** analysis on continuous and categorical variables.
2. Conduct a **parametric statistical test (t-test)** to determine if there is a significant difference in insurance charges between smokers and non-smokers.
3. Conduct a **nonparametric statistical test (Mann-Whitney U test)** to evaluate BMI distributions between males and females.

## Project Structure:
- **Data Exploration:** Univariate and bivariate analysis, including visualizations, to understand distributions and relationships in the data.
- **Statistical Testing:**
  - **Parametric Test (T-Test):** To assess if smokers have higher insurance charges than non-smokers.
  - **Nonparametric Test (Mann-Whitney U Test):** To evaluate whether BMI distributions differ between males and females.
- **Conclusion and Recommendations:** Interpretation of test results, discussion of limitations, and suggestions for stakeholders.

## Dataset:
The dataset includes the following columns:
- **Age:** Age of the insured individual.
- **Sex:** Gender of the individual (male or female).
- **BMI:** Body mass index, a measure of body fat.
- **Children:** Number of children covered under the insurance plan.
- **Smoker:** Whether the individual smokes (yes or no).
- **Region:** Geographic region (Northeast, Southeast, Southwest, Northwest).
- **Charges:** Insurance charges incurred by the individual.

## Visualizations:
- **BMI Distribution:** Histogram of BMI across individuals.
- **Charges Distribution:** Histogram of insurance charges.
- **Bivariate Analysis:** Scatterplots and boxplots to explore relationships between BMI, Charges, Smoking Status, and Gender.

## Statistical Tests:
1. **T-Test (Parametric):** Examining the difference in insurance charges between smokers and non-smokers.
   - **Null Hypothesis (H0):** There is no significant difference in charges between smokers and non-smokers.
   - **Result:** Significant difference found, suggesting smokers incur higher insurance charges.
   
2. **Mann-Whitney U Test (Nonparametric):** Evaluating BMI distributions between males and females.
   - **Null Hypothesis (H0):** BMI distributions are the same between males and females.
   - **Result:** No significant difference found in BMI distributions between males and females.

## Files Included:
- **D599 Task 2_ Data Exploration.pdf:** Contains the analysis, statistical test results, and visualizations.
- **Jupyter Notebooks:** Code used for data analysis and hypothesis testing.
- **Images:** Visual representations used in the analysis.
  - BMI_vs_Charges1.jpeg
  - Region_vs_Charges.jpeg
  - Smoker_vs_Charges.jpeg
  - ... (other included images)

## How to Run:
1. Clone the repository to your local machine.
2. Open the Jupyter Notebooks to view the code and rerun the analysis.
3. View the **Data Exploration PDF** for a complete report of the findings and visualizations.

## Conclusion:
This project highlights the importance of statistical testing in analyzing insurance data. Stakeholders can use the insights gained to design targeted interventions, such as smoking cessation programs, to reduce medical costs. Additionally, the BMI analysis shows no significant differences across genders, suggesting uniform BMI-based health initiatives.
