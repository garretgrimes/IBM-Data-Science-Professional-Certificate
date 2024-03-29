# IBM-Data-Science-Professional-Certificate

Please note that to view the maps in this notebook, it is recommended that you use nbviewer.org instead of GitHub. The maps were created using the Folium library, and may not render properly on GitHub. To make it easier for you, here's a link to nbviewer.org.

https://nbviewer.org/github/garretgrimes/IBM-Data-Science-Professional-Certificate/blob/main/Analyzing_Austin_TX_Neighborhoods_IBM_Capstone.ipynb

For my IBM Data Science Professional Certificate I analyzed downtown Austin, TX to determine an optimal location for a new fusion food truck and bar. To gather and visualize data on potential locations, I utilized several tools, including BeautifulSoup, GeoPy, and an API to FourSquare.

With the use of BeautifulSoup, I scraped information on all the neighborhoods present in downtown Austin, while GeoPy enabled me to geocode the addresses of each neighborhood. This allowed me to accurately locate each neighborhood on a map, providing crucial insight into their distances from other significant landmarks and establishments in the area.

In addition, I utilized the Foursquare API to access information on the various types of establishments and businesses present in each neighborhood, such as restaurants, bars, coffee shops, and more. This provided key data points that helped me to collect information on the venues in the area and their respective locations.

To segment the neighborhoods in my analysis, I utilized kMeans clustering, an unsupervised machine learning algorithm that helped group similar neighborhoods together based on the types of establishments and businesses that were present in each one. This allowed me to better understand which neighborhoods had similar market conditions and potential competition.

In conducting my analysis, I considered several key factors such as foot traffic, accessibility, and visibility when identifying potential locations. My primary focus was on evaluating the existing competition in the area and identifying any gaps in the market that a new food truck and bar could potentially fill, recognizing that selecting the right location is crucial for the success of any new business venture.
