# ABC Company Employee Data Analysis Project

## 📊 Project Overview

This project involves an in-depth analysis of a dataset provided by ABC Company, containing information about its employees across various teams. The objective is to preprocess the data, analyze key attributes, and derive actionable insights that can aid the company in understanding its workforce distribution, salary trends, and demographic patterns.

### 🔍 **Key Objectives:**
1. **Data Preprocessing**: Cleaning and preparing the dataset to ensure accuracy and consistency.
2. **Data Analysis**: Extracting valuable insights from the dataset through statistical analysis.
3. **Visualization**: Presenting findings effectively using graphical representations.
4. **Data Storytelling**: Summarizing trends and patterns in a clear and concise manner.

## 📂 Dataset Information

- **Dataset**: The dataset consists of 458 rows and 9 columns, covering various attributes of the employees, such as:
  - **Employee ID**: Unique identifier for each employee.
  - **Team**: The department or team the employee belongs to.
  - **Position**: The job title or role of the employee.
  - **Age**: Age of the employee.
  - **Height**: Height of the employee (preprocessed).
  - **College**: The college or educational institution of the employee.
  - **Salary**: The annual salary of the employee.
  - **Gender**: Gender of the employee.
  - **Experience**: Number of years of experience.

## ⚙️ Data Preprocessing

### **Steps Involved:**
1. **Missing Value Handling**:
   - Filled missing values in the `"college"` column with `"Unknown"`.
   - Replaced missing values in the `"salary"` column with the median salary to minimize the impact of outliers.
2. **Data Correction**:
   - Replaced the `"height"` column values with random integers between 150 and 180 to ensure data consistency.
3. **Data Validation**:
   - Ensured no missing values remained after preprocessing.
   - Checked data types and corrected any inconsistencies.

## 📈 Data Analysis Tasks

### **Analysis Performed:**
1. **Employee Distribution by Team**:
   - Calculated the number and percentage of employees in each team.
   - **Visualization**: Bar plot showing the distribution of employees across teams.

2. **Employee Segregation by Position**:
   - Analyzed the distribution of employees across different job roles.
   - **Visualization**: Bar plot displaying the frequency of each position.

3. **Predominant Age Group**:
   - Categorized employees into different age groups to identify the predominant age range.
   - **Visualization**: Bar plot illustrating the age group distribution.

4. **Highest Salary Expenditure by Team and Position**:
   - Determined which teams and positions had the highest total salary expenditures.
   - **Visualization**: Bar plots for total salary expenditure by team and position.

5. **Correlation Between Age and Salary**:
   - Analyzed the relationship between an employee’s age and their salary using correlation analysis.
   - **Visualization**: Scatter plot displaying the correlation between age and salary.

## 🔍 Key Insights

1. **Team Distribution**: The analysis revealed significant variations in team sizes, with New Orleans Pelicans being the largest and Orlando Magic, Minnesota Timberwolves being the smallest.
2. **Position Analysis**: The most common role was SG, indicating its critical function within the company.
3. **Age Demographics**: The age group 25-34 was predominant, reflecting a relatively younger workforce at ABC Company.
4. **Salary Expenditure**: The highest salary expenditure was seen in Cleveland Cavaliers and the C, suggesting these are high-value roles requiring specialized skills or leadership.
5. **Age-Salary Correlation**: A positive correlation was found between age and salary, indicating seniority trends in the company.

## 📊 Visualizations

The analysis included several visualizations to effectively present the findings:
- **Bar plots** for team and position distributions.
- **Age group analysis** using a bar plot.
- **Salary expenditure** analysis using bar plots for teams and positions.
- **Scatter plot** for visualizing the correlation between age and salary.

## 📑 Conclusion

This project provided a comprehensive analysis of ABC Company's employee dataset, uncovering key insights into workforce distribution, salary trends, and demographic characteristics. The findings offer valuable guidance for the company’s strategic decision-making in areas such as hiring, salary adjustments, and workforce planning. By understanding these trends, ABC Company can better align its human resources strategies with its organizational goals.

## 🗂️ Repository Structure

```
├── ABC_Company_Employee_Analysis.ipynb  # Jupyter Notebook with complete analysis
├── myexcel-myexcel.csv                  # Dataset file
├── README.md                            # Project overview and details
```

## 🛠️ How to Run the Project

1. **Install Required Packages**:
   - Ensure you have Python installed. Install the necessary packages using:
     ```
     pip install pandas numpy matplotlib seaborn
     ```
2. **Open the Jupyter Notebook**:
   - Run the notebook using Jupyter:
     ```
     jupyter notebook ABC_Company_Employee_Analysis.ipynb
     ```
3. **Explore the Analysis**:
   - Follow through the notebook to see the data preprocessing, analysis, and visualizations.

## 📝 Author

- DEEPTHY A - deepthydevadasan@gmail.com

## 🔗 References

- Python Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## 📅 Submission
This project was submitted as part of a data analysis task, providing a comprehensive exploration of the company's employee dataset.
