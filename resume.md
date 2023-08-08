# Statistical Pitch: The Burden of California's Rising Education Costs
## Story Summary 
  In recent decades, American universities have witnessed a steady surge in their tuition fees, rendering them increasingly unaffordable for potential students. The average expenses across all universities saw a substantial increase from 2013 to 2023, far outpacing the growth in financial aid availability. Consequently, the soaring costs of attendance have reached a point where they appear unrealistic when compared to the annual household income in California, as evident from the data.

  Despite the median annual household income and financial aid seeing some improvement, the expanding affordability gap has left numerous students burdened with overwhelming student loan debts. In order to preserve accessibility to knowledge for countless individuals, policymakers and educators must take prompt and decisive action to ensure that higher education remains within reach for all and does not become an unattainable aspiration.

## Data Analysis Process
  I wanted to gather information about the increasing financial burden on students due to high tuition fees and living costs in college. This collection of data examines college fees and financial aid trends at 13 universities in California, along with the changes in household income in the state. All but one of these universities could be analyzed; that is, the University of California, San Francisco. The colleges analyzed in alphabetical order:

1. UC Berkeley 
2. UC Davis 
3. UC Irvine
4. UCLA
5. UC Merced
6. UC Riverside
7. UC San Diego
8. UC Santa Barbara 
9. UC Santa Cruz 
10. California State University, Chico 
11. California State University, Long Beach
12. California State University, Sacramento 
13. California State University, San Marcos

  As I looked at the data, I noticed that college expenses are getting more expensive, making it harder for students to afford education. Through this research, I hope to raise awareness about this issue and encourage action to make college more affordable for students in California.

## Scope of Analysis
1. **Percent Change For The Costs of Attendance (Off-Campus) by University (Tuition Fees and Living Expenses), for Both Out-state and In-state students.**
    - _Compute the percentage change in the costs of attendance for off-campus, in-state, and off-campus, out-of-state students at all universities between the academic years 2013-14 and 2022-23. What is the average increase in costs of attendance among all universities?_
2. **Change in Percentage of Average Amount of Financial Aid Received per Student By University.**
    - _Analyze the percentage change in each type of financial aid (grant/scholarships, Pell grants, and federal student loans) at each university between the academic years 2013-14 and 2021-22._
3. **Change in Percentage of Students Receiving Financial Aid By University**
    - _Calculate the percent change of the percent of Students receiving financial aid by University between 2013-14 and 2021-22, also for all three types of financial aid._
4. **Average Increase of Annual Household Income in the State of California**
    - _Find the average increase of annual household income in the State of california across 2013-2021 and compare it to the average increase of costs of attendance of all universities together. What is the difference between both percentages?_
6. **Top 5 Universities with Highest Increase in Costs of Attendance and Their Accompanied Trends in Financial Aid.**
    - _During the period from 2013 to 2023, identify the top 5 universities with the most significant increase in costs of attendance and examine the corresponding increases in financial aid offered at each of these universities._
7. **The Cost of Attendance For the Top 5 Universities With the Highest Increases in 2021-22 and 2022-23.**
    - What the costs of attendance for the school years 2021-22 and 2022-23 for these universities are. For the year 2021-22, how much percent does the costs of attendance cover the median annual household income of that year?
      

### Analysis 1: Percent Change For The Costs of Attendance (Off-Campus) by University (Tuition Fees and Living Expenses), for Both Out-state and In-state students.
 
_Question: Compute the percentage change in the costs of attendance for off-campus, in-state, and off-campus, out-of-state students at all universities between the academic years 2013-14 and 2022-23._

![Image 8-7-23 at 8 07 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/c935b5b3-43ef-4228-b8d5-9b4697efad01)

Average Increase In-State Costs of Attendance:
![Image 8-7-23 at 8 08 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/87501137-d9ff-432b-98b0-759d11c5b1a5)

Average Increase Out-State Costs of Attendance:
![Image 8-7-23 at 8 09 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/1b5e1690-535f-41bf-b79d-0434195a6b9a)

### Sheet Used: Costs_of_attendance_by_university
#### Data Analysis Process :
1. Created two new columns to show the percentage change in IN-state and OUT-of-state costs of attendance between 2013-14 and 2022-23.
2. Using the unique letters of the columns (E and F), I calculated the percentage difference between school years 2013-14 and 2022-23: (=E11/E2/E2). 
3. The formula was applied to all rows for both columns; the rows which did not represent needed percentages for this dataset were deleted, and the percent icon (%) in the upper left corner was selected to make the values percentages.
4. Then, I created a pivot table to show you the percent changes in a more clear overview; I added “University” to Rows and the Percent Changes to Values, after which I selected SUM.
5. Finally, selected the values for each column and looked at the average.

### Analysis 2: Change in Percentage of Average Amount of Financial Aid Received per Student By University

  _Question: Analyze the percentage change in each type of financial aid (grant/scholarships, pell grants, and federal student loans) at each university between the academic years 2013-14 and 2021-22.  What is the average trend in financial aid among all universities?_
![Image 8-7-23 at 8 12 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/96f1af4b-74c6-45d3-b6e2-58683299a698)
  Average Trend Financial Aid Received, Grants/Scholarships:
![Image 8-7-23 at 8 12 PM (1)](https://github.com/kikidebruijne/j21-project/assets/140004293/97325a2b-a134-4dbb-9abd-e995f47f7521)
  Average Trend Financial Aid Received, Pell Grants:
![Image 8-7-23 at 8 12 PM (2)](https://github.com/kikidebruijne/j21-project/assets/140004293/abb69ab6-2698-4fc6-8d1e-4113d8d1de98)
  Average Trend Financial Aid Received, Federal Student Loans:
![Image 8-7-23 at 8 12 PM (3)](https://github.com/kikidebruijne/j21-project/assets/140004293/793a83d6-5a4e-46dd-b6ae-accf2df97d92)

### Sheet Used: Financial_aid_by_university 

#### Data Analysis Process :

1. Created a sheet that included the school years, universities, and their average amount of financial aid received and the number of people (and % of student population) who received financial aid for all three types (1) grant/scholarships, (2) pell grants, and (3) federal student loans. This was 8 columns in total.
2. Created 3 new columns to show the percent change of the average amount of financial aid received.
3. Calculated percent change (between 2013-14 & 2021-22) using formula =(D10-D2)/D2. 
4. For the formulas, used the unique letters of the columns (D, F, and H), and applied the formulas to all the rows. 
5. Selected the Percent Icon (%) to all columns. Now I have the percent change of the average amount of financial aid received.
6. Created a pivot table and added University to Rows and Percent Changes to Values.
Finally, selected all values for each column and looked at the average.




