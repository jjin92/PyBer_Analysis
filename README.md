# PyBer_Analysis
Module 5 
## Challenge
### The first paragraph should include the following:

- The purpose of this challenge is to produce a data table summarizing key factors based on 3 city types. A multi line chart is built to showcase the relationship between fares and timespan. 
- The tools used were jupyter notebook, pandas, matplotlib, etc. Most data processing were on dataframe. Most visualization were through matplotlib. 
- summary DataFrame:
- ![Deliverable_1](https://github.com/jjin92/PyBer_Analysis/blob/master/analysis/Deliverable_1.png)
- multiple-line graph:
- ![Deliverable_2](https://github.com/jjin92/PyBer_Analysis/blob/master/analysis/Deliverable_2.png)
- From the images above, we can conclude that:
    - Urban cities have 10 times more rides and 30 times more drivers than rural areas. Even with 10 times more total fares, urban cities have cheaper rides and much less fare per driver. 
    - Total fare in urban cities is about twice more than the suburban total fares, and 5 times more than the rural total fares.
    

### The second paragraph should include the following:
- The copy() function and rename column function took me sometime to debug. I missed the inplace=True in rename() function
- The groupby() on two columns also took me some time
- I also spent some time trying to add the y axis label using the object-oriented method. I could distinguish this method from MATLAB method, but the df.plot() function confused me a bit. 
- Other difficulties were easily solved by checking the documentations

### The third paragraph should include the following:
- Only in urban cities, the total drivers are more than the total rides. That means, on average, one-thirds of the drivers may not get any rides. We should decrease the number of drivers in the urban cities.
- We could also include the distance per ride in the analysis. In combination with the fare, we could infer the price per miles
- We could also include the population of each cities, and compare the number with the total drivers in the city to see if there is any shortage or surplus of drivers.
