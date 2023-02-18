# Finding-the-Best-Markets-to-Advertise-In
Data taken from https://github.com/freeCodeCamp/2017-new-coder-survey

This dataset describes the results of a survey. It has 136 columns and 18175 rows.
We are using ready-made set as we don't have access to providing a survey.
The questions' answers vary from Yes/No to time questions (months working in a field) to money amounts

1. Cleaning data:
- Removing NaN data

2.Preparing for exploration:
- splitting the different itrests ("Full-Stack Web Developer,   Front-End Web Developer") into 2 separate values
- Counting the number of times each of the possible interests occurs and what percentage they make up.
  eg.  1     31.650458%
       2     10.883867%
       3     15.889588%
  This indicates that most people are interested in 1 thing (eg. Web dev) and 10% are interested in 2 things, etc.
  
Counting the number of people interested in web dev:
  True     86.241419%
  False    13.758581%
  ![image](https://user-images.githubusercontent.com/85899536/219864281-08d083f0-3e8b-4d6a-97d0-c4c4442a816d.png)

2.1 Narrowing down the investigation of months spent, money spent:
- Count the number of months a user spent programming
- Count the amount of money user spent on training/learning 

2.2
- The amount spent has some outliers:
-- Clean outliers
- Get rid of results where monthsspent < 3 & moneyspend >20000 & no bootcamp attended as this refers to uni which we don't count.

Conclusion:
Our advertisement should be split between USA (70% of those asked), with India (15%) coming close second. Potentially, Canada can also be an option
