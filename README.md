# wildlife-road-safety
The purpose of this project is to analyze geospatial data spanning the last eight years to anticipate and prevent wildlife-vehicle collisions.

<h2>Background</h2>
As someone who has long been troubled by the distressing sight of lifeless animals on the sides of roads and highways during my drives, my concern has deepened over time. These incidents, which appear to be increasingly prevalent, present a critical issue. In Canada, it's estimated that a wildlife-vehicle collision happens roughly every 38 minutes. In the province of Ontario alone, there are approximately 14,000 reported wildlife collisions involving large animals each year. These collisions not only pose immediate risks to both human and animal lives but also have far-reaching consequences, including contributing to population declines, particularly among rare and endangered species. The visual below illustrates the consequences of wildlife collisions in Canada.

<p align="center">
  <br>
  <img src="/images/img1.JPG">
</p>

<h2>Purpose and Scope of Analysis</h2>

The purpose of this analysis is to harness the power of geospatial data obtained from the Alberta Wildlife Watch (AWW) Program, which collects data related to animal-vehicle collisions in Alberta. Animal-vehicle collisions account for 50% of all collisions on Alberta's highway network, leading to a significant number of injuries and fatalities each year. The financial toll is also considerable, costing Albertans $300,000 per day in property damage, healthcare expenses, and highway cleanup costs. AWW gathers essential data on animal carcasses through its mobile app, which pinpoints specific locations prone to these collisions. By identifying high-risk areas, understanding the species affected, and recommending protective measures, my aim is to reduce the occurrence and impact of these distressing incidents. I believe that the insights extracted from this project can serve as a blueprint for addressing similar challenges in regions across the globe where such incidents appear to be on the rise, contributing to global wildlife conservation efforts. 

My analysis will focus on the geographical distribution of animal-vehicle collisions, the species involved, and trends over the past eight years. I aim to identify collision hotspots, assess the consequences of roadways on wildlife, and suggest strategies to protect Alberta's ecosystems and its unique wildlife. Together, we can make a significant contribution to wildlife conservation and promote the harmonious coexistence of humans and animals.

<h2>Exploratory Data Analysis (EDA)</h2>

In the quest to understand the dynamics of wildlife-vehicle collisions, I began by delving into the geospatial aspects of the data. The analysis of Latitude and Longitude provided with crucial insights into the distribution of these incidents and their implications for the environment.

<h4>Latitude Insights:</h4>

The dataset consists of 30,708 data points, representing the locations of animal-vehicle collisions in Alberta. The Latitude values span from 49.00° to 59.21°, indicating the geographic breadth of these incidents. The standard deviation of approximately 1.85° suggests a relatively wide distribution of collision locations. The mean Latitude of around 52.09° signifies the central location of these accidents.

<h4>Longitude Insights:</h4>

The Longitude values range from -119.99° to -110.01°, reflecting the longitudinal diversity of these events. The standard deviation of roughly 1.86° emphasizes the dispersion in the locations. The mean Longitude of approximately -113.75° denotes the central position of these collisions.

Understanding the spatial distribution of wildlife-vehicle collisions helps set the stage for more comprehensive analyses. These insights serve as the foundation for uncovering spatial patterns, hotspot identification, and the development of strategies to mitigate these incidents. 

<h3>Time Series Analysis</h3>

<b>Seasonal Trends and Patterns:</b>

The chart below explores the number of species impacted by month and year. A striking seasonal pattern becomes evident, where the data unveils annual spikes in November. This recurring phenomenon signifies a crucial period characterized by increased wildlife movement and heightened collision risks.

The November spike in wildlife collisions can be attributed to a confluence of factors. Seasonal migrations, mating periods, and hunting seasons align during this time, contributing to the surge in incidents. As wildlife embark on journeys or become more active due to hunting pressures, they are more likely to cross paths with vehicular traffic.

<p align="center">
  <br>
  <img src="/images/img2.jpg">
</p>

<b>Species Distribution:</b>

The heatmap chart showcases the diversity of species impacted by these collisions. Among the species analyzed, White-Tailed Deer emerges as the most frequently affected, with 9944 recorded incidents. Following closely is Mule Deer with 8014 incidents, highlighting the significance of these species in the collision data. Additionally, the analysis identifies Moose, Porcupine, and Skunk as notable species affected by vehicular collisions.

This underscores the importance of understanding the seasonal dynamics of wildlife collisions, contributing to strategies for wildlife protection and road safety. By delving into the factors behind these patterns, it offers valuable insights for conservation efforts and roadway design considerations.
