# Dynamic_Map_Creation_using_Geospatial_Covid19_Data
Worldwide dynamic mapping of spread of corona virus showing the dynamic change.

# Method
John Hopkins data contains country wise COVID 19 data taken from 22nd Jan,2020 up to 14th
Feb,2021 and also latitude and longitude and World shape file contains country name and coordinates from
vertices of polygon. We have joined two datasets through the country name and found mismatch of different
country names from two datasets when we tried to join them. To solve that problem, we have imported the
shape file in QGIS and after observing where such mismatches are present and we manually changed the
names to make them constant for the two datasets. Then using geo-pandas library, we have made dynamic
mapping of spread of corona virus and finally made a .gif file which shows the dynamic change.

Note: Find the code in master branch.
