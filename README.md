# ldn-restaurants-geospatial-analysis
Various geospatial analysis and visualization of london restaurant data
![Screenshot](screenshot1.png)

### Data Sources
 File name                                 |Data type                        |Source                              |Component
------------------------------------------ |---------------------------------|----------------------------------- |--------------
english_region_region.shp                  |Spatial                          |[data.gov.co.uk](https://www.data.gov.uk/dataset/d310b2c5-5253-4bc2-a78d-f8240293119d/boundary-line)                    |Shapefile(.shp, .dbf, .prj, .shx)
greater_london_const_region.shp            |Spatial                          |[data.gov.co.uk](https://www.data.gov.uk/dataset/d310b2c5-5253-4bc2-a78d-f8240293119d/boundary-line)                    |Shapefile(.shp, .dbf, .prj, .shx)
london_tube_stations.kml                   |Spatial                          |[doogal.co.uk](https://www.doogal.co.uk/london_stations)  |kml
London_Train_Lines.kml                     |Spatial                          |[doogal.co.uk](https://www.doogal.co.uk/london_stations)  |kml
bus-stops-example.csv                      |Non-spatial                      |[tfl.gov.uk](https://tfl.gov.uk/info-for/open-data-users/our-open-data)                           |Csv file(with the following columns: `Stop_Code_LBSL`	`Bus_Stop_Code`	`Naptan_Atco`	`Stop_Name`	`Location_Easting`	`Location_Northing`	`Heading`	`Stop_Area`	`Virtual_Bus_Stop`
rdata.csv                                  |Non-spatial                      |[wyre data api](https://wyre-data.p.rapidapi.com/restaurants/town/london)                           |Csv file(with the following columns:  `_id`	`BusinessName`	`RatingValue`	`AddressLine2`	`PostCode`	`Geocode_Longitude`	`Geocode_Latitude`)
London_tube_lines.csv                      | Non-spatial                     |[doogal.co.uk](https://www.doogal.co.uk/london_stations)|Csv file(with the following columns:  `Tube Line`	`From Station`	`To Station`

	
### To-do:
Add error handling functionality to functions
