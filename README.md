# Segmenting-and-Clustering-Neighborhoods-in-Toronto
Peer-graded Assignment: Segmenting and Clustering Neighborhoods in Toronto

### 1_WebScraping_TO_Neighborhoods_data.ipynb

* The dataframe will consist of three columns: PostalCode, Borough, and Neighborhood
* Only process the cells that have an assigned borough. Ignore cells with a borough that is Not assigned.
* More than one neighborhood can exist in one postal code area. For example, in the table on the Wikipedia page, you will notice that M5A is listed twice and has two neighborhoods: Harbourfront and Regent Park. These two rows will be combined into one row with the neighborhoods separated with a comma as shown in row 11  in the above table.
* If a cell has a borough but a Not assigned  neighborhood, then the neighborhood will be the same as the borough.
* Use the .shape method to print the number of rows of your dataframe.

### 2_Add_Latitude_Longitude_TO

Now we need to get the latitude and the longitude coordinates of each neighborhood. 

* CSV file that has the geographical coordinates of each postal code is attached to this page

### 3_Explore_&_Cluster_TO_Neighborhoods

Explore and cluster the neighborhoods in Toronto. I decided to work with Scarborough region.
