# LogAnalyze
滞在者情報算出

outputデータとして、以下  
・visit.csv：APを訪れた回数  
データ容量が大きいため、アップロードせず  
・staytime.csv：APに滞在した時間  
データ容量が大きいため、アップロードせず  
・stayhour.csv：時間別の訪問AP回数  
・stayday.csv：日別の訪問AP回数  



inputデータである、duration_all.csvは以下の形式  
clientid,from_time,duration,from,to  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-04 15:36:07,-1.0,1123,237  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-04 15:36:07,2356.0,237,259  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-04 16:15:23,696.0,259,256  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-04 16:26:59,340009.0,256,247  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-08 14:53:48,19.0,247,233  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-08 14:54:07,2173.0,233,237  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-08 15:30:20,602997.0,237,234  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-15 15:00:17,2321.0,234,256  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-15 15:38:58,862.0,256,243  
3ec5e05ca27d3c9c2e8adce4f460fad040e34e9a,2014-09-15 15:53:20,6573.0,243,246
