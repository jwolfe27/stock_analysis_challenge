# Stock Analysis Challenge
---
## Overview of Project
The objective was to analyze green stock performance data from 2017 and 2018 for Steve and his parents. The below summary report details my analysis, which includes screenshots of run times using the original code, and run times utilizing the refactored code.  The original workbook from the module only analyzed one stock ticker "DQ".  My completed analysis expands to include all green stock (12 total) performances over the two year period, 2017 - 2018.

### Purpose
To provide Steve's parents accurate stock performance analysis on 12 provided stocks for the years 2017, and 2018 to help them make educated and/or informed investment decisions

## Results - Original Code vs Refactored Code Run Times
### 2017 Original Code Run Time
![2017 Original Code](https://user-images.githubusercontent.com/89044350/131709059-6f4ee347-1e62-415b-91e2-52f0a79bad8d.PNG)

### 2017 Refactored Code Run Time
![2017 Refactored Code](https://user-images.githubusercontent.com/89044350/131709084-d6d93d3d-87e3-45cc-83ec-e2d44334fa14.PNG)

### 2018 Original Code Run Time
![2018 Original Code](https://user-images.githubusercontent.com/89044350/131709124-c808e5e1-d037-414a-bbec-ec0336fdc38f.PNG)

### 2018 Refactored Code Run Time
![2018 Refactored Code](https://user-images.githubusercontent.com/89044350/131709150-0ca955c2-98a8-49c8-8a4d-4305e25ce864.PNG)

## Comparison of Run Times
The above shows that Refactored Code runs much quicker than the Original Code consisting of a "Nested For" loop to calculate the data. 
Image below of Nest For loop used in Original VBA Code:

![NestedForLoop](https://user-images.githubusercontent.com/89044350/131711307-e54e343d-66eb-48b8-9077-f980ec52ac82.PNG)


## Overall Stock Performace 2017 - 2018
![2017 Stock Performace](https://user-images.githubusercontent.com/89044350/131676383-e5b804fd-bab0-4b95-ae55-36b5eded0c5f.PNG)

- As displayed above, for the year 2017 the 12 stocks requested to be analyzed performed well.  Only one stock, "Terp", showed negative return at -7.2% respectively. Steve's parents are using Daily Volume to represent a stocks success.  These results show Terp to fall in the middle of the pack in regards to Daily Volume in comparion, yet are the only stock showing a negative return for the year.

![2018 Stock Performance](https://user-images.githubusercontent.com/89044350/131680062-725a25c0-4e66-404a-b4b9-9abf1d4cb610.PNG)

- As displayed above, 2018 experienced very different returns than what we saw the year prior.  All but two stocks (ENPH, RUN) showed negative returns for the year. The two successful stocks in 2018 both landed in the Top 3 for Total Daily Volume, showing that analyzing Total Daily Volume can paint a picture of a stocks success overtime. 

## Pros/Cons to Refactoring Code

### Pros:
- Refactoring code allows a writer to clean up, reorganize and identify any potential duplications or unnecessary steps within a code.  This provides a cleaner, more easily understandable piece of code for others to view and/or use   
- You can easily apply your existing code solution to a new project once the code is updated for the new dataset.  This could consist of simply updating sheet names within the code, or number/name of ticker rows to be analyzed. The more organzized your refactored code is, utilizing whitespace to comment on each step taken, the easier this would be for any end user to update the code to analyze additional data
- Refactoring code could also allow you to debug or troubleshoot existing code to find the root source of an error

### Cons:
- Refactoring code could potentially be very time consuming, which if on a budget could cost a considerable amount of time and wages. 
- Refactoring code could also result in "breaking" already working code if the writer is not careful.

## Pros/Cons to Original VBA Script:
### Pros:
- The original VBA script was relatively easy to follow, as long as descriptive comments were used
- It is a good foundation to ultimately achieve the same results as the refactored code, although the it requires more memory to run

### Cons:
- Original code consisted of a Nested FOR loop to calculate results, resulting in writing more code than necessary, which also resulted in longer run times.  If working with a larger dataset, this could become an issue


## Summary
It would be my personal recommendation to Steve and his parents to dig deeper into both ENPH and RUN stocks as lucrative investment opportunities.  ENPH and RUN both experienced positive returns in 2017 and 2018, respectively.  It would be to their benefit to run the same analysis for 2019 and 2020 to make an even more informed financial decision. 





















