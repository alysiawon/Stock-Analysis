# stock-analysis

## Overview of Project

### Purpose
The purpose of this analysis is to compare the total daily volume and yearly return for various green energy stocks. This analysis will provide insight on how the various green energy stocks compared to each other, and specifically DAQO New Energy Corp (DQ) in 2017 and 2018.

## Analysis and Challenges

The data preparation includes refactoring the original VBA script by reorganizing arrays, for loops, and if-then statements. This helped to convert the data into a more efficient format and run faster. Insight are generated on the <a href="VBA_Challenge.xlsm">VBA Analysis spreadsheet</a>.

### Results

## Analysis and Results of 2017 Stocks

**Analysis**

1. On average, the total daily volume of stocks traded is 263,886,592, with the highest being SPWR and the lowest being DQ.

2. Overall, 2017 was a positive year. All stocks but TERP had a positive return. The average return rate for all stocks are 67.3%

**Results**

DQ performed the best in this dataset. They had the highest return with 199.4% but the least total daily volume. 

<img src="Resources/VBA_Challenge_2017.png" width="500">

## Analysis and Results of 2018 Stocks

**Analysis**

1. On average, the total daily volume of stocks traded is 275,503,183, with the highest being ENPH and the lowest being AY. 

2. 2018 produced mostly negative results, with only ENPH and RUN stocks producing a positive return. The average return rate for all stocks are -8.5%

**Results**

DQ performed the worst in this dataset. They had the least return and the total daily volume is less than average. 

<img src="Resources/VBA_Challenge_2018.png" width="500">

**Performance of Refactored Code**

After refactoring the code, 

<img src="Resources/Original_Timestamp.png" width="500">
<img src="Resources/Refactored_Timestamp.png" width="500">


**What are some limitations of this dataset?**

This dataset does not specify how the data was collected. As a result, the data collected from different sources can vary in quality and format. 

The dataset can also have bias, including under-represented populations, misinterpretation of the data, and cognitive bias just to name a few. 

**What are some other possible tables and/or graphs that we could create?**

With this dataset, here are 2 examples of tables and/or graphs that we could create: 

1. *Average time frame of campaigns based on outcomes*

	Do certain time frames (longer or shorter kickstarters) lead to more success or failure? With this table and graph, we could see if there is a correlation of how long a campaign was live and its correlation to its success rate. 

	We could filter it even more to see if this differs based on locations, parent categories or sub-categories. 

2. *Average donations of campaigns based on location and/or parent category*

	Do locations and/or parent categories impact the average donation amount? With this table or graph, we could determine if certain locations or parent categories have a higher or lower average donation amount.

	We could also determine if an average donation amount per location or parent category is correlated to a certain outcome. 
