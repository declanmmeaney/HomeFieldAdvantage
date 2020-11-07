# HomeFieldAdvantage

The code in this respository was written to analyse results from past Premier League seasons to determine the extent to which teams benefit from home field advantage (if at all). 

The data is from the 2013 through 2019 seasons and was taken from data.world, a cloud-native data catalog available to the public.

Prior to my analysis using python, I converted the csv files to xlsx and cleaned the data in Excel.

My analysis focuses specifically on goals scored at home vs goals scored away. This analysis defines home field advantage by goals scored, not by other variables, such as wins or goal differential. I intend to analyse both of those variables in the near future and will update the repository once that work is complete. 

Across the six seasons from which I analysed data, there were 6207 total goals scored, of which 3510 were scored by the home team and 2697 by the away team. The 95% confidence interval for the difference of two population proportions, home goals and away goals, respectively, was (0.106, 0.156). Given the interval does not contain the null value, I conclude that home field advantage does exist and the difference in number of goals socred home vs away is statiscally significant.
