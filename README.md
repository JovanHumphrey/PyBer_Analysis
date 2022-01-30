#PyBer with Matplotlib#
 
#Overview#
 
PyBer is a ridesharing app company. They hired me to create a variety of charts to tell the story of the company. The purpose of these charts is to help PyBer improve access and affordability in underserved neighborhoods.
 
The charts I initially created are for reporting between January and April of 2019 and show:
•	The relationship between the type of city, (rural, suburban, and urban) and the number of drivers and fares (Fig 1)
•	The percent of total fares by type of city (Fig 2)
•	The percentage of drivers by type of city (Fig 3)
•	The percentage of rides by type of city (Fig 4)
 
Once this project was done, I was given a new assignment:
1.	Create a summary DataFrame of the ride-sharing data by city type. (PyBer_Challenge.ipynb)
2.	Create a multi-line graph that shows the total weekly fare for each city type. (Fig 5)
3.	Summarize how the information differs by city type and advise PyBer decision-makers on how to use that information.
 
#Results#
 
Fig 1-4 easily show correlation between the city type, number of drivers, and total fares. Unsurprisingly, urban cities have more of everything, while rural locations have less. Fig 5 shows what the difference looks like in dollars. As we can see for the period between January and April of 2019 there were no times when the fares across city types overlapped. At their peak rural fares hit only $500 in early April, while urban cities never dipped below $1500. Taken as a whole, urban cities earned 3-5 times more fare dollars than rural areas.
 
It is worth mentioning that the data provided does not give definitions of city types so there is no way to tell if the types were determined by geography, population, or other factors. Therefore, it is not possible to determine if any of these areas are underserved. Though rural cities have the fewest number of drivers and the lowest fare totals, PyBer may be performing at peak efficiency in those cities.
 
#Summary#
 
Below are three recommendations I would like to make to the CEO of PyBer:
 
1.	If PyBer wishes to improve fares and ridership in underserved areas I would first recommend that they take into consideration the population sizes of cities. Then they can determine the ratio of drivers per capita. Similarly, I would suggest they gather geographical data to determine the square milage of service areas. Then they can determine the ratio of drivers to service areas.

2.	I would recommend that PyBer look at cities of similar size and density and compare ratios. For example, if Port David and West Angela each have about 100,000 people and span an area of approximately 50 miles then they should have roughly the same number of drivers. However, if West Angela has 1 driver per 1,400 people for every .75 miles while Port David has 1 driver per 14,000 people for every 7 miles then we can assess that Port David is comparatively underserved.

3.	More research should be done to measure additional factors such as income levels, availability of public transportation, distance traveled for work, and access to commercial and recreational opportunities to determine need and affordability of ride sharing. Since urban areas tend to sprawl and have vastly different cultures between boroughs it may be worth breaking urban city types into neighborhood subtypes. With that information they can better determine the needs of diverse areas.
