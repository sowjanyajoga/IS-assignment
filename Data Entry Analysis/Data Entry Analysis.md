###### This markdown document is related to the three files POND2010, ZOOP-TEMP, ZOOP-TEMP-MAIN

### PROJECT TITLE
Data Entry Analysis Assignment

### LIST OF DATA FILES IN THE DIRECTORY
1. [POND2010](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/pond2010.xlsx)
2. [ZOOPTEMP](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp.xlsx)
3. [ZOOPTEMP-MAIN](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp-main.xlsx)


### FILES NEWLY ADDED
1. [POND2010](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/pond2010.xlsx)
2. [ZOOPTEMP](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp.xlsx)
3. [ZOOPTEMP-MAIN](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp-main.xlsx)
4. [Data Entry Analysis.md](https://github.com/sowjanyajoga/IS-assignment/blob/master/Data%20Entry%20Analysis/Data%20Entry%20Analysis.md)   
Note:  A markdown document which describes the problems in the data files and which provides solutions to those problems

### FILES MODIFIED
None

### FILES DELETED
None

### LAST MODIFIED
* Author/Contributor: sowjanyajoga  
* Date and Time: 09/10/17 13:00 PM

### SYNOPSIS
The 3 files linked above were all intended to be part of the same study – the investigators wanted to examine the day-night distribution of 2 species of zooplankton across multiple years. The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies. The investigators plan to repeat this study for several more years. 

### Task 1 Problems Identification
#1: Based on class readings, prior experience, and your own good sense, list some of the problems in the way that the data are currently organized (there are at least 8 problems with these spreadsheets; try to identify as many as possible, but at least 4).
**Response:** 
The problems identified from the data files provided are listed below:
1. Data is being maintained in two different files (zoop-temp.xlsx and zoop-temp-main.xlsx, which is not required as all the columns are same in both files.
2. In zoop-temp.xlsx it is stated that "_Station B is in a shallower southern arm of the lake, see yellow notebook for map and details_". But there is no yellow notebook or any link for this notebook provided.
3. The data collected only consists of the date but not the time at which the data is collected. So this data does not help the investigators to examine the day-night distribution of the zooplankton species
4. The units of measurement for the columns in all the data files are not mentioned
5. The pond2010 data is for the year 2010, whereas the zoop data is for the year 2011. Linking both these data files and converting this to useful information would be a difficult task
6. Negative values were found in few columns like "number of cuni/chippo per litre" which are not valid values.
7. When the data is viewed through the column names, one cannot get an idea of the exact definition of the column as the column names are abbreviated. There is no definitions stated for all the column names
8. Few values are in red/yellow. There is no reason stated for these color codes

### Task 2 Solutions
#2: Suggest a new system for organization. Create a table in your Markdown document showing a potential template for later years of data collection that would address the problems you identified in #1.
#### **Response**:
1. The data in zoop-temp.xlsx and zoop-temp-main.xlsx files can be combined into one single excel sheet
2. An additional column can be added with the column name as "Location" and a link to the map can be provided. Another additional column can be added with the name as "Miscellaneous Information" for noting any other important details
3. An additional column with the name "Time" can be added to analyze the data by the criteria of the day and night distribution
4. All the units of measurement considered during the investigation can be added after the column name 
5. Combining all the three excel files into one single file can help in eliminating these discrepancies
6. Make sure that there is no negative value included in the data
7. The column names should be expanded and not be written in short forms (just for the convenience of the investigator)
8. Having an additional column with the name "Miscellaneous information" as stated in point 2 can resolve this issue

### TABLES

**Table A: Chippo Table**  

| Date | Time(EST) | Temperature(Degree Celsius) | Density(kg/cubic meter) | Colony Diameter(meters) | Species | Depth(meters) | Chippo #/L | Chippo Colony Size(millimeter) | Chlorophyll A | Station | Miscellaneous Information |
|------|-----------|-----------------------------|-----------------|-------------------------|---------|---------------|------------|--------------------------------|---------------|---------|---------------------------|
|      |           |                             |                 |                         |         |               |            |                                |               |         |                           |

**Table B: Cuni Table**  

| Date | Time(EST) | Temperature(Degree Celsius) | Density(kg/cubic meter) | Colony Diameter(meters) | Species | Depth(meters) | Cuni #/L | Cuni Colony Size(millimeter) | Chlorophyll A | Station | Miscellaneous Information |
|------|-----------|-----------------------------|-----------------|-------------------------|---------|---------------|----------|------------------------------|---------------|---------|---------------------------|
|      |           |                             |                 |                         |         |               |          |                              |               |         |                           |


