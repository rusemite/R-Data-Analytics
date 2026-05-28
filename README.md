HR Analytics: Data Analysis with R
This repository contains a dataset focused on Human Resources (HR) metrics within multinational companies (MNCs). It is designed for practicing data cleaning, exploratory data analysis (EDA), and predictive modeling using the R programming language.
📂 Repository Structure
HR_Data_MNC_Data Science Lovers.csv.gz: The primary dataset in a compressed CSV format.
📊 Dataset Overview
The dataset is typically used to predict the probability of an employee leaving their current job or looking for a new one (Employee Attrition/Churn).
Key Features:
city_development_index: Development index of the employee's city.
experience: Total years of experience.
education_level: Level of education (Graduate, Masters, PhD, etc.).
last_new_job: Difference in years between previous and current job.
training_hours: Training hours completed.
target: 0 if not looking for a job change, 1 if looking for a job change.
🛠 Getting Started with R
You can load the compressed dataset directly into your R environment using read.csv or the tidyverse package.
Loading the data:
# Using base R
data <- read.csv("HR_Data_MNC_Data Science Lovers.csv.gz")

# Using tidyverse (Recommended)
library(readr)
hr_data <- read_csv("HR_Data_MNC_Data Science Lovers.csv.gz")

# Preview the data
head(hr_data)
str(hr_data)
📈 Suggested Analysis Tasks
Exploratory Data Analysis (EDA): Use ggplot2 to visualize the relationship between education_level and the target variable.
Data Cleaning: Handle missing values using dplyr or tidyr.
Statistical Modeling: Run a Logistic Regression (glm) to identify key factors influencing employee turnover.
Reporting: Create an RMarkdown or Quarto report summarizing your findings.
📜 License
This project is open-source and available under the MIT License.
