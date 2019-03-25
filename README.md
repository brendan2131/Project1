# Data Bootcamp Milestone Project
In this project, my group and I set out to complete a project showcasing our skills in Python programming, calling and utilizing APIs, creating and merging dataframes using Pandas, and creating visualizations using Matplotlib and the Pandas library.  Additionally, we performed statistical analyses using scatterplots and Pearson coefficient tests to determine whether our results were statistically significant, and whether they supported or rejected our hypothesis/null hypothesis.  

# St. Louis Food Desert Data Conclusions
Our team set out to investigate whether there existed any correlation between low numbers of grocery establishments and median income and obesity rates in St. Louis City.  Using data colelcted from Google Places API, the US Census API, and a CSV containing obesity rate data gleaned from a study conducted by St. Louis City, we sought to find out if our suspicions concerning food access, obesity, and income could be illustrated with any statistical significance based on the data we pursued.  Our hypotheses were as follows:

-There is a correlation between food deserts and households with low median income

-There is a correlation between low income areas and low numbers of grocery stores

-We expect to find a correlation between food deserts and obesity rates in examined areas 

# Food Deserts and Households with Low Median Income
As illustrated by a heatmap created from US Census Data pertaining to median income and number of grocery stores per STL zip code, grocery stores seem to cluster around the borders of high income zip codes.  However, as illustrated by our bar graph, the maximum number of grocery stores per zip code was 5, while some zip codes had none at all.  The limited size of our data set makes it difficult to glean statistically significant conclusions concerning the relationship between household income and food access.

# Food Deserts and Obesity Rates
Heatmaps suggest that areas with more grocery stores experience lower obesity rates.  This suggestion is supported by calculating the Pearson Coefficient for obesity rate and grocery stores, which returned a value of -.24, indicating that the less obese a zip code is, the more grocery stores are in it.  However, the statistical significance of this coefficient is compromised by the small size of our data set.

# Low Income Areas and Low Numbers of Grocery Stores
Heatmaps do not conclusively suggest a correlation between high income and higher numbers of grocery stores, nor does our scatter plot.  Once again, the small size of our data set concerning zip codes and number of grocery stores compromises our ability to glean statistically significant conslusions.

# Data Shortcomings, and Suggestions for Further Study

-If we were to conduct our research again, we would likely want to collect data from a variety of metro areas, large and small, so that we may survey a larger geographic area with a higher density of food access establishments.  

-When calling Google Places' API, we found that grocery stores and supermarkets are categorized differently.  Moreover, we noticed that many small, family owned grocery establishments and international stores were not included in Google's summary of grocery stores.  Additionally, considering alternative sources of fresh, healthy produce such as farmers' markets, urban farms, food banks, and other avenues of food access would increase the size of our data set and provide a more elaborate picture of relationships between location, income level, and food access.

-Racial demographics and income levels are essential to the study of inequality and access.  This being said, the US census groups racial demographic data in a manner that makes interpreting it a complex matter.  For example, if one identifies as hispanic, that identifier is situated under an umbrella category of white racial identity.  Similarly, someone who identifies as a pacific islander may be grouped under the umbrella category of asian racial identity.  Bearing all of this in mind, the challenges, economically and institutionally, faced by particular racial demographics may be very difficult to quantify given the nature of the census' nested racial categories.

-Public health data is generally lacking, difficult to access, and inconsistent.  We applied data on obesity rates per zip code in St. Louis city from a study conducted in 2010.  However, upon reading the study's research methods, data concerning weight was gleaned from participants' driver's lisences, meaning that weight and height were self-reported, and thus likely inaccurate, and also that information concerning physical condition, and a participant's address, could be several years old, making this data set potentially very unreliable.
