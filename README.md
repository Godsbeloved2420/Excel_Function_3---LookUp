# Excel_Function_Analysis using LookUp Function


## 1.0. Title

Excel_Function_Analysis using LookUp Function

## 2.0 Introduction

### 2.1. Objectives: 

The aim of the analysis were to look-up the different salary compensation schedule for the different grade levels from a salary structure chart.

### 2.2. Context:

The dataset is made up two datasets: the organizational Database which is the Salary Compensation Schedule as at 1st January 2020 and the Simple Salary Structure. The Database is made up of: seriel number, employee number, employee names, departments, grade level. Other columns like: 
Basic, housing, transport, meal, leave, utility and gross pay was look-up from the Simple Salary Structure sheet using VLOOKUP function. The Simple Salary Structure chart which represent the simple salary scale per level have columns like: Level, Basic, housing, transport, meal, leave, utility and gross. This sheet served as the look-up array.

### 2.3. Data Sources

The primary source of data used here is Excel_Function 3-LookUp.xlsx which was gotten as an excel file and was supplied by the facilitator.

## 3.0. Data Understanding

### 3.1. Data description
The dataset was gotten in a structured form. The Database sheet has 85 observations and 5 fields while the Simple Salary structure sheet contains 9 observations and 8 fields.

### 3.2. Exploratory data analysis (EDA)

Microsoft Excel was implored in analyzing the dataset. At the end of the analysis, we were able to look-up the basic, housing, transport, meal, leave, utility and gross salary from the simple salary structure chart into the database using VLOOKUP function.

## 4.0. Methodology

### 4.1. Data preprocessing

The dataset was not preprocessed because it came as cleaned data.


## 5.0. Analysis

### 5.1. Results

#### To look-up the Basic salary from the salary structured chart for each of the level, the following formula was used.

```Excel
=VLOOKUP(E9,'Simple Salary Structure'!$B$8:$I$16,2,0)

```
Where the look-up value is the grade level, the table array is the simple salary structure table, the column index number is the column number of the particular column to look-up from, and the range shows whether the exact match is needed for the look-up or approximate match where zero(0) represents Exact match and one(1) represents approximate match.

The table array cells was locked so as to enable flash-filling to take effect for each of the level and salary without encountering an error.
                        
### 5.2. Interpretation/key findings: 

From the result, it can be seen:

•	The Director has the highest gross salary more than any other employee of other grades.

•	The different salaries: basic, housing, transport, meal, leave, utility and gross salary for each of the employee was gotten from the salary structure chart using VLookup function

## 6.0. Conclusion

### 6.1. Summary of finding:

•	The dataset is made up two datasets: the organizational Database which is the Salary Compensation Schedule as at 1st January 2020 and the Simple Salary Structure. 

•	The analysis is aimed at looking up the different salary structure for each employee in the company based on their grade and to get the gross payment for each of the employee.

•	VLOOKUP formula was implored in the analysis.

•	The Director has the highest gross salary more than any other employee of other grades.


## 7.0. Acknowledgement

I acknowledge LITA for this great platform for learning. I want to sincerely appreciate Mr. Joseph Elijah for providing the dataset that was used for this analysis. Google Colab was employed in this analysis.

