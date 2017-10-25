# Socrata-Github-AHP tool to prioritize the publication of open data 4 indicators
The Application is divided in the next subfolders (read the README.md for the details of everyone):
- db (contains the database shared by all the processes of this application)
- Socrata Dataset Gatherer
- Semi-automated-categorization-process
- Github ETL
- Indicators calculation process
- AHP 

Firstly, it is necessary to carry out all the steps included in Socrata Dataset Gatherer in the indicated order.

Then, is it possible to concurrently do the steps included in the Semi-automated-categorization-process and Github ETL.

Then, the combined result of the aforementioned process are used in the Indicators calculation process.

Finally, it is possible to create a Spreadsheet based on AHP that uses the indicators calculated in the previous process.

