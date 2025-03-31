# The story
Crime data from 2003 to 2025 in San Francisco has been made publicly available. On this website vehicle theft will be analyzed.

When we look at the nr of occurrence of vehicle theft in San Francisco from 2003 to 2025 it is clear that the incidents of stolen vehicles have been reduced. 

![Vehicle Theft by Year graph](assets/images/VTbYg.png)

**Key Events Related to Vehicle Theft Reduction:**  
The graph is showing the different recorded initiatives of San Francisco to reduce the number of vehicle thefts.
**(A)** Car manufacturers updated car keys to include microchips making it almost impossible to [bypass a car](https://www.nytimes.com/2014/08/12/upshot/heres-why-stealing-cars-went-out-of-fashion.html).

**(B)** The National Insurance Crime Bureau (NICB) and LoJack Corporation launched a nationwide educational campaign to raise awareness about vehicle theft prevention, encouraging owners to take [protective measures](https://en.wikipedia.org/wiki/Vehicle_Theft_Protection_Program?utm_source).

**(C)** Police Chief Bill Scott reassigned 69 officers to neighborhood foot patrols, nearly doubling the number in high-crime areas. This contributed to a significant drop in larceny thefts, including [vehicle break-ins](https://www.sfchronicle.com/crime/article/San-Francisco-auto-break-ins-UC-study-finds-13443374.php?utm_source).

**(D)** The San Francisco Police Department (SFPD) expanded its use of technology, including drones, automated license plate readers (ALPRs), bait cars, and plainclothes operations, leading to a sharp decrease in auto break-ins in [2024](https://www.sf.gov/news--san-francisco-police-using-new-technology-target-auto-break-ins-making-arrests-hotspot-areas).
 

This fact could be due to technological advancement that was implemented by car manufacturers in the 1990s which made it essentially impossible to start a car without the ignition key [Barro, Josh. 2014. Here's why Stealing Cars Went Out of Fashion. The New York Times](https://www.nytimes.com/2014/08/12/upshot/heres-why-stealing-cars-went-out-of-fashion.html). The ignition key was redesigned with a microchip that is uniquely programmed by the dealer to match the car. Judging by the drop in vehicle theft criminals don't seem to have been able to counterfeit the keys – or it is not profitable.
However, one would assume that only new car keys have microchips and therefore that the number of vehicle theft would gradually decrease as cars get replaced with newer models. Yet in San Francisco, the reduction of vehicle theft seems to happen in the same year. In 2006 vehicle theft decreased in San Francisco by 60%.
Now, according to this low-quality source [San Francisco Metro Area Population 1950-2025. Macrotrends.net](https://www.macrotrends.net/global-metrics/cities/23130/san-francisco/population) the population in SF was 3,246,000 in 2003 and 3,363,000 in 2025, indicating that it is not probable that nr of cars decreased in the area during the same time.

Another observation is that vehicle theft does not decrease down to zero that might indicate that there are some cars that are either a. not locked properly or b. worth the effort for organized vehicle theft. Given that in scenario a the perpetrators are equally spread around the city (an unlocked vehicle is not more likely to be stolen by organized crime than pedestrians), one would assume that improper locking of cars are not prone to an unequal spread of vehicle thefts throughout the city of SF, but the second reason could.

<embed type="text/html" src="assets/InteractiveGraphs/folium_map.html" width="800" height="500">
[folium_map.html](assets/InteractiveGraphs/folium_map.html)

The graph shows the distribution and evolution of vehicle theft in San Francisco from 2003 to 2025.
The different districts are colored based on whether the average vehicle theft is higher or lower than the average vehicle theft in the city.

Blue and green colors indicate that vehicle theft is less than the average in the city and it can be observer that the North and North Vest of the city enjoys less stolen cars than average. The yellow, orange and red colors, the South and South East, on the otherhand are being pestered with vehicle theft. Now, since the analysts of this data are not familiar with the affluence of the different districts it is unclear whether the cars are better in those areas or if they are picked for convenience (less cameras or perhaps because the perpretators are heading south?).

However, it is interesting to get more granular data on the behaviour taking place. There doesn't seem to be any season, month or day of the week that is most likely to contribute to the nr of incidents. However, the reports of stolen cars are more likely to occur during the later hours of the day and decreasing before and around midnight. Therefore incidents are investigated from an hourly basis.

<iframe src="assets/InteractiveGraphs/BokehPlot.html" width="1200" height="800"></iframe>
[BokehPlot.html](assets/InteractiveGraphs/BokehPlot.html)

From the interactive graph above, it's clear that thefts are least common between 1 AM and 6 AM, when most people are asleep. The number of incidents rises in the afternoon, with a peak around 8 PM and remains high until dropping after midnight. This does not reveal a surprising pattern, as most crimes are done in the dark of night, instead of broad daylight. It could indicate that thieves strike after the car have been parked at the end of the day.


## Is there some way of forecasting vehicle theft?
Unless there is some good corrolation is found between a variable and vehicle theft, it is not plausible to think a forecast is viable. Since no corrolations were found (sometimes due to lack of quality data) on the usual variables associated with increased crime (nr of vehicles, population, economic inequality, income, drug addiction etc).