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

The November spike in wildlife collisions can be attributed to a confluence of factors. Seasonal migrations, mating periods, and hunting seasons align during this time, contributing to the surge in incidents. As wildlife embark on journeys or become more active due to hunting pressures, they are more likely to cross paths with vehicular traffic. This underscores the importance of understanding the seasonal dynamics of wildlife collisions, contributing to strategies for wildlife protection and road safety. By delving into the factors behind these patterns, it offers valuable insights for conservation efforts and roadway design considerations.

<p align="center">
  <br>
  <img src="/images/img2.jpg">
</p>

<b>Species Distribution:</b>

The dynamic interplay of species impacted by collisions is vividly portrayed in the heatmap chart and the chart below, revealing a spectrum of diversity among the top 10 species affected. White-Tailed Deer takes the forefront, accounting for a substantial 32.4% of the total collisions, with a staggering 9944 recorded incidents. Mule Deer follows closely behind, contributing 26.1% with 8014 incidents, emphasizing the considerable impact of these species on collision data.

In addition to deer species, the analysis highlights other notable contributors to vehicular collisions. Moose, registering at 6.7% (2066 incidents), Coyote at 6.5%, and Porcupine at 4.6%, add to the diversity of species affected. This comprehensive insight prompts a closer examination of why these species, including deer, are prominently affected. Factors such as population density, inherent vulnerability due to increased movement, and external influences on their habitats may contribute to the observed collision rates. Understanding these nuances is vital for formulating targeted solutions and strategies to minimize collisions and foster coexistence between vehicular traffic and diverse wildlife populations.

<p align="center">
  <br>
  <img src="/images/img4.JPG">
</p>

<h3>Geospatial Analysis</h3>

The visual representation below illustrates the specific locations where incidents involving Elk occurred over the course of six years. The subsequent scatter plot provides a comprehensive overview of the average latitude and average longitude values for each species affected by incidents. These insights are instrumental in discerning the prevalent geographical areas where a higher frequency of incidents is observed. Such knowledge enables us to identify regions of heightened risk for certain species, paving the way for targeted conservation efforts and preventive measures in those specific geographical zones. This analytical approach allows us to identify regions of elevated risk not only for Elk but also for other species impacted by incidents.

Two distinct clusters emerge in the geographical distribution of Elk incidents — one in the southern region near Lethbridge and another in the northwestern part of Alberta near Grande Prairie. There were also concerns raised in a recent article regarding Parks Canada's monitoring of the declining elk population in Banff. The article underscores a worrisome trend in elk population decline across Alberta in recent years. An annual survey conducted in the lower Bow Valley, spanning from Castle Mountain to the east gate of Banff National Park, reported a fall classified count of 139 elk in 2022. This figure represents a notable decline compared to previous years: 171 in 2021, 212 in 2020, 249 in 2019, and 267 in 2018. The observed decrease raises significant conservation concerns, highlighting the importance of continued monitoring and conservation efforts to safeguard Alberta's Elk population.

<p align="center">
  <br>
  <img src="/images/img3.jpg">
</p>

The following are some of the insights from the analysis of the average latitude-longitude for each species.
- Species like Antelope and Rabbits & Hares are more commonly impacted in southern regions.
- Mule Deer, Red Fox, Porcupine, and Coyote collisions are concentrated in more northern and westerly regions.
- Elk, White-tailed Deer, Moose, and Black Bear collisions show a clear northern and westerly distribution, with Elk being more westerly and Moose being more northerly.

This relative comparison provides insights into the diverse geographical patterns of wildlife collisions for each species, aiding in the development of targeted preventive measures for specific regions and species.

The visualization below shows the changing landscape of collision incidents, particularly in the year 2022 compared to all the previous years. 

<p align="center">
  <br>
  <img src="/images/img8.JPG">
</p>

The geospatial visualization of incident data using latitude and longitude coordinates revealed distinctive trends:

- <b>Reduced Incidents in Northern Regions</b>: Notably, 2022 exhibited a decline in the number of incidents in the Northern parts, particularly in proximity to Grande Prairie. This shift may indicate alterations in wildlife movement patterns or changes in habitat usage in these regions.

- <b>Persistent Hotspots Near National Parks</b>: The concentration of incidents remained conspicuous around National Parks, with Banff emerging as one of the enduring hotspots. This sustained prominence suggests the continued vulnerability of wildlife in these protected areas, highlighting the need for targeted conservation efforts.

- <b>Decrease in Incidents South of Lethbridge</b>: An intriguing observation in 2022 was a noticeable reduction in incidents in the Southern regions, particularly south of Lethbridge. This could be attributed to various factors, including local conservation initiatives or changes in human activities influencing wildlife behavior.

- <b>Consistent Incidents Near Major Cities</b>: Despite fluctuations in certain regions, incidents continued to be significant in proximity to major cities such as Edmonton, Calgary, and Red Deer. The persistent occurrence near urban centers underscores the ongoing challenges of wildlife-urban interactions and emphasizes the importance of implementing measures to mitigate such incidents.

<h2>Clustering Analysis</h2>

Unraveling the patterns of wildlife collisions through clustering isn't just an analytical exercise — it's a critical step towards targeted conservation efforts. By identifying distinct clusters, we can gain insights into the specific regions where incidents are prevalent. This enables us to tailor preventive measures based on geographical features, proximity to cities, and landmarks, thereby fostering more effective wildlife protection strategies.

In essence, clustering emerges as a powerful tool not only for understanding the spatial dynamics of wildlife collisions but also for crafting proactive solutions that safeguard both wildlife and human communities. To ensure the speed of processing is not impacted and to observe relevant patterns in the recent past, I ran the clustering algorithms on data exclusively from the year 2022.

I initially opted for HDBSCAN, drawn to its reputation for robustness, but it fell short of providing the clarity I was aiming for. The resulting clusters lacked well-defined boundaries, posing challenges for interpretation. While HDBSCAN offers advantages over DBSCAN, particularly in handling varying cluster densities and identifying noise points, its performance on the spatial data didn't align with the distinctiveness I needed for effective geospatial clustering. I then pivoted to hierarchical clustering, a method that captures underlying structures within the data by forming a tree-like hierarchy of clusters. This strategic shift proved instrumental, yielding clusters with well-defined boundaries and a more intuitive structure as shown in the chart below.

<p align="center">
  <br>
  <img src="/images/img5.JPG">
</p>

Hierarchical clustering not only partitions data into clusters but also structures these clusters hierarchically. This hierarchical approach aligns seamlessly with the geographical context of the data. By organizing clusters in a tree-like structure, hierarchical clustering provides a comprehensive representation of the inherent hierarchy in the wildlife collision data, capturing relationships between clusters at different scales. While HDBSCAN excels in capturing density-driven clusters, hierarchical clustering, specifically applied in this analysis, emphasizes the hierarchical structure in a way distinct from HDBSCAN. The hierarchical clustering approach embraces the layered nature of geographical data, where proximity and hierarchy play pivotal roles. This ensures that the clusters not only reflect dense regions but also capture the broader spatial relationships between clusters. The result is a more nuanced and interpretable segmentation of the geospatial landscape of wildlife collisions.

The heatmap and the bar chart below illustrate the number of incidents for each month within each cluster, providing valuable insights into the seasonal patterns of wildlife collisions. The heatmap shows a normalized frequency of incidents, while the bar chart shows the species that were the most impacted within each cluster.

<p align="center">
  <br>
  <img src="/images/img6.JPG">
</p>

<p align="center">
  <br>
  <img src="/images/img7.JPG">
</p>

<b>Cluster 1</b>: Peaks in June and November suggest heightened incidents, possibly linked to breeding or migratory seasons. A significant number of incidents (280) impacted Moose. In addition, November's peak aligns with White-Tailed Deer breeding patterns.

<b>Cluster 2</b>: Distinct patterns show elevated incidents from October to November, aligning with mating seasons or migration. Diverse impact on White-Tailed and Mule Deer. Coyote incidents (over 100) in this cluster could relate to territorial behaviors or seasonal activities.

<b>Cluster 3</b>: Varied monthly distribution with notable incidents in October, November, and December, potentially related to fall wildlife movements. Substantial Mule Deer incidents (1300) indicate areas with a higher population. November's peak also coincides with increased wildlife movement.

These findings underscore the importance of considering seasonal and species-specific patterns for targeted wildlife collision prevention. The clusters offer a geographical context, aiding in pinpointing regions with distinct collision risk factors.

<h2>Conclusion: Unveiling Insights into Wildlife Collision Incidents</h2>

In the culmination of my comprehensive analysis of wildlife collision incidents, I embarked on a journey to uncover patterns, trends, and geospatial nuances encapsulated in the data spanning from 2016 to 2022. My multifaceted approach aimed to not only visualize incidents but also derive actionable insights to inform conservation strategies and enhance public awareness.

<h3>Key Results</h3>

<b>Latitude and Longitude Summary Statistics:</b>
A focus on latitude and longitude summary statistics revealed the geographical distribution of incidents. Insights gleaned from these statistics included the identification of prominent hotspots, the influence of proximity to National Parks, and a nuanced understanding of incident density in various regions.

<b>Exploratory Data Visualization:</b>
Leveraging data visualization tools, I brought the incident data to life, unveiling seasonal patterns, species distribution, and the impact of incidents across different months and years. Engaging visualizations enhanced my ability to communicate complex trends in an accessible manner. My exploration extended into a comparative analysis of 2022 against the preceding years. Notable findings included a reduction in incidents in Northern regions, persistent hotspots near National Parks, and consistent incidents in proximity to major cities.

<b>Species Impact Analysis:</b>
The examination of species impact allowed me to discern the most affected wildlife, guiding my focus on targeted conservation efforts. Filtering and visualizing the top species provided clarity on the types of collisions demanding immediate attention.

<b>Clustering Analysis:</b>
Transitioning into advanced analyses, I delved into clustering techniques to uncover spatial patterns within incidents. While HDBSCAN initially fell short, hierarchical clustering emerged as a robust alternative, emphasizing the hierarchical structure inherent in geographical data. Evaluation metrics, including the Calinski-Harabasz Index and Silhouette Coefficient, validated the efficacy of my clustering approach. The clear delineation of clusters provided a nuanced understanding of incident patterns, enabling more targeted interventions.


<h3>Achieving Project Objectives</h3>

<b>Spatial Understanding</b>: Through geospatial analyses, I achieved a good understanding of the spatial distribution of wildlife collision incidents, uncovering regional variations and identifying areas of heightened risk.

<b>Conservation Implications</b>: The identification of hotspots and impactful species paves the way for informed conservation initiatives. By pinpointing regions with elevated incident frequencies, authorities can tailor interventions to protect vulnerable wildlife populations.

<b>Public Awareness</b>: My visualizations and analyses provide a compelling narrative for public awareness campaigns. By translating complex data into accessible visuals, I contribute to fostering a greater understanding of the human-wildlife interface and the importance of responsible driving.


<h3>Future Measures for Prevention</h3>

The project findings underscore the critical need for targeted measures to prevent wildlife collisions, particularly in regions proximate to major cities and conservation parks. To address this, I propose some of the following strategies:

<b>Wildlife Crossings and Fencing:</b>
Continue to focus on the implementation of wildlife crossings and fencing near major highways and roads which can significantly mitigate collisions. These structures guide wildlife to safe passages, reducing the risk of encounters with vehicles.

<b>Speed Limits and Signage:</b>
Strategic adjustment of speed limits in high-risk areas, coupled with clear signage, can enhance driver awareness. In regions identified as collision hotspots, reducing speed limits and implementing wildlife-awareness signage can contribute to safer road conditions.

<b>Public Education Campaigns:</b>
Launching targeted public education campaigns can foster awareness about the prevalence of wildlife collisions and encourage responsible driving behaviors. Collaborations with local communities, schools, and businesses can amplify the impact of these campaigns.

<b>Technology Integration:</b>
Exploring the integration of advanced technologies, such as wildlife detection systems, into transportation infrastructure can provide real-time alerts to drivers, offering a proactive approach to collision prevention.

<b>Collaboration with Conservation Authorities:</b>
Continued collaboration between transportation authorities and conservation organizations is paramount. Joint initiatives can focus on habitat preservation, ensuring that wildlife populations are not displaced into high-risk areas.

By implementing these measures, Alberta can proactively address the challenges posed by wildlife collisions, fostering safer roads for both human commuters and the diverse wildlife that shares their habitat.

In summary, this project not only fulfilled its core objectives but also ventured beyond, offering a holistic perspective on the intricate dynamics of wildlife collision incidents. The amalgamation of data exploration, visualization, and advanced analyses positions this project as a valuable resource for conservationists, policymakers, and the general public, emphasizing the urgent need for concerted efforts to mitigate the impact of vehicular collisions on our wildlife populations.
