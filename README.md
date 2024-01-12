# HR Data Analysis
### Overview
This data analysis project is a dummy project in which I performed 10 types of analysis on a dummy dataset known as HR Dataset.

### Tools
In this project I am going use two most important data analysis tools used in industries.

- Excel - Data Cleaning
  Excel is the most fundamental tool used in data analysis for data cleaning and analysing.
  
- Power BI - Creating Reports
  A business intelligence tool provided by microsoft to analyze data and make some beatufull dashboards.

### Data Cleaning/Preparation

In the initial data preparation phase, I performed the following tasks:
- Data Loading and inspection
- Handling Missing Values
- Data Cleaning and formatting

### Exploratory Data Analysis (EDA)

EDA involved exploring the HR Data to answer some key questions, such as:

1) How many people are in each job?
2) Gender break-down of the staff
3) Age spread of the staff
4) Which jobs pay more?
5) Top earners in each job
6) Qualification vs. Salary
7) Staff growth trend over time
8) Employee filter by starting letter
9) Leave balance analysis
10) Quick HR Dashboard

### Data Analysis

In the data analysis part I have analyzed the data and made some new measures as well using DAX (Data Analysis Expression).
1. Getting the headcount - Counting the number of rows in the staff table which eventually helped us to answer the questions.
   
   ``` DAX
   Headcount = countrows(employees)
   ```
   
![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/0895dde4-9a26-4e34-96cb-013fde54f758)


2. Creating a measure to know the average salary from the overall salary column.

   ```DAX
   Avg. Salary = AVERAGE(employees[salary])
   ```
   
### Results

From the anaylsis of the data I have answered all the questions and also gained some key insights from them whih are displayed in the form of charts below.

1. Packaging associate is the most loved job and has the maximum number of employees in it, whereas marketing specialist is the job with least number of employees. Need to focus more on marketing specialists job recruitements.

![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/b121968b-6c2f-4097-8455-3fcc2befd4d7)

                                           
2. On the overall basis most of the employees in the company are female but for some of the jobs the ratio between both the genders is nearly 50-50.

![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/96e41827-1681-4509-893d-cd37268afab6)



3. As there are a large number of employees with different different ages, so I decided to group them in age groups which basically combines the individual ages into age groups of 5 years. 25 to 35 is the age groups with most employees in the companies.

![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/0790efd2-4503-4e41-ac5f-875d6de9d4fd)



4. Product Manager is the most high paying job and packaging associate which has the most numbeer of employees is the least paid job.

![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/0c11d0f1-76b0-47ea-9839-26c6bafc3003)


5. The visuals helped in determinig top three and bottom three earners on the basis of salary. 

![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/56680b03-3d2d-407e-9403-8a90bf7a732c)

6. Master's degree are the most paid followed by the diploma. The maximum number of employees have done bachelor's degree.

    ![image](https://github.com/Vivek-Mishra-2/HR-Data-Analysis/assets/114797063/2e4c7eac-6cc9-468c-a6f7-14519c82faa0)
