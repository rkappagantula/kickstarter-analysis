# Kickstarting with Excel

## Overview of Project

The data is about content generated from various countries with detailed information of launch dates, deadlines, goals, pledeged amount and outcomes.

### Purpose

The purpose of this exercise demonstrated the use of various excel functions like converting unix timestamp to regular date format, extract year from date fields, how to create pivot tables and charts based on different data parameters

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

 - Theater outcomes are very successful in the month of May and see a steady decline in the rest of the months
 - Month of December have almost the same number of success and failures outcomes
 - zero cancelleations in the month of july

### Analysis of Outcomes Based on Goals
 - Successful percentage dropped to 0 when the goal was between 45000 to 49999
 - 50% success and failure was observed when goal was 15000 to 19999
 - The highest percentage of success was obsereved when goal was between <1000 and <49999

### Challenges and Difficulties Encountered

 - Calclating number of outcomes involved complex function - COUNTIF
 - Creating pivot tables and chart for outcomes based on launch date was tricky due to the additional conversion

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

 - More launches during spring and summer time will lead to more successful outcomes
 - ~37% failures were identified based on launch dates

**- What can you conclude about the Outcomes based on Goals?**

 - When goal amount is <1000 there is a very high chance of success with the outcomes
 - When goal is optimal then there is equal chance of failure and success.

**- What are some limitations of this dataset?**

 - $ Value is not consistent due to currency, as a result ist hard to predict the outcomes
 - Outcome information is very limited as it doesnt tell on what criteria it was classified as successful/failed

**- What are some other possible tables and/or graphs that we could create?**
 - outcomes based on parent category
 - outcomes based on country
 - outcomes based on pledged amount
 - country vs goal
 - country vs parent category
 - country vs pledged amount
