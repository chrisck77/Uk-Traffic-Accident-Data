# Uk-Traffic-Accident-Data 
2 data sets 1.Uk Accidents, 2. vehicles involved in UK Accidents data 

Data Science on Uk traffic data, SQL, Tableau and Python

ETL1 	Data Wrangling with excel and notepad ++ (split file with notepadd++, data format with excel etc)

ETL2 	SSIS Load with MVS  - auto import into microsoft SQL database
                            - due dilligence check for errors
			    
ETL3 	MS SQL EXpress      - created working table WRK from RAW data
			                      - created Derived tables BLD from WRK (joined table)

note that the vehicle data set --> can be anywhere from 1 up to 20+ vehicles sharing same accident because they are from the same accident
Accident vehicle data will have unique accident number for each row

ETL3 	Accident file       - error checking  - filters (WHERE, ISNUMERIC <> 1, LEN, ISDATE)
                                              - PROC's stored procedures
	
VISUALISATION with TABLEAU  - using MS SQL Express to filter accident file back into a csv for opening with Tableau
