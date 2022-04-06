## This work has been done by Akhil Udathu

The datasets from all years were merged into a single dataset for ease in cleaning and processing. 

To be able to extract the individual datasets easily, a year column was added to each dataset. 

The data was then put into a postgres store in a schema called fifa. 

The primary key would be combination of sofifa_id and year. (During preprocessing sofifa_id was renamed to fifa_id) 
