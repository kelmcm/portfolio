## Assignment: Visualizing government debt
The goal of this assignment is to visualize global government debt over time. Countries take on different forms of government dept. The general government debt-to-GDP ratio is an indicator used to measure the health of a government's finances. In the below exercise we look at this metric from different lenses.   

### Part 1: Government finance sustainability above average for US and Canada - not a good thing
I've lived large portions of my life in Canada and the United States, so I like to compare these contries a lot when looking at data. Taking a peak at the general government debt-to-GDP ratio for 2019, Canada and the US are above average. For this indicator, a good value is below 60%. 

<iframe src="https://data.oecd.org/chart/6ObY" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6ObY" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

Source: OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 09 September 2022)

### Part 2: Global debt-to-GDP ratio trends upwards over past 3 decades
The below visualization similarly compares the general government debt-to-gdp ratio, howver it now shows the value over time between the years 1995-2021. Each country is shown with an individual sparkline. Sparklines are a nice tool to the trends of many datapoints all at once without overcrowding the visualization because each datapoint has their own mini-chart. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11143867"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Part 3: Japan's debt-to-GDP ratio soaring above comparable countries by GDP
After transforming the data to lookg at all countries' ratio on a single line chart. It was clear how drastic Japan's debt-to-GDP ratio was above all others since the early 2000s. I decided to dig deeper to see which countires could actually be compared to Japan. I settled on using GDP as an equal comparison of the activity within the country (World Bank, 2022). After isolating countries that have a GDP between $2-5 trillion USD, Japan still soared high above all other countries. 

I chose the line chart because I wanted to see in one place, how the different countries stacked up and if there were any jarring outliers like Japan. I restricted the number of countries that can be displayed on the chart by including the multi-select picker. This allows the chart to only show a limited amount of data by default, but still allows the reader interact with the visualization and add in a country they might find interesting to investigate. With the default countries, I made Japan pink to stand out as the outlier and gave all the other countries a grey color to be placed in the background for comparison. Lastly, I added a clear title that will draw the reader to the message of the visualization. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11143960"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Additional Sources: 
The World Bank. (2022). _GDP (current US$)_. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?most_recent_value_desc=true
