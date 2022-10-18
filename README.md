# DATA422-Group-Project
Repository for project diary, code files, and other resources used in the DATA422-22S2 group project.

Project Overview:
![alt text](https://github.com/parkerb193/DATA422-Group-Project/blob/main/Project_Overview.png)

Workflow:

1. The events-scraping notebook should be run first to produce events.csv.
2. This file is then used by the event-links and weather-api notebooks. 
   Either of these two notebooks can be run next to produce the corresponding .csv files.
3. The results notebook must be run after the event-links.csv has been created, and will generate the results.csv file. 
4. The injuries notebook does not depend on any of the other notebooks so it can be run at any stage.

Additionally, the Visualisations directory contains an R notebook that produces two example plots using the output data. 
