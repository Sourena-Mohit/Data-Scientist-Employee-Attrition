# Data Scientist Employee Attrition - Job Change of Data Scientists

**Author:** Sourena Mohit  
**Project from:** MIT Professional Education

## Problem Statement

A company active in Big Data and Data Science aims to hire data scientists from candidates who successfully complete their training courses. Many individuals enroll in these courses, and the company wants to identify which candidates are likely to work for them after training versus those seeking new employment. This helps reduce costs, improve training quality, and plan courses and candidate categorization effectively. The dataset includes information on demographics, education, and experience provided by candidates during signup and enrollment.

## Objective
The goal is to understand the factors leading a person to leave their current job, which is valuable for HR research. By building a model using current credentials, demographics, and work experience data, we aim to predict the probability that a candidate is looking for a new job and interpret the main factors influencing an employee's decision to continue or leave.

## Data Description

- **Enrollee_id:** Unique ID for candidate
- **City:** City code
- **City_development_index:** Development index of the city (scaled)
- **Gender:** Gender of candidate
- **Relevant_experience:** Relevant experience of candidate
- **Enrolled_university:** Type of university course enrolled, if any
- **Education_level:** Education level of candidate
- **Major_discipline:** Education major discipline of candidate
- **Experience:** Candidate's total experience in years
- **Company_size:** Number of employees in the current employer's company
- **Company_type:** Type of current employer
- **Last_new_job:** Difference in years between previous job and current job
- **Training_hours:** Training hours completed
- **Target:** 0 – Not looking for job change, 1 – Looking for a job change
## Project Structure

1. **Data Collection:** Gather data from candidates during signup and enrollment.
2. **Data Preprocessing:** Clean and preprocess the data for analysis.
3. **Exploratory Data Analysis (EDA):** Analyze the data to understand patterns and relationships.
4. **Model Building:** Build predictive models to determine the probability of job change.
5. **Model Evaluation:** Evaluate the models using appropriate metrics.
6. **Interpretation:** Interpret the main factors affecting employee attrition.
7. **Conclusion:** Summarize findings and provide recommendations.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/Sourena-Mohit/Data-Scientist-Employee-Attrition.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Data-Scientist-Employee-Attrition
    ```

## License

This project is licensed under the MIT License
