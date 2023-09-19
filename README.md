# project1
Starbucks vs. Dutch Bros

This project focuses on conducting a comprehensive analysis of the business strategies employed by two major coffee chains, Starbucks and Dutch Bros, within Maricopa County, Arizona. To achieve this, I employed spatial analysis techniques to precisely map the locations of these stores. Starbucks store locations were acquired through web-scraping the Starbucks website, involving the conversion of a list of store addresses into geographical coordinates. For Dutch Bros, I manually created a dataframe by inputting store addresses and generated geocoded coordinates using the Bing API. In total, I mapped 399 Starbucks stores and 49 Dutch Bros outlets across Maricopa County, utilizing Python's Folium library for visualization.

![Starbucks vs Dutch Bros](https://github.com/jaenaldo/project1/assets/72944189/772a2918-4549-4031-b679-c1ff0e93ecc4)

Regarding spatial analysis, I calculated distances between Starbucks stores themselves and between Starbucks and Dutch Bros locations using the Haversine formula. The findings revealed that the median distance between the closest Starbucks stores is 2.53 kilometers, illustrating Starbucks' strategy of expanding its market presence by opening new stores, thanks to its substantial budgetary resources compared to Dutch Bros. Conversely, Dutch Bros strategically prioritizes proximity to Starbucks locations when opening its stores, with a median distance of 0.51 kilometers between Starbucks and their stores. These insights underscore the competitive dynamics and differing strategies within the coffee retail industry, highlighting how Starbucks maintains its market presence through resource allocation while Dutch Bros competes effectively against a formidable market leader.

![Starbucks and Starbucks](https://github.com/jaenaldo/project1/assets/72944189/f156aafd-14dc-45a8-baab-e0a87cfcb2d3)
![Dutch Bros and Starbucks](https://github.com/jaenaldo/project1/assets/72944189/50b47194-f017-4a28-b776-7cabb448c07f)
![Stat](https://github.com/jaenaldo/project1/assets/72944189/a107fca8-2be2-4e08-94ab-1271d72b6953)
