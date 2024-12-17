# Analysis_Data_Developer_Salary_in_2024_DA_Batch1

## Objective
The objective of this analysis is to explore salary trends for data developers in 2024. The analysis focuses on identifying factors that influence salaries, including experience level, job title, remote work, company size, and geographical location.

## About the Dataset
- **Dataset**: The dataset includes salaries and job details of data developers for the year 2024.
- **Key Features**:
  - `work_year`: Year of the recorded data.
  - `experience_level`: Employee's experience (`EN`, `MI`, `SE`, `EX`).
  - `employment_type`: Job contract type (`FT`, `PT`, `CT`, `FL`).
  - `job_title`: Employee's job role.
  - `salary_in_usd`: Standardized salary in USD.
  - `remote_ratio`: Percentage of remote work (0%, 50%, 100%).
  - `company_size`: Company scale (`S`, `M`, `L`).
  - `employee_residence` and `company_location`: Geographical locations.

---

## Steps
1. **Data Cleaning**:
   - Removed duplicate rows.
   - Filtered out unrealistic salary values (`<15,000` or `>500,000`).

2. **Exploratory Data Analysis**:
   - Analyzed salary trends based on:
     - Experience Level.
     - Job Title.
     - Remote Work Ratios.
     - Company Size.
     - Employee Residence.
   - Visualized salary distributions using bar plots, scatter plots, and boxplots.

3. **Key Insights**:
   - Experience level significantly impacts salaries.
   - Tech roles like *ML Engineer* and *Data Engineering Manager* pay the most.
   - Fully remote roles offer higher salaries.
   - Medium-sized companies pay more compared to small or large ones.
   - Certain countries, like Qatar and Malaysia, have higher average salaries.

4. **Visualization**:
   - Created various charts (bar plots, KDE plots, scatter plots) to summarize findings visually.

---

## Conclusion
1. **Experience Level**: Higher experience levels (`SE`, `EX`) lead to higher salaries.  
2. **Job Titles**: Technical and managerial roles, such as *ML Engineer* and *Data Engineering Manager*, offer the highest salaries.  
3. **Remote Work**: Fully remote jobs tend to pay more, emphasizing the importance of flexibility in work arrangements.  
4. **Company Size**: Medium-sized companies offer the most competitive salaries.  
5. **Geographical Impact**: Salaries vary significantly across countries, with Qatar and Malaysia leading in averages.  

### Final Note:
Investing in AI/tech training, supporting remote work, and targeting high-demand roles can significantly improve salary outcomes and attract top talent.
