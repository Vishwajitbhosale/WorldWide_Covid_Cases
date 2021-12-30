# WorldWide_Covid_Cases

"Countrywise_Covid_Cases.txt" file contains the aggregated countrywise data of covid cases. This is an historical data.

First the data recived from API is stored in HDFS, then the using HVE table agregated the data countrywise. Finally using SQOOP the data from hdfs is transferred to MYSQL database.

Using "GRAFANA", an open source dashboarding tool, created pannel for covid cases wordwide. The created pannel is shown in "WorldMap_with_CovidCases.png" image.

All the process and commands are provided in the code.txt
