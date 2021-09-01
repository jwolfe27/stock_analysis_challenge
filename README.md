# Stock Analysis Challenge
---
## Overview of Project
Analyze green stock performance from 2017 and 2018 for Steve and his parents. The below summary report details my analysis, which includes screenshots of run times using the original code, and run times utilizing the refactored code.  The original workbook from the module only analyzed one stock ticker "DQ".  My completed analysis expands to include all green stock (12 total) performances over the two year period, 2017 - 2018.

### Purpose
To provide Steve's parents accurate stock performance analysis on 12 provided stocks for the years 2017, and 2018 to help them make educated and/or informed investment decisions

## Results - Original Code vs Refactored Code Run Times
### 2017 Original Code Run Time
![2017 Original](https://user-images.githubusercontent.com/89044350/131672851-5789204d-5953-43ce-abf2-69f8e9e234e2.PNG)

### 2017 Refactored Code Run Time
![2017 Refactored](https://user-images.githubusercontent.com/89044350/131673215-0918cf4a-fc6e-491e-bec7-9c792c3b9fc3.PNG)

### 2018 Original Code Run Time
![2018 Original](https://user-images.githubusercontent.com/89044350/131674505-8a623306-a05f-4d5d-9d1a-355ba06ac4dd.PNG)

### 2018 Refactored Code Run Time
![2018 Refactored](https://user-images.githubusercontent.com/89044350/131674594-64626df9-46f6-44b9-89f8-6e250ef35ca4.PNG)

## Comparison of Run Times
My results did not show a significant difference in process times between the original code used to analyze the 12 green stocks as compared to using the refactored code to analyze the same dataset.  There are variables that should be taken into account that could affect these results which include: 
- Other programs running in the background utilizing memory at time of analysis
- Overall performance capabilities of the end users PC/Laptop 

## Overall Stock Performace 2017 - 2018
![2017 Stock Performace](https://user-images.githubusercontent.com/89044350/131676383-e5b804fd-bab0-4b95-ae55-36b5eded0c5f.PNG)

- As displayed above, for the year 2017 the 12 stocks requested to be analyzed performed well.  Only one stock, "Terp", showed negative return at -7.2% respectively. Steve's parents are using Daily Volume to represent a stocks success.  These results show Terp to fall in the middle of the pack in regards to Daily Volume in comparion, yet are the only stock showing a negative return for the year.

![2018 Stock Performance](https://user-images.githubusercontent.com/89044350/131680062-725a25c0-4e66-404a-b4b9-9abf1d4cb610.PNG)

- As displayed above, 2018 experienced very different returns than what we saw the year prior.  All but two stocks (ENPH, RUN) showed negative returns for the year. The two successful stocks in 2018 both landed in the Top 3 for Total Daily Volume, showing that analyzing Total Daily Volume can paint a picture of a stocks success overtime. 

## Advantages/Disadvantages to Refactoring Code
### Advantages:
- Refactored code leaves you with a clean, more efficient and well organized set of code to work with.  Correct use of whitespace (comments) explains what is happening step-by-step within the code, helping yourself to remember and others to understand your thought process. Clean, well organized code results in a more efficient program that is easy to understand.  This is beneficial not only to the code writer if he needs to step away from their project, but to others viewing or using the code in the future. 
- You can easily apply your existing code solution to a new project once the code is updated for the new dataset.  This could consist of simply updating sheet names within the code, or number/name of ticker rows to be analyzed. The more organzized your refactored code is, the easier this would be for any end user update the existing code to analyze more data.

### Disadvantages:
- Refactoring code could potentially be very time consuming, which if on a budget could cost a considerable amount of time and money. 
- If not careful, the writer could "break" the original working code, resulting in more time lost locating the root cause of any new errors that occur when debugging.

## Summary
It would be my personal recommendation to Steve and his parents to dig deeper into both ENPH and RUN stocks as lucrative investment opportunities.  ENPH and RUN both experienced positive returns in 2017 and 2018, respectively.  It would be to their benefit to run the same analysis for 2019 and 2020 to make an even more informed financial decision.





















