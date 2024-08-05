# Afame_technology_HR_Attrition_Analysis
Introduction
This project involves a comprehensive data cleansing process for an HR dataset followed by an in-depth analysis of employee attrition within a company. The goal is to prepare the data for effective analysis by removing irrelevant information, handling missing values, eliminating redundancies, and making other necessary adjustments to ensure the dataset is clean, consistent, and ready for further analysis or modeling.

Data Cleansing Steps
1. Remove Unnecessary Columns
Identify and remove columns that are not useful for analysis.

2. Rename Columns
Give columns meaningful names to enhance readability and understanding.

3. Eliminate Redundant Entries
Remove duplicate rows to ensure unique entries.

4. Eliminate NaN Values
Address NaN values by either dropping or filling them with appropriate values

Data Description
The dataset contains information on:
- Employee demographics (age, gender, etc.)
- Job roles and departments
- Compensation details
- Attrition status and reasons
- Other relevant attributes

Dashboard Overview
The Power BI dashboard visualizes key metrics such as:
- Overall attrition rates
- Attrition by department
- Attrition by job role
- Attrition by education field
- Attrition by distance from the workplace
- Attrition by salary slab
- Job satisfaction levels
- Age range distribution
- Years of service distribution

 Insights
1. Overall Attrition:
   - The company has 1,470 employees.
   - 237 employees have left, resulting in an attrition rate of 16.1%.
   - The average salary is 6.5K, and the average age is 37 years.

2. Attrition by Education Field:
   - High attrition rates in the Life Sciences and Medical fields.

3. Attrition by Job Role:
   - Healthcare Representatives and Sales Executives have the highest turnover.

4. Attrition by Distance:
   - Employees living far from the workplace show the highest attrition.

5. Attrition by Salary Slab:
   - Most employees leave within the 'up to 5k' salary range.

6. Attrition by Department:
   - Highest attrition in R&D (133) and Sales (92) departments. Lowest in HR (12).

7. Job Satisfaction and Attrition:
   - High attrition among 'Very Dissatisfied' (66) and 'Dissatisfied' (52) employees.

Recommendations
1. Target High Attrition Roles:
   - Conduct exit interviews for Healthcare Representatives and Sales Executives.
   - Implement retention programs and career development opportunities.

2. Address Distance-Related Issues:
   - Offer flexible work arrangements and transportation assistance.

3. Improve Job Satisfaction:
   - Conduct regular satisfaction surveys and enhance workplace culture.

4. Review Compensation Structure:
   - Assess and adjust salaries, especially in the 'up to 5k' range.

5. Focus on High Attrition Departments:
   - Investigate and address challenges in R&D and Sales departments.

7. Tailor Support for Age Groups:
   - Offer career development, work-life balance initiatives, and retirement planning.

8. Engage Long-Term Employees:
   - Provide special recognition and mentorship opportunities.

9. Promote Work-Life Balance:
    - Implement flexible working hours and wellness programs.

Repository Structure
- data/
  - `hr_data.csv`: Original dataset
  - `cleaned_hr_data.csv`: Cleaned dataset

- dashboard/
  - `HR_afame.pbix`: Power BI dashboard file

Conclusion
We have identified key factors influencing employee attrition by analyzing the HR dataset and visualizing the data in a Power BI dashboard. Implementing the recommendations can help reduce turnover rates and improve employee retention, leading to a more stable and productive workforce.

