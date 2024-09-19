# Project Background
This project showcases a Human Resources dashboard created using Tableau, turning raw Human Resources data into actionable strategic insights. The dataset, simulated using a combination of **ChatGPT** prompts and the **Python Faker library**, reflects real-world complexities such as employee demographics, salary structures, performance evaluations, and attrition trends. 

By leveraging advanced data visualization techniques, the dashboard empowers HR teams and business leaders to make data-driven decisions—whether it's improving employee retention, identifying performance trends, or optimizing salary allocations. The integration of AI-driven data generation demonstrates the ability to scale and diversify data efficiently, a crucial skill in today's AI-dominated analytics landscape.

# Executive Summary
The company’s workforce, currently at 7,984 employees after a net hiring rate of 8,950 since 2015, saw a notable hiring surge in 2017 (17%) and a dip in 2021 (5%). The Operations department, though the largest, also faces the highest turnover, with over 300 terminations recorded throughout the year. While employees with PhDs outperform their peers, those with high school diplomas often receive 'needs improvement' ratings. Notably, women with advanced degrees surpass men in earnings, but a 12% gender pay gap persists among bachelor’s-level employees, suggesting potential areas for pay equity improvements.

Human Resources Dashboard Overview Snapshot:
![HR Dashboard Overview Snapshot](/Snapshots/HR%20Dashboard%20Overview.png)

---
You can find the Python code for generating a realistic Human Resources dataset here: [**link**](/Python%20code/generation.py)

An interactive Tableau dashboard used to report and explore HR trends can be found here: [**link**](https://public.tableau.com/app/profile/zolboo1658/viz/HRDashboards_17267167597120/HRSummary)

# Insights

1. ### Workforce Hiring and Attrition Trends
The company has exhibited a **cyclical hiring trend** since its inception in 2015, with **2017 marking a peak** (17% of total hires) and a **sharp downturn in 2021** (5% hiring rate). While this may indicate fluctuating operational demands, the 966 terminations reveal that **employee retention strategies might need to be revisited** to prevent high turnover, especially within key departments. Future workforce planning should prioritize stabilizing hiring and attrition cycles to ensure sustainable growth.

2. ### Departmental Disparity in Turnover and Retention
The Operations department, despite being the largest in the company with over 2,000 employees, is experiencing **disproportionately high turnover rates**, with nearly 300 terminations in a year. This points to **potential inefficiencies** or dissatisfaction within the team, signaling the need for **department-specific retention strategies**. Cross-departmental analysis could identify whether similar trends exist elsewhere, guiding resource reallocation and employee engagement programs targeted at high-turnover departments.

3. ### Geographic Workforce Concentration
The company’s geographical distribution presents a notable concentration in **New York (70% of total employees)**, suggesting potential **over-reliance on a single location**. This could present risks, such as operational bottlenecks or constraints in talent acquisition, especially as the remaining 30% of employees are dispersed across smaller regional offices in states like Michigan and Pennsylvania. **A diversified workforce** in other regions, or an increase in **remote work adoption**, could **mitigate geographic concentration risks** while opening up the talent pool.

4. ### Performance Correlation with Educational Attainment
A strong **correlation between higher educational attainment and performance** is evident, particularly with employees holding PhDs consistently demonstrating **excellent performance ratings**. However, the **lower performance metrics for employees with high school diplomas** could indicate a **skills gap** at the lower education level. This finding highlights the need for **targeted learning and development initiatives** aimed at upskilling this segment of the workforce to close performance gaps and enhance overall productivity.

5. ### Performance Correlation with Educational Attainment
Despite notable advances for women with advanced degrees—where they **outperform men in earnings**, especially at the PhD and Master’s levels—the **12% pay gap for employees with bachelor’s degrees** reveals a **gender-based disparity** in earlier career stages. This disparity underscores the importance of introducing **pay equity audits** and **early-career mentorship** programs for women, ensuring **equitable career progression and salary growth** for employees at the bachelor’s level, while **mitigating turnover due to perceived inequities**.

# Recommendations

1. ### Addressing the Operational Turnover Spike
Given that the Operations department accounts for the largest workforce and also the highest turnover, it is essential to investigate the root causes. High turnover can result in decreased productivity, increased recruitment costs, and lowered employee morale.

- **Recommendation**: Conduct exit interviews and employee engagement surveys to identify key drivers of turnover. Based on findings, implement retention strategies such as tailored leadership programs or employee wellness initiatives specific to the Operations department.

- **Potential Impact**: Reducing turnover could directly increase the employee-to-manager ratio efficiency while lowering onboarding and hiring costs. It can also improve productivity by fostering a more stable workforce.

2. ### Optimizing Geographical Workforce Distribution
With 70% of the workforce concentrated in New York, there’s a significant opportunity to explore more cost-effective and strategic locations. Michigan, while the second largest hub, presents a chance for expansion and talent acquisition outside the headquarters.

- **Recommendation**: Explore increasing remote work adoption in underrepresented locations (Pennsylvania or North Carolina) where talent pools are available but operational costs are lower. This could be supplemented by offering remote working incentives or expanding remote leadership roles.

- **Potential Impact**: Expanding remote or distributed work could balance workforce costs, improve diversity, and increase the company's footprint without the high cost of expanding HQ operations. It also enables better employee satisfaction due to flexible working environments.

3. ### Creating Mentorship Programs for Bachelor's-Level Employees
The analysis indicates a significant gender pay gap at the bachelor’s degree level, where men earn 12% more on average than women. By comparison, women with advanced degrees (Master's, PhDs) earn more than men. This suggests an opportunity to level the playing field at the bachelor's level.

- **Recommendation**: Implement a structured mentorship program for female employees with bachelor's degrees, focused on career development, leadership opportunities, and upskilling. Pair this initiative with gender pay audits and promotion tracking to ensure equitable career progression.

- **Potential Impact**: This will reduce turnover among women at the bachelor's level, promote internal equity, and cultivate future leaders within the organization. It also helps the company project a stronger commitment to diversity and inclusion, benefiting overall employer branding.

4. ### Leveraging High-Performing PhD Employees
PhD employees consistently show strong performance ratings, highlighting an opportunity to leverage this talent pool more effectively.

- **Recommendation**: Offer specialized leadership development programs or innovation hubs led by PhD employees, encouraging them to contribute not only as individual contributors but also as mentors and leaders. Provide clear pathways for their progression into more strategic roles across the business.

- **Potential Impact**: This could accelerate innovation, improve problem-solving, and inspire others to pursue advanced educational opportunities within the company. Additionally, it positions the company as a hub for high-level talent development.