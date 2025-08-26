# ABC Company Employee Analysis

## Project Overview
This project analyzes the ABC Company employee dataset to understand team distribution, employee positions, age demographics, salary expenditure, and the relationship between age and salary. The analysis was performed using Python (pandas, numpy) in a Jupyter Notebook environment.

---

## Data Source
The dataset was provided through Google Sheets and imported using pandas.  
- Original rows: 458 (excluding header)
- Cleaned rows: 447 (after removing rows with missing critical fields and duplicates)

---

## Preprocessing Steps
1. Imported the dataset from Google Sheets into pandas.
2. Renamed columns for consistency (Name, Team, Position, Age, Salary, etc.).
3. Replaced the Height column with random integers between 150 and 180 cm as per assignment instructions.
4. Converted Age and Salary to numeric data types.
5. Removed rows with missing values in critical columns (Team, Position, Age, Salary).
6. Removed duplicate rows.

---

## Analysis and Results

### 1. Distribution of Employees by Team
- Total unique teams: 30
- Top teams by headcount:
  - New Orleans Pelicans: 19
  - New York Knicks: 16
  - Milwaukee Bucks: 16
  - Utah Jazz: 16
  - Dallas Mavericks: 15 (several teams tied at 15)

### 2. Distribution of Employees by Position
- SG: 99
- PF: 97
- PG: 88
- SF: 84
- C: 79

### 3. Predominant Age Group
- Age group counts:
  - <=25: 195 employees (43.7%)
  - 26-30: 163 employees (36.5%)
  - 31-35: 67 employees
  - 36-40: 22 employees
  - 41 and above: 0 employees
- Predominant age group: <=25

### 4. Salary Expenditure Analysis
- Team with highest total salary: Cleveland Cavaliers (106,988,689)
- Position with highest total salary: Center (C) with 466,377,332
- Top 5 teams by salary:
  - Cleveland Cavaliers: 106,988,689
  - Los Angeles Clippers: 94,854,640
  - Oklahoma City Thunder: 93,765,298
  - Golden State Warriors: 88,868,997
  - Chicago Bulls: 86,783,378

### 5. Correlation Between Age and Salary
- Pearson correlation: 0.2140
- Interpretation: Weak to moderate positive correlation, meaning salary slightly increases with age but the relationship is not strong.

---

## Key Insights
- The company workforce is young, with 80% employees aged 30 or below.
- Cleveland Cavaliers has the highest salary expenditure among teams.
- Centers (C) account for the largest cumulative salary expenditure among positions.
- Age has only a weak positive correlation with salary.

---


