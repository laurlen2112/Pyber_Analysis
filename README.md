# Module 5: PyBer Analysis

## *Overview and Purpose of analysis*:
The purpose of this project is to create a summary data frame organizing ride-share data by city type and to create a multiline plot showing weekly fares per city type.

## *Results*:
[The PyBer summary data frame](https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/PyBer_DF_Summary.png):

 The urban city type category holds the largest accumulated ride total, the largest number of drivers, and the largest total fares.  Despite those 
  metrics, the urban city type posts the lowest average fare per ride at $24.53 and the lowest average fare for per driver at $16.57.  

 By contrast, the rural city type posts the lowest ride totals, lowest number of drivers, and lowest fare totals; however, its average fare per ride and 
  average fare per driver rank the highest of the three categories.  

 While suburban category falls in between the urban and rural types, it is noteworthy that its average fare per driver, $39.50.  This metric is more than double the amount of 
  the urban type and about $16.00 lower than the rural type in the same category.  Likewise, the suburban type's average fare per ride is about $6.00 higher than the urban type's average fare and about 
		$4.00 lower than the rural type's average fare per ride.
 
[The Pyber line plot](https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/PyBer_Plot.png):

 The information on the Pyber plot correlates with the above, showing the urban category with the highest fares followed by the suburban type and rural.  Additionally, the peaks and valleys of the lines enables one to glean increases and decreases of rides per city type over a period of time.  Interestingly, all 3 city types appear to have a sharp increase in rides toward the end of February and a similar decrease at the beginning of March.  

 Unfortunately, this increase and decrease cannot be explained by [this data](https://github.com/laurlen2112/Pyber_Analysis/blob/main/analysis/pyber%20analysis%20DF%20in%20code.png) because the data frame this analysis is based on only looks at: city, date, fare, ride ID, driver count, and city type.

## *Summary*:

Based on this analysis, it is recommended that PyBer invest resources to grow the suburban type market share because its average fare per ride is more lucrative than the urban city type and its population density will likely provide more customers than the rural category.  

Although the urban category's total rides are about double that of the suburban type, the average fare per ride is about $5 lower than the average suburban ride fare. Similarly, while the rural type has a higher average fare per ride, its potential for additional customers may be low since rural areas tend to have less population density. Therefore, based on this data, focusing resources on the suburban city type has the greatest potential for a return on investment.

Finally, as discussed above, the underlying data is not sufficient to account for some of the sharp peaks and valleys visualized in the graph.  Therefore, it is recommended to rerun the analysis with an expanded data set to include factors that may account for the peaks and valleys such as advertising, promotions, and circumstances which may increase ride share use like holidays. 
