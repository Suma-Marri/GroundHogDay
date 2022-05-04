# GroundHogDay
The legend behind Groundhog Day tradition goes likes this:
Thousands gather at Gobbler’s Knob in Punxsutawney, Pennsylvania, on the second day of February to await the spring forecast from a groundhog known as Punxsutawney Phil. According to legend, if Phil sees his shadow the United States is in store for six more weeks of winter weather. But, if Phil doesn’t see his shadow, the country should expect warmer temperatures and the arrival of an early spring.

### Dataset
Archive: https://www.kaggle.com/datasets/groundhogclub/groundhog-day

Weather: https://www.ncdc.noaa.gov/cag/statewide/time-series/36/tavg/1/2/1895-2021?base_prd=true&begbaseyear=1901&endbase

### Analysis

The p-value of .217 with no real relationship between them. This 21.7% chance outweighs the .05 significance level, so the correlation is not statistically significant. On the other hand, with 10 points, we have (almost) a 0% chance that we’re wrong about a correlation between X and Y, and thus it is statistically significant.

![image](https://user-images.githubusercontent.com/58046234/164565551-bc32de7f-8a72-4a71-b110-4df633e5b7b1.png)

OLS regression can tell us the best relationship between a set of predictor variables and a target variable. The predictor was X and the target was Y. For the Groundhog Day analysis, our predictor is Phil’s prediction, and the target is the temperature offset.

The temperature offset for April is plotted against the year. Points are colored by Phil’s prediction for that year — blue when he predicted 6 more weeks of winter, and red when he predicted an early spring. As you can see, many more of the red points are concentrated below 0. This means that if you were trying to bet whether April would be hotter or colder than average, based only on Phil’s prediction, you would be better off betting colder.

![image](https://user-images.githubusercontent.com/58046234/166839800-c67e0960-d819-4528-8efc-623aa3fe1cf3.png)

On the other hand, taking a look at another month, March, we don’t see a clear preference one way or the other. The red points are fairly evenly distributed above and below the line.

![image](https://user-images.githubusercontent.com/58046234/166840171-342ca163-9484-49e7-b39a-f1778d86e02b.png)


### Results
Unfortunately, it doesn’t look like groundhogs are very good at predicting the weather. :frowning_face:	
