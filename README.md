# School_District_Analysis
with Pandas

## Project Overview
A chief data scientist for a city school district is responsible for the following tasks:
- analyzing information from a variety of sources and formats
- preparing all standardized test data for analysis, reporting, and presentation
- providing insights about performance trends and patterns to the school Board, so decisions can be made about student funding and test scores.

## Resources
- Data Sources: schools_complete.csv and students_complete.csv
- Software: Conda 4.10.3, Python 3.7.6, Jupyter Notebook 6.3.0, Pandas, and NumPy

## Summary 
The list of deliverables for the analysis of the school district: 

- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:

### Top 5 and bottom 5 performing schools, based on the overall passing rate
![Top_5_Schools.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Top_5_Schools.png)
![Bottom_5_Schools.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Bottom_5_Schools.png)

### The average math score received by students in each grade level at each school
![Math_Scores_by_Grade.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Math_Scores_by_Grade.png)

### The average reading score received by students in each grade level at each school
![Reading_Scores_by_Grade.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Reading_Scores_by_Grade.png)

### School performance based on the budget per student
![Spending_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Spending_Summary.png)

### School performance based on the school size 
![Size_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Size_Summary.png)

### School performance based on the type of school
![Type_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Type_Summary.png)
    
## Challenge Overview 
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Challenge Results
The following are the updated results:
- How the district summary was affected: Cleaning the data  and using the new student count resulted in a decline in average scores and percentages. The Average Math Score went down 0.1 points, the Average Reading Score did not change, the % Passing Math went down 0.20%, the % Passing Reading went down 0.10%, and the % Overall Passing went down 0.30%. See comparison charts below:
![Original_District_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Original_District_Summary.png)
![New_Student_Count_District_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/New_Student_Count_District_Summary.png)

- How the school summary was affected: The only calculations that changed were the last five columns for Thomas High School. As shwon in the below comparison charts below; the Average Math Score and the Average Reading Score did not change much while the % Passing Math, the % Passing Reading, and the % Overall Passing declined 28%:
![Original_School_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Original_School_Summary.png)
![New_Student_Count_School_Summary.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/New_Student_Count_School_Summary.png)
![Summary_School_Comparison.png](https://github.com/KimberlyCrawford/School_District_Analysis/blob/main/Resources/Summary_School_Comparison.png)

- How replacing the ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other schools:
- How replacing the ninth-grade scores affected the following:

### Math and reading scores by grade:
### Scores by school spending:
### Scores by school size:
### Scores by school type:

## Challenge Summary 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. Change 1
2. Change 2
3. Change 3
4. Change 4

#### Module 4, Data Analysis & Visualization Certificate Program, UT Austin McCombs School of Business, 2021.
