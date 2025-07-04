# Palmoria-Group-HR
The dashboard and the report provide insights and visualizations that will guide the management team in making informed decisions to promote gender equality within the organization.
## Palmoria Group HR Analysis Report

## Backstory

The Palmoria Group, a prominent manufacturing company based in Nigeria, has recently come under scrutiny due to allegations of gender inequality across its three regional offices. The media has highlighted these issues with the headline "Palmoria, the Manufacturing Patriarchy," which poses a significant threat to the company's reputation and its ambitions to expand both regionally and internationally.

In response to these allegations, the CEO, Mr. Ayodeji Chukwuma, has tasked the Chief Human Resources Officer (CHRO), Mr. Yunus Shofoluwe, with addressing these concerns promptly. Mr. Shofoluwe has enlisted the help of an HR Analytics expert to analyze the company's HR data and provide actionable insights to rectify these issues. The future of gender equality at Palmoria is now in the hands of this expert team.

## Data Cleaning Process Using Power Query

To ensure the accuracy and reliability of the analysis, a thorough data cleaning process was conducted using Power Query. The following steps were taken:

1. **Handling Missing Gender Data**: 
   - Employees who did not disclose their gender were assigned a generic gender status to ensure inclusivity in the analysis.

2. **Excluding Former Employees**:
   - Employees without a salary were identified as no longer being with the company and were removed from the dataset to maintain the relevance of the analysis.

3. **Removing Null Departments**:
   - Records with departments indicated as "NULL" were excluded from the dataset. This step reduced the total row count from 1015 to 946, ensuring that only valid and complete data was used in the analysis.

These data cleaning steps were crucial in preparing the dataset for a comprehensive analysis of gender-related issues within the Palmoria Group. The cleaned data will be used to generate insights and visualizations that will guide the management team in making informed decisions to promote gender equality within the organization.

# Analysis of Palmoria Group HR Data

The Palmoria Group HR data provides insights into the distribution of employees based on gender, region, salary, and department. Below is a detailed analysis of the data presented in the dashboard.

## Employee Distribution by Gender
- **Total Employees**: 946
- **Male Employees**: 465
- **Female Employees**: 441
- **Undisclosed Gender**: 40

The gender distribution shows a slight difference between male and female employees, with males being slightly more numerous.

## Regional Distribution
- **Kaduna**: 182 males, 165 females, 18 undisclosed
- **Abuja**: 159 males, 158 females, 14 undisclosed
- **Lagos**: 124 males, 118 females, 8 undisclosed

The regional distribution indicates a fairly balanced gender representation across the regions, with a small number of employees having undisclosed gender.

## Salary Analysis
- **Total Salary**: 70 million
- **Average Salary**: 73.70k
- **Average Bonus**: 0.03

The salary data suggests that the average salary is approximately 73.70k, with a minimal average bonus.

## Departmental Distribution by Gender
### Male Employees
- Legal: 49
- Product Manager: 47
- Support: 42
- Sales: 40
- Human Resources: 38
- Training: 38
- Accounting: 37
- Business Development: 37
- Services: 37
- Engineering: 36
- Marketing: 33
- Research and Development: 31

### Female Employees
- Services: 42
- Business Development: 41
- Human Resources: 41
- Product Management: 41
- Engineering: 38
- Research and Development: 38
- Sales: 36
- Training: 36
- Support: 35
- Legal: 34
- Marketing: 31
- Accounting: 28

### Undisclosed Gender
- Engineering: 6
- Legal: 5
- Research and Development: 5
- Sales: 4
- Support: 4
- Business Development: 3
- Human Resources: 3
- Services: 3
- Training: 3
- Accounting: 2
- Marketing: 1
- Product Management: 1

## Conclusion
The data reveals a slight gender gap in departmental distribution, with certain departments having more male or female employees. However, the presence of employees with undisclosed gender makes it challenging to draw definitive conclusions about the gender gap. To accurately assess the gender gap, it would be necessary to identify the gender of the undisclosed employees. Nonetheless, based on the available data, there is a slight difference in gender representation across departments.

### Gender Distribution
- **Male Ratio**: 49% of the workforce
- **Female Ratio**: 47% of the workforce
- **Gender Pay Gap**: Potential pay gap due to department clustering, with females possibly overrepresented in lower-paying sectors like HR and Services.

### Employee Ratings
- **Majority Rating**: "Average" with 212 employees
- **Lower Ratings**: "Very Good" (34), "Not Rated" (31), "Very Poor" (31)
- **Female Ratings**: Large portion in "Average" or "Poor", possibly limiting recognition and progression.

### Departmental Insights
- **Top 5 Departments by Employee Count**: Legal (49), Product Management (47), Support (42), Sales (40), HR (38)
- **Female Representation in Top Departments**: Services (42), Business Development (41), HR (41), Product Management (41), Engineering (38)
- **Male High-Earners' Departments**: Legal, Support, Business Development, Product Management, Accounting

### Salary Insights
- **Total Employees**: 465
- **Total Salary**: $35M
- **Average Salary**: $74.79K
- **Average Bonus**: 0.03
- **Male Employees with Salary ≥ ₦90,000**: 152 employees, average salary ₦105.94K
- **Female Employees with Salary ≥ ₦90,000**: 126 employees, average salary ₦105.19K

### Location Distribution
- **Female Presence**: Higher in Kaduna and Abuja, lower in Lagos
- **Male High-Earners' Locations**: Kaduna (59), Abuja (53), Lagos (40)
- **Female High-Earners' Locations**: Kaduna (47), Lagos (40), Abuja (39)

### Key Observations
- **Performance Ratings for Male High-Earners**: Symmetry between strong and weak ratings, suggesting pay may not always reflect performance.
- **Geographic Distribution**: Balanced opportunity for female high-earners across regional offices.
- **Departmental Spread for Female High-Earners**: Strong representation in strategic, technical, and people-oriented departments, indicating multi-dimensional contributions.

This analysis highlights the gender distribution, salary insights, and departmental representation within Palmoria Group, providing a comprehensive overview of workforce dynamics and potential areas for improvement.
