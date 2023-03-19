# ICC Men's T20-Cricket World Cup 2022 Data Analysis
![ICC mEN'S t20](https://user-images.githubusercontent.com/118357991/226156747-e978c29f-7dde-40e1-b47f-dc45255cc5af.png)
In This project Created a Power BI Dashboard which helps to review and compare performances of all the players in T20 Men's Cricket World Cup 2022 tournament. This dashboard also enables us to select the best 11 of the tournament based on their performance based on defined selection criteria which is included as a part of problem statement.

## Datasource :

Scrapped all the data regarding match and world cup from www.espncricinfo.com and all details of player career performace and collect data on [brightdata](https://brightdata.com/)

## Data Collection:
Scrapped all the data regarding match and world cup and all details about players career from [brightdata](https://brightdata.com/) using Beautiful Soup library and Jupyter Notebook is used to convert the json files into the dataframes and then these dataframes into csv file for further data analysis on power bi.

## Data Transformation:
Performed initial data cleaning after scrapping such as player name correction, handle missing value, match id linking etc. using Pandas. Transformed the final data for dashboard using Power Query of Power BI.

## Data Modelling:
Connected all the datasets with based on some defined primary keys such as team and match ids. Also, created many measures, calculated columns and parameters for data analysis and dash boarding using DAX.

## Dashboard:
Created final dashboard using Power BI visuals

## Player Analysis : 

### Openers
![2022 T20 Cricket World Cup Dashboard- Best Final 11-2](https://user-images.githubusercontent.com/118357991/226159999-bc423241-a835-49c6-bbaf-4810089bbe44.png)


### Middle Order
![2022 T20 Cricket World Cup Dashboard- Best Final 11-3](https://user-images.githubusercontent.com/118357991/226160125-3183adf0-8155-4060-b47f-083f24771fa3.png)


### Finisher
![2022 T20 Cricket World Cup Dashboard- Best Final 11-4](https://user-images.githubusercontent.com/118357991/226160218-37527b00-f0da-4365-8a7b-fadff816d621.png)


### All Rounder
![2022 T20 Cricket World Cup Dashboard- Best Final 11-5](https://user-images.githubusercontent.com/118357991/226160322-29a2dac1-928f-4533-8ffb-3f1d4968d8cd.png)


### Specilist Fast Bolwers
![2022 T20 Cricket World Cup Dashboard- Best Final 11-6](https://user-images.githubusercontent.com/118357991/226160372-cdb65794-d49f-4aa8-b884-8f1bd6bd97e0.png)


### Final Best 11 Players
![2022 T20 Cricket World Cup Dashboard- Best Final 11-8](https://user-images.githubusercontent.com/118357991/226160404-653cf126-519c-426f-b715-a5041535e8d7.png)


## Tools, Software and Libraries

1.Jupyter Notebook

2.Python

3.Pandas

4.Webscraping

5.Beautifual Soup

6.Power Query Editor

7.Power BI

8.Anaconda Envirement

## References

https://codebasics.io/courses

https://2022.t20worldcup.com/

https://stats.espncricinfo.com/ci/engine/records/team/match_results.html?id=14450;type=tournament

https://www.espncricinfo.com/series/icc-men-s-t20-world-cup-2022-23-1298134/namibia-vs-sri-lanka-1st-match-first-round-group-a-1298135/full-scorecard

https://brightdata.com/cp/data_collector/collectors/c_lefxe7xf2rj3m5b1b3/code?draft_id=lefxeciy8d6v38d3d



