# HASS-assignment5

1. The data is first extracted from data.gov.sg as CSV. (Refer to expenditure.csv)

2. Next, the data is cleaned/grouped together using Python. Redundant rows/columns were also removed in Python. The data was also split into two - 
one of the development budget, the other of the operating budget. (Refer to expenditure_grouped.csv, expenditure_v2_grouped_depend.csv and expenditure_v2_grouped_operating.csv)

3. The CSV files that was generated from Python was then converted into JSON files. 

4. After that, to convert the json files to a hierarchical JSON array, another sequence of javascript was used to churn it. Refer to convert_tojson.html for the file.
The code was run twice to generate both sets of hierarchical data, for presentability and readability. (Refer to expenditure_grouped_v2_depend,json
or expenditure_grouped_v2_operating.json for this.)

5. Finally, the hierarchical json file was used to generate treemaps for both development and operating budget. (Refer to index.html for this.)
