# Module 5: PyBer Analysis

## *Overview and Purpose of Analysis*:
The purpose of this project is to create a summary data frame organizing ride-share data by city type and to create a multiline plot showing weekly fares per city type.

## *Results*:
[PyBer summary data frame](https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/PyBer_DF_Summary.png):

<img src= "https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/PyBer_DF_Summary.png" width="700" height="300"/>


 The urban city type holds the largest accumulated ride total, the largest number of drivers, and the largest total fares.  Despite those 
  metrics, the urban type posts the lowest average fare per ride at $24.53 and the lowest average fare for per driver at $16.57.  

 By contrast, the rural city type posts the lowest ride totals, lowest number of drivers, and lowest fare totals; however, its average fare per ride and 
  average fare per driver rank the highest of the three city types.  

 While suburban category falls in between the urban and rural types, it is noteworthy that its average fare per driver is $39.50.  This metric is more than double the amount of 
  the urban type and about $16.00 lower than the rural type in the same category.  Likewise, the suburban type's average fare per ride is about $6.00 higher than the urban type's average fare and about 
		$4.00 lower than the rural type's average fare per ride.
 
[Pyber Line Plot](https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/pyber%20line%20plot%202.png):

<img src= "https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/pyber%20line%20plot%202.png" width="700" height="300"/>

 The information on the Pyber plot correlates with the above.  It shows the urban category with the highest fares, followed by the suburban type in the middle and the rural category posting the lowest fares.  In addition to the above, the peaks and valleys of the lines allows one to easily glean increases and decreases of fares per city type over a period of time.  For example, all three city types appear to have a sharp increase toward the end of February and a similar decrease at the beginning of March.  

 Unfortunately, these peaks and valleys cannot be adequately explained by this data because [the data frame](https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/pyber%20analysis%20DF%20in%20code.png)  this analysis is based on only looks at: city, date, fare, ride ID, driver count, and city type.  Those data points do not sufficiently explain the reason behind this pattern.

## *Summary*:

Based on this analysis, it is recommended that PyBer invest resources to grow the suburban category market because its average fare per ride is more lucrative than the urban city type and its population density will likely provide more customers than the rural category. While the urban category has double the total rides of the suburban category, its average fare per ride is lower by approximately $5. Similarly, the rural category has a higher average fare per ride, but its potential for additional customers may be limited due to lower population density.

However, to confirm that the differences in average fare per ride among city types are due to population density and distance between pick-up and drop-off points, it is recommended that PyBer track ride distance and population density. This will enable a more sound investment strategy based on accurate data.

Furthermore, as discussed earlier, the sharp peaks and valleys in the graph cannot be fully explained by the current data. Therefore, it is recommended that PyBer rerun the analysis with an expanded data set to include factors such as advertising, promotions, and events that may increase ride-share use like holidays. This will provide a more comprehensive understanding of the market trends and enable PyBer to make better-informed decisions
