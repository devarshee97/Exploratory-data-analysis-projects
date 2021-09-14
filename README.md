# Data analysis project
This repository contains my experience in data science through analysis of real world data, focussing primarily on data visualization, extraction of relevant insights so as to answer business queries and story-telling. Currently, there are two projects which can be briefly summarised in the following manner: 
1. The project entitled Zomato_Delfi_EDA is based on an exploratory analysis of various restaurant features in Delhi. This data is obtained from Kaggle where it is publicly available and the corresponding notebook is also uploaded for public access.
2. The second project is focussed on analysis of air quality in various states of India and is started from scratch. At first the air quality data is extracted from www.opendata.gov.in through API in JSON format. After doing the relevant processing, the data is converted to CSV and the relevant dataframe is prepared. However, this data has a missing component i.e the actual air quality index value for all measuring station. Hence, the latter is separately obtained from https://app.cpcbccr.com/AQI_India/ first in an excel file and then converted to csv format. The relevant column from this data is then merged with the former to obtain the final dataset for analysis.
3. The above data is updated in real time within every one hour
