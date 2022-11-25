# Analysis-of-A-B-test-results
Practical Statistics with Python.

SUMMARY

With p-values of ab-page= 0.19, p-value of US=0.457 and p-value of CA=0.074, it can be shown that both the page and the country are not statistically significant but are 
practically significant. The ab_page p-value suggests that its unlikely our statistic is from alternatives hence we fail to reject null which means it tends towards null 
that comes to the conclusion that the old_page should be retained. This is also applicable to the p-values of US and CA respectively using UK as a baseline, their 
p-values also suggests to stick to null.
For the second regression model, the p-values are as follows ab_page=0.6349, US=0.7598, CA=0.7674, ab_US=0.2377, ab_CA= 0.1681. These p-values are all greater than 0.01 
which concludes that it fails to reject null and reject alternative hypothessis, hence, the old page should be retained.
However, in comparison with type I error rate of 0.05, the three p-values for the page and countries falls in the category > or = alpha , which concludes to reject the 
alternative and stick to null i.e fail to reject null.
The effect of page and country to predict conversion is not statistically significant but practically significant.
Indeed, we do not find the new page providing us any significant benefit regarding new user conversions. The old page should be good for now. We can always make another
experiment in the future if the circumstances change.
