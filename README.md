There are 282191 rows and 21 columns in this dataset. 

-------------

The same data cleaning procedures apply for Excel too.

4 steps:
1) Removing duplicates
2) Standardizing Data
3) Handling NULL Values
4) Deleting Unnecessary Rows/Columns if possible

-----------

I followed these guidelines as well as the reference video.

---------

### Scenario and the three requests:

![Page1](Images/P-1.png)

----------

### Raw Data:

![Raw Data-1](Images/P-2.png)

![Raw Data-2](Images/P-3.png)

----------

- To get the day of the week from the date, use the function WEEKDAY(H2; 1) --> Sunday:1... Saturday:7
- Then, change the numbers 2,3,4,5,6 to Monday, Tuesday, Wednesday, Thursday, Friday.
- One can change the number format in the WEEKDAY function.
- For example, WEEKDAY(H2; 2) gives 1 (Monday) through 7 (Sunday).

![Data Cleaning 1](Images/Data_Cleaning1.png)

----------

Now, standardize the bus company name:

1) Insert a new blank column beside the original column.
2) Use filters to find the most general bus company name for each of them --> manually done.
3) Utilize copy-paste and CTRL+Shift+Down Arrow to quicken the process.

![Data Cleaning 2](Images/Data_Cleaning2.png)

----------

Use text to row button to separate delay times.
- Later, the average of the low end and high end numbers are used inside pivot tables and charts.

![Data Cleaning 3](Images/Data_Cleaning3.png)

-----------

### The first request is handled - Part 1 - Common Delay Reasons

![Common Delay Reasons 1](Images/CommonDelayReasons1.png)

-----------

Part 2 - Common Delay Reasons

![Common Delay Reasons 2](Images/CommonDelayReasons2.png)

------------

### The second request is managed - Part 1 - Delay Times

![Delay Times 1](Images/DelayTimes1.png)

-----------

Part 2 - Delay Times

![Delay Times 2](Images/DelayTimes2.png)

-----------

Part 3 - Delay Times

![Delay Times 3](Images/DelayTimes3.png)

-----------

### The last request is taken care of - Part 1 - Day of Week

![Day of Week 1](Images/DayOfWeek1.png)

-----------

Part 2 - Day of Week

![Day of Week 2](Images/DayOfWeek2.png)

-----------

### Thank you!
