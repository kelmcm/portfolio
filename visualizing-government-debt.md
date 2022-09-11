## Assignment: Visualizing government debt
The goal of this assignment is to visualize global government debt over time. Countries take on different forms of government dept. The general government debt-to-GDP ratio is an indicator used to measure the health of a government's finances. In the below exercise we look at this metric from different lenses.   

### Part 1: Government finance sustainability above average for US and Canada - not a good thing
I've lived large portions of my life in Canada and the United States, so I like to compare these contries a lot when looking at data. Taking a peak at the general government debt-to-GDP ratio for 2019, Canada and the US are above average. For this indicator, a good value is below 60%. 

<iframe src="https://data.oecd.org/chart/6ObY" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6ObY" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

Source: OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 09 September 2022)

### Part 2: Global debt-to-GDP ratio trends upwards over past 3 decades
The below visualization similarly compares the general government debt-to-gdp ratio, howver it now shows the value over time between the years 1995-2021. Each country is shown with an individual sparkline. Sparklines are a nice tool to the trends of many datapoints all at once without overcrowding the visualization because each datapoint has their own mini-chart. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11143867"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Japan's debt-to-GDP ratio soaring above above all other countries
After transforming the data to lookg at all countries' ratio on a single line chart. It was clear how drastic Japan's debt-to-GDP ratio was above all others since the early 2000s. I decided to dig deeper to see which countires could actually be compared to Japan. I settled on using GDP as an equal comparison of the activity within the country (World Bank, 2022). After isolating countries that have a GDP between $2-5 trillion USD, Japan still soared high above all other countries. 

I chose the line chart because I wanted to see in one place, how the different countries stacked up and if there were any jarring outliers like Japan. I restricted the number of countries that can be displayed on the chart by including the multi-select picker. This allows the chart to only show a limited amount of data by default, but still allows the reader interact with the visualization and add in a country they might find interesting to investigate. With the default countries, I made Japan pink to stand out as the outlier and gave all the other countries a grey color to be placed in the background for comparison. Lastly, I added a clear title that will draw the reader to the message of the visualization. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11143960"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Additional Sources: 

The World Bank. (2022). _GDP (current US$)_. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?most_recent_value_desc=true

### Part 4: Many countries trending towards financial instability in recent years

<div class='tableauPlaceholder' id='viz1662922172861' style='position: relative'><noscript><a href='#'><img alt='Many countries trending towards financial instability in recent years ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Govtdept-to-GDPratioWorkbook&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Govtdept-to-GDPratioWorkbook&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Govtdept-to-GDPratioWorkbook&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1662922172861'); var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%'; vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>
