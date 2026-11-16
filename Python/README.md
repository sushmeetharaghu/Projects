# Employee Project Data Analysis: Python Fundamentals Capstone

## Description

**This capstone project uses Python and Pandas to clean, combine, and analyze employee and project data, turning three separate tables into one consolidated dataset with bonuses, designation changes, and cost summaries.**

Starting from three raw tables (Project, Employee, and Seniority Level), this project fills in missing project costs using a running average, splits and formats employee names, and joins everything into a single "Final" dataframe. It then applies business rules to calculate a 5% bonus for finished projects, demote the designation level of employees whose projects failed, promote employees older than 29, and remove anyone who falls out of eligibility. Finally, it summarizes the total project cost per employee and filters employees by city.

## Dataset

| Table | Columns | Rows |
|---|---|---|
| Project | ID, Project, Cost, Status | 14 |
| Employee | ID, Name, Gender, City, Age | 5 |
| Seniority Level | ID, Designation level | 5 |

Designation scale: 1 is the highest, 2 and 3 are mid positions, and 4 is the lowest. Anyone above 4 loses eligibility to head a project.

## Skills Used

*Data cleaning, Data manipulation, Missing value imputation, Data merging and joins, Aggregation and grouping, Conditional logic, String processing, File handling (CSV)*

## Technologies and libraries Used

**Python, Jupyter Notebook, Pandas, NumPy**

## Tasks Completed

1. Created three dataframes and saved them as `.csv` files (all later tasks read from these files only)
2. Replaced missing project costs with a running average using a `for` loop
3. Split the employee `Name` column into `First name` and `Last name`
4. Joined all three dataframes into one `final` dataframe
5. Added a `bonus` column: 5% of project cost for finished projects only
6. Demoted designation level by 1 for failed projects and removed records above level 4
7. Added "Mr." / "Mrs." to first names and dropped the `Gender` column
8. Promoted designation level by 1 for employees older than 29 using an `if` condition
9. Created a `totalprojcost` dataframe with the total project cost per employee
10. Filtered employees whose city name contains the letter "o"

## Final Outcome

The final outcome of this project is a clean, analysis-ready dataset and a set of summary outputs built entirely with Pandas and NumPy. This includes:

- Two missing project costs filled with running averages (Project5 = 3,250,500 and Project9 = 2,061,714)
- A consolidated `final` dataframe with bonus amounts and updated designation levels for every project
- A `totalprojcost` summary showing total project cost per employee:

| ID | Employee | Total cost |
|---|---|---|
| A001 | Mr.John | 5,063,714 |
| A002 | Mrs.Alice | 2,680,000 |
| A003 | Mr.Tom | 5,150,000 |
| A004 | Mrs.Nina | 9,500,000 |
| A005 | Mrs.Amy | 3,850,500 |

- A filtered list of employees based in cities containing the letter "o" (London and Newyork)

## Files in this Repository

- `python_project.ipynb`: notebook with all code, comments, and outputs
- `Capstone project - Python Fundamentals.pdf`: the project problem statement

## How to Run

1. Clone this repository
2. Install the requirements: `pip install pandas numpy jupyter`
3. Open `python_project.ipynb` in Jupyter Notebook
4. Run the cells in order, since each task reads the `.csv` files saved by the earlier tasks
