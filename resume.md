# Statistical Pitch: The Burden of California's Rising Education Costs 
## Story Summary 
  In recent decades, American universities have witnessed a steady surge in tuition fees, rendering them increasingly unaffordable for potential students. The average expenses across all universities substantially increased from 2013 to 2023, far outpacing the growth in available financial aid. Consequently, the soaring costs of attendance have reached a point where they appear unrealistic when compared to the annual household income in California, as evident from the data.

  Despite the median annual household income and financial aid seeing some improvement, the expanding affordability gap has left numerous students burdened with overwhelming student loan debts. In order to preserve the accessibility to knowledge for countless individuals, policymakers and educators must take prompt and decisive action to ensure that higher education remains within reach for all. 

## Data Analysis Process 
  My goal was to gather information about the increasing financial burden on students due to high tuition fees and living costs in college. This collection of data examines college fees and financial aid trends at 13 public universities in California, along with the changes in household income in the state. These are the colleges analyzed in alphabetical order:

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

  As I analyzed the data, I observed that college expenses are increasing, making it harder for students to afford college and a high quality education. Through this research, I aim to raise awareness about accessibility to higher education  and encourage actions to make college more affordable for students in California.

## Scope of Analysis
1. **Percentage Change for Off-Campus Costs of Attendance by University (Tuition Fees and Living Expenses), for Both Out-of-state and In-state students.**
    - _Compute the percentage change in the costs of attendance for off-campus, in-state, and off-campus, out-of-state students at all universities between the academic years 2013-14 and 2022-23. What is the average increase in costs of attendance among all universities?_
2. **Change in Percentage of Average Amount of Financial Aid Received per Student By University.**
    - _Analyze the percentage change in each type of financial aid (grant/scholarships, Pell grants, and federal student loans) at each university between the academic years 2013-14 and 2021-22._
3. **Change in Percentage in the Count of Students Receiving Financial Aid Across University**
    - _Calculate the percent change of the percent of Students receiving financial aid by University between 2013-14 and 2021-22, also for all three types of financial aid._
4. **Average Increase of Annual Household Income in the State of California**
    - _Find the average increase of annual household income in the State of california across 2013-2021 and compare it to the average increase of costs of attendance of all universities together. What is the difference between both percentages?_
6. **Top 5 Universities with Highest Increase in Costs of Attendance and Their Accompanied Trends in Financial Aid.**
    - _During the period from 2013 to 2023, identify the top 5 universities with the most significant increase in costs of attendance and examine the corresponding increases in financial aid offered at each of these universities._
7. **The Cost of Attendance For the Top 5 Universities With the Highest Increases in 2021-22 and 2022-23.**
    - What the costs of attendance for the school years 2021-22 and 2022-23 for these universities are. For the year 2021-22, how much percent does the costs of attendance cover the median annual household income of that year?
      
### Analysis 1: Percentage Change For Off-Campus Costs of Attendance by University (Tuition Fees and Living Expenses), for Both Out-of-state and In-state students.
 
_Question: Compute the percentage change in the costs of attendance for off-campus, in-state, and off-campus, out-of-state students at all universities between the academic years 2013-14 and 2022-23._

![Image 8-7-23 at 8 07 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/c935b5b3-43ef-4228-b8d5-9b4697efad01)

**Average Increase In-State Costs of Attendance:** <br />
23.14%

**Average Increase Out-of-State Costs of Attendance:** <br />
24.20%

### Sheet Used: Costs_of_attendance_by_university
#### Data Analysis Process :
1. Created two new columns to show the percentage change in IN-state and OUT-of-state costs of attendance between 2013-14 and 2022-23.
2. Using the unique letters of the columns (E and F), I calculated the percentage difference between school years 2013-14 and 2022-23: (=E11/E2/E2). 
3. The formula was applied to all rows for both columns; the rows which did not represent needed percentages for this dataset were deleted, and the percent icon (%) in the upper left corner was selected to make the values percentages.
4. Then, created a pivot table to provide a clearer overview of the percentage changes; I added “University” to Rows and the Percent Changes to Values, after which I selected SUM.
5. Finally, selected the values for each column and looked at the average.

### Analysis 2: Change in Percentage of Average Amount of Financial Aid Received per Student By University

  _Question: Analyze the percentage change in each type of financial aid (grant/scholarships, pell grants, and federal student loans) at each university between the academic years 2013-14 and 2021-22.  What is the average trend in financial aid among all universities?_
![Image 8-7-23 at 8 12 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/96f1af4b-74c6-45d3-b6e2-58683299a698)
**Average Trend Financial Aid Received, Grants/Scholarships:** <br />
13.45% <br />

**Average Trend Financial Aid Received, Pell Grants:** <br />
21.53% <br />

**Average Trend Financial Aid Received, Federal Student Loans**: <br />
-5.48%

### Sheet Used: Financial_aid_by_university 

#### Data Analysis Process :

1. Created a sheet that included the school years, universities, and their average amount of financial aid received and the number of people (and % of student population) who received financial aid for all three types (1) grant/scholarships, (2) pell grants, and (3) federal student loans. This was 8 columns in total.
2. Created 3 new columns to show the percentage change of the average amount of financial aid received.
3. Calculated the percentage change (between 2013-14 & 2021-22) using formula =(D10-D2)/D2. 
4. For the formulas, used the unique letters of the columns (D, F, and H), and applied the formulas to all the rows. 
5. Selected the Percent Icon (%) to all columns. Now I possess the percentage alteration in the average amount of received financial aid.
6. Created a pivot table and added University to Rows and Percentage Changes to Values.
7. Finally, selected all values for each column and looked at the average.

### Analysis 3: Change in Percentage of the Count of Students Receiving Financial Aid Across University

  _Question: Calculate the percentage change of the students receiving financial aid by University between 2013-14 and 2021-22 for all three types of financial aid._
![Image 8-7-23 at 10 10 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/d2383889-c594-4a4b-8724-ccdf06b4e367)

**Average Trend Students Receiving Financial Aid, Grants/Scholarships:** <br />
7.62%<br />

**Average Trend Students Receiving Financial Aid, Pell Grants:** <br />
-9.28%<br />

**Average Trend Students Receiving Financial Aid, Federal Student Loans:** <br />
-48.24% <br />


### Sheets Used: Financial_aid_by_university & Financial_aid_receiving_students

#### Data Analysis Process :

1. The dataset includes three columns that present both the precise student counts receiving financial aid and their corresponding percentages (refer to the image below):
    - ![Image 8-7-23 at 10 11 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/85a0dfc1-4c65-4bc4-8155-2554e1e4e46e)

2. To simplify the calculation, I decided to focus solely on the percentage of students receiving financial aid for each university.
3. Introduced three additional columns and utilized the formula =RIGHT(C2,5) to exclusively show the percentage of students receiving financial aid.
    - ![Image 8-7-23 at 10 12 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/74faefe8-7870-4670-ae79-b0c5a8cbfa2b)
4. Created a new sheet titled “Financial_aid_receiving_students”; then, copied and employed a special paste tehcnique for the percentage values; then, calculated the percentage changes between years 2013-14 and 2021-22 using the formula =(C10-C2)/C2
5. Lastly, generated a pivot table to provide a clear summary of the changes in percentages by university. I included the "University" in the Rowssectiond and the variations in the percentage of students receiving grants/scholarships, pell grants, and federal student loans were included in the Values section.

### Analysis 4: Average Increase of Annual Household Income in the State of California
  _Question: Find the average increase of annual household income in the State of california across 2013-2021._
![Image 8-7-23 at 10 15 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/7b2aa2b9-5250-4b48-974e-e262ee1e6485)

### Sheets Used: Median Household Income

#### Data Analysis Process :

1. Looked at median household income of the years 2013 and 2021
![Image 8-7-23 at 10 15 PM (1)](https://github.com/kikidebruijne/j21-project/assets/140004293/6afb21ac-10c4-4972-af0f-e8db5a017ddf)
2. Calculated the percentage increase in median household income with the formula =(B39-B31)/B31, after which I selected the percentage icon in the upper left corner to convert the number into percentages.

### Analysis 5: Top 5 Universities with Highest Increase in Costs of Attendance and Their Accompanied Trends in Financial Aid.

  _Question: During the period from 2013 to 2023, identify the top 5 universities with the most significant increase in costs of attendance and examine the corresponding increases in financial aid offered at each of these universities._
![Image 8-7-23 at 10 23 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/96ea7073-3ab4-42eb-9e01-3cbe688e4f8c)
![Image 8-7-23 at 10 23 PM (1)](https://github.com/kikidebruijne/j21-project/assets/140004293/2493e90a-d66f-4f1b-b02e-3c240c1b0785)

### Sheet Used: Costs_of_attendance_by_university & Financial_aid_receiving_students

#### Data Analysis Process :

1. Utilized a pivot table to illustrates the changes in percentage of costs of attendance by university. Subsequently, I duplicated the values and used a special paste function to transfer them into a freshly created sheet named "Percentage_change_costs_of_attendance."
    - ![Image 8-7-23 at 10 23 PM 2](https://github.com/kikidebruijne/j21-project/assets/140004293/04d58c17-6fb5-434b-951d-46c8ff2ed207)
2. Created a new column and combined the change in percentages of In-state and Out-of-State costs of attendance by using the formula =(B2+C2)/2. 
3. Selected the new column and sorted sheet from Z to A, leaving highest percentages at the top, and lowest percentages at the bottom. Screenshotted top 5.
4. Then created a new pivot table from the Financial_aid_by_university sheet; added university to Values and changes in percentages per financial aid to values.
5. Created a filter and selected top 5 universities.

### Analysis 6: The Cost of Attendance For the Top 5 Universities With the Highest Increases in 2021-22 and 2022-23.

  _Question: what the costs of attendance for the school years 2021-22 and 2022-23 for these universities are. For the year 2021-22, how much percent does the costs of attendance cover the median annual household income of that year?_
![Image 8-7-23 at 10 28 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/b49a0e4b-269c-486f-84a2-0f99375ec5ad)
![Image 8-7-23 at 10 28 PM 2](https://github.com/kikidebruijne/j21-project/assets/140004293/8bf3b3b2-9c3b-4d1e-b599-71c1c77a69c7)

### Sheet Used: Costs_of_attendance_by_university & Median_Household_Income_California

#### Data Analysis Process :

1. Created a pivot table and added Universities and Years to Rows and average costs of attendance to Values. 
2. Created filter, selected top 5 schools
3. Copy pasted the schools into a new sheet and deleted all years but 2021-2022 and 2022-23 from the sheet.
4. Then, to calculate how much percent the costs of attendance cover the median annual household income for 2021-22, I filtered out the year 2021-22 and copy special pasted it into a new spreadsheet, where I also added a new column with the median household income of the year 2021:
    - ![Image 8-7-23 at 10 29 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/941e999b-82e8-474d-969c-b698b7e458d0)
5. Finally, I created a formula to calculate how much percent the costs of attendance, both Out-of-State and in-state: =(C2/E2) and selected the percentage icon to convert the numbers into percentages.

## Sourcing 

### Potential Interview Contacts:

1. **Lillian Kimbell**
    - _Contact information: phone number: 818-248-2925_
    - Work Position: Legal Counsel and Business Manager of the Center for the Study of Democratic Institutions
      - Lillian Kimbell plays a significant role in the decision making processes behind college tuition fees’ increases concerning California State Universities. Including someone who is involved in the discussion and difficult decision-making processes concerning tuition fees could offer us a different, maybe more understanding perspective about the topic of the rising tuition fees. 

2. **Emma Kerr**
    - _Contact information: ekerr@usnews.com_
    - Work Position: Personal finance editor at U.S News.
      - In her specialized expertise in reporting on issues relating to educational finance and family finance, debt, spending, and so on, Emma could provide me and the reader with a deeper understanding of the topic of higher college tuition fees, as well as how financial aid and family income relate to this topic. By incorporating the views and knowledge of an expert in these topics, I can clarify my story as well as some important details that might be confusing to both myself and the reader. To make the story useful and engaging, Emma Kerr could also come with tips and tricks for both students and family to better deal with the increasing financial burden of paying for an education. 


### Additional Sources 

1. [Division Costs of Attendance](https://financialaid.berkeley.edu/how-aid-works/student-budgets-cost-of-attendance/)
  - A dataset providing us with details of the division of attendance costs:
    - It would be helpful to have an additional dataset that provides us with the details of where exactly the costs of attendance are going in order to better understand why tuition fees are increasing. This will allow us to identify where expenses are growing the most. Are housing costs the biggest contributor to increased attendance costs, or are professors and GSIs' expenses increasing? We will be able to understand exactly where the problem is most prevalent, and we will also be able to take action to limit the harmful effects of tuition increases.

2. [Data Analysis of World University Ranking](https://rpubs.com/jdiaz50/234350)
- A dataset providing us with the trends of college ratings)
  - The trends in college ratings will also help us understand and analyze the rises and falls in tuition costs. We can answer crucial questions such as whether colleges with the highest increases in tuition and living costs have also improved their college rankings.


## Data Visualization
1) [Costs of Attendance California, Off Campus](https://www.datawrapper.de/_/Sy5NY/)
   
![Image 8-8-23 at 11 09 AM](https://github.com/kikidebruijne/j21-project/assets/140004293/13c91c8f-2e88-4d77-ba12-8f3469b9a643)

2) [Median Annual Household Income spent on Costs of Attendance](https://www.datawrapper.de/_/YEgMx/)

![Image 8-8-23 at 3 19 PM](https://github.com/kikidebruijne/j21-project/assets/140004293/ae0935ae-6ad1-46f9-b2c9-8c6694c7525d)

