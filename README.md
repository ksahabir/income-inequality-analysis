# income-inequality-analysis

# **Abstract**


Income inequality is an issue that affects every facet of a country’s population. A picture of the inequality in a country’s income level can help us understand the workings of a country’s society and the challenges they face in areas of commerce, trade, governance, social issues, etc. We aimed to look at the distribution of wealth in the US, with data obtained from the US Census Bureau, and how it has changed over time by comparing the Gini coefficient for each set of data. The Gini coefficient is a measure of statistical spread that, in our case, measures the inequality in a set of data. Thus, our aim is to observe how income inequality in the US has evolved over time.



# **Introduction**
 
 
The inequality of income in a country is an important tool to understand the health of that country’s economy as well as its population. High levels of 
income inequality are signals of reduced consumer demand, as higher income households tend to hold onto their income more than lower income households. 
Additionally, rising levels of income inequality have been linked to the rise of populist, authoritarian, and nativist movements and governments worldwide. 
We wanted to do a deeper dive into the evolution of income equality in the US graphically by graphing the Lorenz curve of each set of data obtained from 
the US Census Bureau. This would be done by graphing income per quintile of the US population, as the US Census gives us data based on quintiles of the US 
population. Additionally we wanted to express this inequality numerically by calculating the Gini coefficient for each year that we had access to data for. 
This coefficient is a measure of the spread of data in a dataset, measuring the level of inequality in the data. Our expectation is that income inequality 
increases over time. This research will allow us to contextually understand phenomena such as the rise of populist movements combined with rising levels of 
political discontent, as well as economic metrics such as GDP, unemployment, etc. 



# **Description of data**

	
The Lorenz curve is obtained by plotting each point where the quintiles are on the x axis and the mean incomes are on the y axis. The Gini coefficient is 
then calculated in two ways: either by approximating the area between the line of equality, a line with a slope of 1 which represents perfect equality, and 
the Lorenz curve or by calculating the relative mean absolute difference of the data and halving it.
 
 

In our dataset, we have two attributes:
 
Label - Categorical, specified distribution of the population. Possible values: Lowest Quintile, Second Quintile, Third Quintile, Fourth Quintile, Fifth 
Quintile, Highest Quintile
Means - Numerical, Annual mean salary of the quintile 



# **Mathematical/Problem Formulation**


We will be comparing the distribution of wealth against a hypothetical uniform distribution of wealth by  graphing the mean income per quintile in the US 
for the years 2010 to 2021 compared to a line with a slope of 1 (the line of equality). Each quintile represents discrete groups of 20% of the US 
population. We will also be calculating a measure of equality in the same dataset,  by calculating the Gini coefficient, which is a general measure of 
equality in the frequency distribution of a dataset. The formula we use is found in 
https://www.statsdirect.com/help/default.htm#nonparametric_methods/gini.htm
as the second equation on the page.



# **Discussion**
 
	
Based on the table of Gini coefficients, as well as the graphs of the Lorenz curve from 2010 to 2021, we see that there is widespread inequality amongst 
the population of the US. Additionally, we observe the level of inequality rising steadily with each passing year with no change in the trend even during 
the COVID lockdowns of 2020. This supports our original belief that income inequality, for the US population as a whole, has increased over time. Our 
results, where we observe Gini coefficients rising from .494 to .507,  are, according to the UN, indicative of a severe amount of income inequality. This 
level of income inequality especially harms those in the lower income quintiles, and weakens the economy because of reduced demand for goods and services. 
Increasing income inequality only serves to allow the richest parts of the population to consolidate their power and will over the other members of the 
population through wielding their money for political purposes. Therefore, it is highly important for the US government to focus on policies aimed 
specifically towards reducing the level of income inequality in the population.

We observed that our code was fairly efficient and ran very quickly; our code performed all the necessary operations to plot the Lorenz curve and calculate 
Gini’s coefficient within 1 second. This was thanks to a couple of factors, one being that the dataset for each year only consisted of 5 rows (one row for 
each quintile). We did not have to work on constructing each quintile, as these groups were already constructed for us in the dataset, so our code only 
needed to perform plotting and calculations. One choice we made for this study was to calculate the Gini coefficient independently from the Lorenz curve; 
meaning that we calculated the Gini coefficient in the context of relative mean absolute difference rather than the approximated area between the Lorenz 
curve and the line of equality. Initially, we thought to perform numerical integration to approximate the area between the Lorenz curve and line of 
equality. This method would have had us calculate the Gini coefficient by dividing this approximated area A by the total area under the line of equality. 
However, by instead calculating the Gini coefficient in the way we chose for this project, we were sure that the accuracy of our results for the Gini 
coefficient were not affected by approximating the area from the graph.

For the future, a study examining a longer time frame can be done to determine when or if income inequality was in a better state in the US and 
potentially find and understand the correlations between the rise in income inequality and historical events influencing that rise. Additionally, a more in 
depth study with regards to the demographic makeup of these quintiles would help advance this research. This would allow us to better see the levels of 
income inequality along the lines of race, gender, sexual orientation, disability status, and more. Such information could potentially be useful in 
formulating policy to specifically reduce income inequality amongst demographics that display higher levels of income inequality. 



# **Conclusions**


In conclusion, we have found verifiable evidence of an increase in income inequality in the United States. Our conclusion is based on analysis of the 
Lorenz curve and Gini’s coefficient for the mean income of the quintiles of the US population. Both the Lorenz curve and Gini’s coefficient are time tested 
measures of inequality, with historical precedent of what good and bad results are.  We have observed Gini’s coefficient values increasing from .494 in 
2010 to .507 in 2021. This  is a sign of a very high amount of income inequality, which is a bad omen for the future of the US economy as well as the 
financial health of US citizens. The US government needs to take action with a policy specifically aimed at reducing this wealth disparity if it wants to 
avoid a situation where most of the population’s financial health is in jeopardy.



# **References/Bibliography**


https://www.nber.org/papers/w24900#:~:text=In%20response%20to%20rising%20inequality,populist%20promising%20to%20end%20globalization.&text=Countries%20with%20more%20inequality%2C%20higher,model%20and%20in%20the%20data.

https://www.cfr.org/backgrounder/us-inequality-debate#:~:text=Inequality%20is%20a%20drag%20on,can%20also%20hurt%20the%20economy.

https://www.statsdirect.com/help/default.htm#nonparametric_methods/gini.htm

https://data.census.gov/table?q=income+inequality&tid=ACSDT5Y2010.B19081

https://www.unicef.cn/en/figure-27-national-gini-index-20032017








