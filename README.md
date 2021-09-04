# Stock Analysis


## Overview
The background of this analysis is that we are helping a friend analyze the stock market since his parents would like to invest in renewable energy, but they want to choose the most lucrative stock to invest in. The purpose of this analysis is to anaylze and display stock market trends over the past few years in order to help the recipient make an informed decision regarding which stock to invest in. We are analyzing the total daily volume as well as the yearly return for each stock from 2017 to 2018. The previous VBA code utilized in the module was refactored to analyze the dataset more efficiently and quickly without using too much computational power.


## Results
### 2017 Stock Analysis
For all of the stocks in 2017, the return was a positive percentage, except for TERP, which had a return of -7.2%. The highest stock for 2017 was DQ, which had a 199.4% return. When running the code using the original code, the time it took it analyze the dataset for both years was around 0.48 seconds. Once I ran the refactored code, it took around 0.21 seconds for 2017 and 2018.

<img width="372" alt="stock-analysis 2017" src="https://user-images.githubusercontent.com/88624677/132096889-a21f0c36-3b5f-4fe4-90c9-e82b3c32c87c.png">
<img width="331" alt="Screen Shot 2021-09-04 at 10 04 52 AM" src="https://user-images.githubusercontent.com/88624677/132097546-5d1f8976-8c03-4885-b16d-d891ff6c8a20.png">

### 2018 Stock Analysis
For all of the stocks in 2018, the return was negative, except for ENPH and RUN, which both had around a return of 80%. Similarly to the 2017 stock analysis, the original code took around 0.48 seconds to run the stock analysis. As for the refactored code, the code took 0.21 seconds to analyze our stock dataset. 

<img width="372" alt="stock-analysis 2018" src="https://user-images.githubusercontent.com/88624677/132097088-8f3b091c-8de5-43fb-89ec-4f1483d7b6ba.png">
<img width="331" alt="Screen Shot 2021-09-04 at 10 05 21 AM" src="https://user-images.githubusercontent.com/88624677/132097570-a43e6b25-94a8-444d-b3ef-a6f01d73b07f.png">

### Data Structures
We used arrays as the main data structure to increase code efficiency without sacrificing time or computational power. Using these along with loops allowed analysis to compute more efficently.
<img width="766" alt="Screen Shot 2021-09-04 at 10 26 00 AM" src="https://user-images.githubusercontent.com/88624677/132097936-5735245a-5f28-4e7f-98af-1a06f61f6738.png">


## Summary
There are many advantages of refactoring code. Refactoring allows you to use less memory and computational power, increase the speed and efficiency of your code, while improving the logic of the original code. On the other hand, refactoring code can be time-consuming and difficult since you need to improve the logic and come up with unique solutions to improve the code. These pros and cons definitely apply to refactoring the original script due to the fact that there will always be a better solution to a coding problem and the first attempt at solving a problem may not be the best way to solve it. For example, while refactoring the code, I was having trouble with the arrays and the TickerIndex, and it took me a while to look at the problem from another perspective that included the arrays and loops. One important thing I was constantly forgetting was to include the index when using the arrays. On the other hand, I would say the original code was a lot more simpler and used less logic than the refactored code.
