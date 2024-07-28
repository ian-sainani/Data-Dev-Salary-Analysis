# Data_Dev_Salary_Analysis

## Objective
The objective of this analysis is to explore and analyse data developer salaries based on various factors such as job title, experience level, employment type, company region, company size, and changes over the years. 

The goal is to identify trends and insights that can help understand how these factors impact salaries in the data development field.

## Problem Statement
Understanding salary distributions and identifying factors that influence data developer salaries are crucial for employers, employees, and job seekers. 

This analysis aims to answer the following questions:
- What are the average, median, minimum, maximum, and standard deviation of salaries for different job titles?
- How does experience level affect salary?
- How does employment type affect salary?
- What is the impact of remote ratio on salary?
- How does company region affect salary?
- Does the size of the company impact the salary of their employees?
- How has the average salary changed over the years?

## Salary Analysis by Job Title

<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/e096464d-3756-4e80-8b09-0a451b592061">
</p>
The histogram shows a right-skewed distribution, with a mean salary of $132,017.80 and a median salary of $127,292.80.

This suggests that a few job titles have significantly higher salaries than most others. These high-paying job titles include Analytics Engineering Manager, Data Science Tech Lead, and Head of Machine Learning.

The standard deviation of salaries across all full-time job titles is $68,351.02, while the standard deviation of average salaries grouped by job titles is $57,862.94. 

The large standard deviations indicate considerable variability in salaries, which decreases when grouped by job titles, prompting further analysis to identify additional influencing factors.

## Salary Analysis by Experience Level

Employees with more experience tend to earn higher salaries.

<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/ad272047-92df-44a1-88a7-5a96366081dc"> <br>
<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/5e28b84f-66cd-446a-9272-a5fb0d18b98c"> <br>

<img width="500" alt="image" src="https://github.com/user-attachments/assets/a7e12733-c304-4c84-b3b5-e5932a905880">
</p>
</p>

As expected, a positive correlation between experience level and average salary is observed.

Key observations:
- A significant number of outliers are present, primarily among experience levels of SE and below, with outlier salaries significantly higher than the mean salaries of EX employees.
- EX employees have the largest IQR, while EN employees have the smallest IQR, and MI employees have the largest overall range.

## Salary Analysis by Employment Type

<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/0f68ad96-862a-46b6-8d50-c367ebc331bd"> <br>
<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/5ec3a28c-b741-4695-8ebd-4396eb228d8e"> <br>

<img width="500" alt="image" src="https://github.com/user-attachments/assets/3b3f833e-8f26-49de-ad47-74b27ffac44c">
</p>
</p>

Key observations:
- Full-time employees earn the highest mean salary, while freelance employees earn the lowest.
- Full-time employees exhibit the largest salary range, whereas freelance employees show the smallest range.
- Part-time employees have the largest IQR.
- Full-time employees show the most number of outliers.

## Impact of Remote Ratio on Salary
The correlation score between remote ratio and salary is -0.057, indicating that remote ratio does not significantly influence employee salaries.

## Salary Analysis by Company Region

<p align="center">
<img width="550" alt="image" src="https://github.com/user-attachments/assets/b41d31c6-0f31-44be-b1fd-607e3d751100"> <br>
<p align="center">
<img width="550" alt="image" src="https://github.com/user-attachments/assets/e21085df-5899-49b6-b69b-3158b267931b"> <br>
</p>
</p>

Key observations:
- Employees in North America have the highest mean and median salaries and the largest salary range, including the most outliers.
- Employees in South Asia have the lowest mean and median salaries.
- Employees in East Asia & Pacific have the largest IQR.
- Employees in Sub-Saharan Africa have the smallest IQR and overall range.

### Drill down into Regional Salary Distribution among each Experience Level

<img width="500" alt="image" src="https://github.com/user-attachments/assets/c971aeb7-9d38-4f0f-941b-aa0ed2c9ad54">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/0e4bcd39-0aff-4ac5-adc1-6767eade32eb">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/17f83bab-afd4-4d03-8de3-7a2641313e5d">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/84b56b39-fd5b-4642-ad33-4187eb68ee83">

## Salary Analysis by Company Size

<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/feeb09a2-f32b-4b28-80e5-fac00276d81c"> <br>
<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/817eec95-e4e6-4cb9-9eaa-687322d14f22"> <br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/4657c263-7582-43c0-84f8-935c9aa135c8">
</p>
</p>

Key observations:
- Medium-sized companies offer the highest mean and median salaries, while small companies offer the lowest.
- A significant number of outliers are present in medium-sized companies.
- Large companies have the largest IQR.
- Medium-sized companies have the largest overall range.

## Trend Over the Years

<p align="center">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/f11780bc-e1d6-4b55-9ab7-796325880301"> <br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/d9291bcd-2f26-470d-b073-b68aa2138be4">
</p>


Trend analysis indicates a general upward trend in average salaries from 2020 to 2024, with some fluctuations:
- 2020: The mean salary was $106,759.
- 2021: The mean salary slightly decreased to $99,485.
- 2022: A significant increase occurred, with the average salary rising to $134,882.
- 2023: The upward trend continued, reaching the highest average salary of $153,866.
- 2024: There was a slight decrease to $150,864, still significantly higher than in 2020 and 2021.

Key observations:
- The peak average salary was observed in 2023.
- The most substantial increase in average salary occurred between 2021 and 2022.
- Despite a minor decline from 2023 to 2024, the average salary remained considerably higher than in previous years.

## Limitations and Recommendations for Future Analysis
- Data Scope: The analysis is limited to the available data, which may not represent the entire industry. Expanding the dataset to include more job titles, regions, and company types could provide a more comprehensive analysis.
- External Factors: Factors such as economic conditions, industry demand, and technological advancements are not considered and may influence salary trends. Including these factors could enhance the analysis.
- Data Quality: Outliers and missing values could impact the results. Ensuring data quality and addressing anomalies could improve the accuracy of the analysis.
- Detailed Segmentation: Further segmentation by additional factors such as education level, certifications, and specific skills could provide deeper insights into salary determinants.
By addressing these limitations, future analyses can offer more robust and actionable insights into the factors influencing data developer salaries.

## Conclusion

This analysis highlights several key insights into data developer salaries. Higher experience levels correlate with higher salaries, affirming the value of expertise. Full-time employment offers the highest average salaries, while freelance work offers the lowest. Remote work ratio does not significantly impact salaries, suggesting remote work is well-integrated and does not penalize employees financially.

Regionally, North America offers the highest salaries, while South Asia offers the lowest. Medium-sized companies provide the most competitive salaries compared to small and large firms. Over the years, salaries have generally increased, peaking in 2023 and remaining high in 2024.

The analysis, however, has limitations such as data scope and unconsidered external factors. Future studies should expand the dataset and consider additional factors like education and skills to provide deeper insights. Addressing these limitations will enhance the understanding of salary determinants in the data development field.











