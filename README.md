# WorldWide_Covid_BasedON_Historical_data

"Countrywise_Covid_Cases.txt" file contains the aggregated countrywise data of covid cases. This is an historical data.

First the data recived from API is stored in HDFS, then the using HVE table agregated the data countrywise. Finally using SQOOP the data from hdfs is transferred to MYSQL database.

Using "GRAFANA", an open source dashboarding tool, created pannel for covid cases wordwide. The created pannel is shown in "WorldMap_with_CovidCases.png" image.

All the process and commands are provided in the code.txt

<img width="767" alt="image" src="https://github.com/Vishwajitbhosale/WorldWide_Covid_Cases/assets/92929807/c162e4b4-088e-465a-8df7-8004ba086ffc">

https://public.tableau.com/app/profile/vishwajit.bhosale/viz/Covid19_Data_16525348187550/Dashboard2
