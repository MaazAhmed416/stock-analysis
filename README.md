# Stock-analysis

## Overview of the analysis
The purpose of this anaysis was to analyze returns on stocks for two different years using VBA. Initially, for a few tickers we found the total volume traded and the amount of return(investment or loss) the ticker(stock) made during the year. For this analysis, our objective was to refactor the code so it can be used for multiple years and also hold more tickers if necessary.

## Results of the analysis
![image](https://user-images.githubusercontent.com/76402559/118720796-0e9ee980-b7f8-11eb-87bd-b8085aabe74a.png)

For the year of 2017, all the tickers(stocks) had great returns except 1 stock which made a loss. The ticker DQ had close to a 200% return which is incredibly high.

![image](https://user-images.githubusercontent.com/76402559/118720908-2d9d7b80-b7f8-11eb-9e22-a101fd66d153.png)

For the year of 2018, most of the tickers made a loss except 2. Also, the total volume of the stocks that were traded had also decreased for most of the tickers. It's not quite clear why this happened. The losses incurred were mostly lower percentage numbers compared to the gain percentage numbers in 2017.  

## Summary of the analysis

### Refactoring the code
Refactoring the code helped the process become more efficient and quicker. One key additional thing we added was the three output arrays(tickerIndex and tickerVolumes) as arrays. The extra array helped us loop through the rows, increase the ticker volume and add the total volume of the ticker. After this process, we were able to create our if-statements to select the ticker we want and get the total volume and return for it.

### Original code
In the original code, we had the starting and ending price and we looped through all the values. We only had one loop for this code.

### Refactored code
For the refactored code, we had a inner and outer loop. Moreover, the running time of the code was shortened. This is a positive result of the refactored code which tells us it will run well even for more tickers.
