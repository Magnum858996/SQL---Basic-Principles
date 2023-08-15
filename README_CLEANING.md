SQL---Data-Cleaning-in-SSMS

In my experience learning SQL for data analysis, I have used three different platforms: MySQL, BigQuery, and SQL Server Management Studio. This project uses code specific to the latter, as I wanted to distinguish it from the previous COVID-19 project in which I used BigQuery.
This project examines how to clean data outside of using spreadsheets. While Excel is fun to filter down and remove blanks and duplicates, sometimes datasets are so unwieldy that Excel (or Google Sheets) is insufficient for the task.
This was inspired by Alex the Analyst, in which he provided a more advanced SQL tutorial to do some interesting things. The dataset he/I used can be accessed and downloaded on his Github profile here.
To prepare my data, it was first necessary to install the essential components: SSMS and SQL Server 19. I specifically used the 19th edition, as I found its Import and Export Wizard the most user-friendly. (Technical detail: to connect to the server, I clicked options > connection properties > and checked the “trust server certificate” box.)
Once my tools were setup, I loaded the dataset (in an Excel spreadsheet) as a CSV using the Import Wizard. From there, I was ready to clean this magnificent raw data set of Nashville Housing.
