# Uk-Traffic-Accident-Data 
2 data sets 1.Uk Accidents, 2. vehicles involved in UK Accidents data 

Data Science on Uk traffic data, SQL, Tableau and Python

### ETL - EXTRACT TRANSFORM LOAD

#### ETL1 	Data Wrangling with excel and notepad ++ 
- [x] split file with notepad++
- [x] data format with excel etc

#### ETL2 	SSIS Load with MVS  
- [x] auto import into microsoft SQL database
- [x] due dilligence check for errors
			    
#### ETL3
##### ETL3 Part 1 MS SQL EXpress      
- [x] created working table WRK from RAW data
- [x] created Derived tables BLD from WRK (joined table)

*note that the vehicle data set --> can be anywhere from 1 up to 20+ vehicles sharing same accident because they are from the same accident*
*Accident vehicle data will have unique accident number for each row*

#### ETL3 Part 2 	Accident file        
- [x] error checking  - filters (WHERE, ISNUMERIC <> 1, LEN, ISDATE)
- [x] PROC's stored procedures
	
### VISUALISATION with TABLEAU
- [x] Using MS SQL Express to filter accident file back into a csv for opening with Tableau
- [ ] TABLEAU Insights
