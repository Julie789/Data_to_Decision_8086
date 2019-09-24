# Data Entry Analysis
## Problems:
1. There are some color coding in the files, which doesn't have any explanation. 
2. There are some missing data in the file _pond2010.xlsx_. 
3. The proper units for the data is not mentioned like for _density_ or _Colony Diameter_. 
4. Some column can have multiple meanings in _pond2010.xlsx_. For example, column _temp_ can refer to temperature or temporary. 
5. The column _z_ has a range of values from 0.5 to 50. There is lack of explanation for the field. 
6. The graph shown in _zoop-temp.xlsx_ and _zoop-temp-main.xlsx_ has missing X-axis and Y-axis. Also, both the graphs are different. 
7. The date format is missing, though from the data of _pond2010.xlsx_ it is understood that it is in MM/DD/YYYY format. 
8. The headers for the tables are not self-explanatory. For example, column _Chla_ in _zoop-temp.xlsx_. The _zoop-temp-main.xlsx_ mentions the abbreviation details in another tab. 
9. The abbreviations should be listed down for each file. 
10. The average mentioned in the _zoop-temp.xlsx_ doesn't define the header appropriately as the average is taken for which column, it is clear from the formula in the cell. 

## Suggestions:
1. Define color coding. 
2. Fill in the missing data, or else mention the reason for missing fields. 
3. Add units for all the columns. 
4. Headers should have a meaningful name. 
5. Abbreviations should be defined in each file. 
6. The labels should be defined for the graphs. 
7. Mention date format in header. 
8. The data should be consistent in all the files. 

| Species | Date<br>(MM/DD/YYYY) | Temperature<br>(Fahrenheit) | Density<br>(g/cm^3) | Colony Diameter<br>(cm) | Depth<br>(cm) | Chlorophyll a |
|:---------:|:------------------:|:-------------------------:|:-----------------:|:---------------------:|:-----------:|:---------------:|
| cuni    | 6/5/2010         | 20                      | 59              | 3.03                | 10        | 3.6           |
| cuni    | 6/7/2011         | 15.2                    | 67              | 2.41                | 25        | 2.1           |
| chippo  | 6/5/2010         | 20                      | 61              | 2.88                | 50        | 3.6           |
| chippo  | 6/7/2011         | 15.2                    | 77              | 2.37                | 25        | 2.1           |
