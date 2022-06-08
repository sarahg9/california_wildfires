# California Wildfires
https://github.com/sarahg9/california_wildfires

![screenshot1](/img/screenshot_1.JPG "2010 Fires Full State View")
![screenshot2](/img/screenshot_2.JPG "1980s Fires Close-Up")

# Project Description
Wildfires remain a major concern in California. Unplanned burns can destroy homes, infrastructure, and natural landscapes as well as negatively impact air and water quality. The risk of fires can be made worse by drought conditions and This project aims to explore the history of wildfires in California while using climate change as important context.

While we may hear about the current and long-term impacts of climate change, it can be difficult to visualize the consequences. Our map gives a visualization of changes over time and suggests a trend of increasing fires over recent decades. The focus on California and functions of the map were made with the hope of providing a more localized perspective of climate change impacts while bringing attention to a region heavily impacted by wildfires.
# Data Sources
The data visualized on this map was derived from [The California Department of Forestry and Fire Protection](https://frap.fire.ca.gov/mapping/gis-data/). We used ArcGIS to clean and format the large datasets in order to prevent loading errors and not meet the maximum file size for GitHub uploads. The bottom 10% of wildfire entries in terms of shape area were remove. Not all the entries had values for the acreage burned so we chose not to filter on that attribute. We did not expect the removal of the bottom 10% to have a significant impact on the visualization. Many of these entries were barely visible even at high zoom levels. Based on the statistics for the field, the largest shape area of the removed entries was well below the mean and median shape area values for the entire dataset. Additionally, the acreage burned values for the removed entries appeared to fall below 10 acres, which according to the [National Wildfire Coordinating Group](https://www.nwcg.gov/term/glossary/size-class-of-fire) places the wildfires in the lowest two of the seven size classifcation categories. 
# Applied Libraries
- We utilized [Mapbox](https://www.mapbox.com/) throughout this project and our basemap was a customized map imported from MapBox Studio.
- Our group also utilized [GitHub](https://github.com/) to not only collaborate, but to create a webpage using Github Pages.
- For help with HTML elements, we referenced [W3 Schools' HTML Tutorials](https://www.w3schools.com/html/default.asp).
- For the icons, we used Google Icons from [W3 Schools' icon search function](https://www.w3schools.com/icons/icons_reference.asp).
- The images on the site are from [Unplash](https://unsplash.com/) or similar websites that allow free use of photos.
- We utilized code from our [course's Lab 3 ](https://github.com/jakobzhao/geog458/tree/master/labs/lab03) for an initial framework for adding the map to the page.

# About Us
We are Geography 458 students from the University of Washington! Our goal for this project is to map wildfires in California. It is crucial to map wildfires because they are a valuable tool in depicting the consequences of climate change as well as assessing risk for residents. A few of us are from California and have a particular awareness of the drastic effects of these wildfires. Our passion for this topic has since grown, and we hope to bring awareness and visual aid of wildfires to those in need.
## Team Members
### Zoe Dooley
Geography Data Science Major
### Sarah Gest
Environmental Engineering and Geography Major
### Azzahra Nurmutmainnah
Geography Data Science Major
### Gavin Pereira
Geography Data Science Major
### Eric Fan
Geography Data Science Major

# Acknowledgment
Thank you to our professor and TA for their help with this project.
### Bo Zhao
Professor<br/>
zhaobo@uw.edu
### Jiaxin Feng
TA<br/> 
jxfang@uw.edu
