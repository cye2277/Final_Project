# Final_Project

Airbnb Effect on housing price


Overview：
Airbnb has been launched since 2008. This new and popular short term leasing platform give many house owner a chance to rent their house to tourist in short term. This convenience also lead to other unpredicted situation. Based on recent change in housing market, many researchers started to blame airbnb for contributing to the increasing housing price. 
However, housing price can be influenced by many factors, I will choose the airbnb from different type of cities to see the overall influence(Chicago, Boston, Seattle, San Francisco, etc.). For the time period, I will use the last 5 years airbnb data in those specific cities and explore its possible correlation and causation with those cities’ housing price on Zillow.

Hypothesis:
Airbnb price has strong correlation with rental rates and house prices in at U.S. market.


Data source:
1. Airbnb data source: http://insideairbnb.com/get-the-data.html 
2. Zillow housing related data source https://www.zillow.com/research/data/

Methodology:
Correlation is not the same as causation. However, we can try to prove whether these two trend has correlation. If they do not have correlation, then they must not be the causation relationship.
Here, we will use pandas in python and Jupyter notebook to compare below those 2 type of analysis.
The trend of airbnb price and Zillow rental rate
The ratio of Airbnb short term rate option to Zillow housing price and the ratio of  Zillow long term rental rate to Zillow housing price.


Future work: 

In order to prove the causation of airbnb and long term rental rate and housing price. We will try to control the unobserved factor in the dataset. 

1.Control Zip-code level effect to compare the area that has airbnb housing and the areas that does not have airbnb housing. 
2.Control Arbitrary city level time trends, such as popularity, economic growth rate of specific city, to eliminate other factors that we do not want to involve in.
After eliminate those factors we can see the real effect that airbnb put on the long term rental rate market and housing market.
