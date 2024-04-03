# HR-ANALYSIS-Dashboard

 Introduction
This Power BI dashboard for HR analytics, designed to provide insights into employee data and help businesses make data-driven decisions. The dashboard includes a variety of key performance indicators (KPIs), such as overall employees, attrition count, attrition rate, Average year, and average age of employees.

To create the dashboard, I used various Power BI visualizations, such Slicer for filtering data department-wise attrition, stacked column charts for the number of attrition count by age, matrix charts for job satisfaction ratings, clustered bar charts for salary slab of employees, and attrition by Job role , Area chard to visualize no. of attrition by year at company, Tree map to show no. of attrition by gender of different age group and donut charts for attrition count for different education groups. These visualizations were chosen to provide an intuitive and interactive way to analyse employee data, and to enable users to quickly identify trends and patterns.

By using this dashboard, businesses can gain a better understanding of their workforce, identify areas that require improvement, and make data-driven decisions to improve employee retention and satisfaction. Additionally, the Power BI dashboard provides a centralized location for HR analytics data, making it easier to access and analyse data from various sources.
Overall, this HR analytics Power BI dashboard is a valuable tool for businesses looking to improve their HR processes and make more informed decisions based on employee data. The dashboard is customizable and can be adapted to fit the specific needs of individual businesses.
                 Objectives 
The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization. This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis.
Throughout this project, I've had the chance to:
Dive deep into HR data to uncover valuable insights.
Develop interactive dashboards to visualize key HR metrics.
Provide data-driven recommendations for strategic decision-making.
	
 Tools and Platform
Software- Power BI Desktop
Power BI
Power Query
DAX Query

Steps followed:
1. Data Gathering:
Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
2. Data cleaning:
Cleaning is done by removing empty column, removing duplicates, errors etc.
Replacing values in column with proper values and naming.
Detecting data type of every column, using the auto detect data type function in Power query editor.
3. Data processing:
In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
4. Data analysis:
Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.



Key Questions of the Dashboard:
What is the Total Employee Count?
What is the employee's Average Age & Average Salary?
What is the Attrition Count of men and women?
What is employees Working years at the Company?
Which Department has maximum employee?
What is the Gender distribution?
Which Education Field has maximum employees?
Which Job Role Field has maximum Attrition?

Learned about:
Calculated Field: To Calculate Attrition Rate & Active Employees
Matrix table: To show Job Satisfaction rating
Donut chart and Pie Chart
Bar Chart and Cluster chart 
KPI (Key Performing Indicators) and Slicer.
Filters: Used to filter data according to different Department fields.


Key Insights Summary:
Total Employees: The organization has grown significantly, currently employing 1470 individuals, indicating substantial growth and scale.
Attrition Analysis: A total of 237 employees left the organization. Among them, 150 were male, and 87 were female, indicating a higher attrition rate among males.
Departmental Attrition: The Research and Development Department experienced the highest attrition rate at 56.13%, suggesting potential areas for improvement in employee retention strategies in this department.
Education Field Impact: Employees in the life sciences field had the highest attrition rate, emphasizing the need to address retention challenges in this specific area.
Job Role Affected: The sales role had the highest attrition rate, indicating a need for focused retention efforts in this department to reduce turnover.
Education wise Attrition: The attrition rate of High School is 18.24% which is maximum among the other education.

