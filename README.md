# EMPLOYEE ATTRITION PREDICTION

## Problem Statement
The Human Resources (HR) department of a software company is seeking to transition from a reactive to a proactive employee retention strategy. Currently reliant on exit interviews for insights into employee departures, this approach is hindered by its dependence on interviewer skill, difficulties in aggregating insights, and delayed policy implementation. The proposed project aims to utilize Machine Learning model to predict potential employee turnover among permanent staff, enabling timely and targeted interventions. By identifying at-risk employees before they decide to leave, the HR department intends to improve retention rates, employee satisfaction, and ultimately, foster a more stable and motivated workforce.

## Dataset Description
We have 3 datasets:

1. **department_data**

    This dataset contains information about each department.<br>
    
    __Schema:__<br>
        __dept_id__ – Unique Department Code <br>
        __dept_name__ – Name of the Department <br>
        __dept_head__ – Name of the Head of the Department <br>


2. **employee_details_data** <br>

    This dataset consists of Employee ID, their Age, Gender and Marital Status. <br>
    
    __schema:__<br>
        __employee_id__ – Unique ID Number for each employee<br>
        __age__ – Age of the employee<br>
        __gender__ – Gender of the employee<br>
        __marital_status__ – Marital Status of the employee<br>


3. **employee_data**<br>

    This dataset consists of each employee’s Administrative Information, Workload Information, Mutual Evaluation Information and Status.<br>

    __schema:__<br>
        __status__ – Current employment status (Employed / Left)<br>
        __department__ – Department to which the employees belong(ed) to <br>
        __salary__ – Salary level with respect to rest of their department <br>
        __tenure__ – Number of years at the company<br>
        __recently_promoted__ – Was the employee promoted in the last 3 years?<br>
        __employee_id__ – Unique ID Number for each employee<br>
        __n_projects__ – Number of projects employee has worked on<br>
        __avg_monthly_hrs__ – Average number of hours worked per month<br>
        __satisfaction__ – Score for employee’s satisfaction with the company (higher is better)<br>
        __last_evaluation__ – Score for most recent evaluation of employee (higher is better)<br>
        __filed_complaint__ – Has the employee filed a formal complaint in the last 3 years?<br>
