
# Analytics with Pandas
- I realized this project during my M2 in order to learn how to handle Python and particularly Pandas in order to pre-process data and analyze them 
- This project aims to manipulate a dataset for analytical purposes. The objective is to answer some analytical questions which requires a work of preprocessing, cleaning, manipulation, conversion, visualization of data
- I mainly used Pandas but also other packages and modules.




in this project, you are required to perform data profiling for a given dataset using Python. In the
there are four worksheets:
- COMPANY: firmographics
- INVESTMENT: relevant investments received by the companies
- ACQUISITION: relevant acquisitions the companies have
- EMPLOYEE: relevant employees working in the companies
To help you better understand the datasets, data dictionaries are given below.



Worksheet: EMPLOYEE
Variable Comment
EMPLOYEE_MD5 Hashed unique ID for employee
JOB_TITLES Job titles
COMPANY_NAME Company name
ATTENDED_SCHOOLS Schools that the employee has attended

- Worksheet: COMPANY

|Variable|Comment |
|--------------|------------|
|COMPANY_NAME |Company name (unique ID)|
CATEGORY| Industry category|
|LOCATION| Company location|
|FOUNDED_ON|Date that the company was founded|
|EXITED_ON|Date that the company exited (if any)|
|CLOSED_ON|Date that the company was closed (ifany)|
|REVENUE_RANGE|Revenue range|
|EMPLOYEE_NUMBER|The number of employees|

- Worksheet: INVESTMENT

|Variable|Comment |
|--------------|------------|
|COMPANY_NAME|Company name|
|FUNDING_TYPE|The type of funding|
|MONEY_RAISED|The amount of money raised in the investment|
|ANNOUNCED_DATE|Date that the investment was announced|
|INVESTMENT_STAGE|The investment stage|


- Worksheet: ACQUISITION

|Variable|Comment|
|--------------|------------|
|COMPANY_NAME|Company name|
|ACQUIREE_NAME|Name of the acquired company|
|ANNOUNCED_DATE|Date that the acquisition was announced|
|PRICE|The price of acquisition|
|ACQUISITION_TYPE|The type of acquisition|

 

- Worksheet: EMPLOYEE

|Variable|Comment|
|--------------|------------|
|EMPLOYEE_MD5|Hashed unique ID for employee|
|JOB_TITLES|Job titles|
|COMPANY_NAME|Company name|
|ATTENDED_SCHOOLS| Schools that the employee has attended|

- The notebook is structured as follows: 13 analytical questions that I asked myself while observing the dataset followed by the code required to obtain the answer.

![example](example.png)
- example of the code needed for the question: How many acquisitions did the company with the most acquisitions make per year?