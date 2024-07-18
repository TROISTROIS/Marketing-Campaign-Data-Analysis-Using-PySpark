# Marketing-Campaign-Data-Analysis-Using-PySpark

## Problem Statement
Given a sample Json data for delivered AD campaigns which will be in 100s of GB per day, sample Json user profile data which will be in few 100 GBs, Json store file which will be in few 100 MBs. Various events captured are impressions, clicks and video ads. 

## Solve analytical problems with the following steps
1.	Load ad_campaigns_data.json, user_profile_data.json and store_data.json files in HDFS
2.	Write PySpark code in Jupyter notebook to solve below mentioned analytical Problems
   - Analyse data for each campaign_id, date, hour, os_type & value to get all the events with counts <br>
   - Analyse data for each campaign_id, date, hour, store_name & value to get all the events with counts<br>
   - Analyse data for each campaign_id, date, hour, gender_type & value to get all the events with counts<br>
4.	Store processed Json data of each problem statement into different HDFS output Directory
5.	Once output data is available into HDFS, create external Hive tables on top of it using Json Serde
