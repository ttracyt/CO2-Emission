# CO2-Emission Dashboard

## About this project: 

Our objective for this assignmnet was to choose a global problem, collect datasets, and present our findings on Tabelau through dashboards. After we completed our project, I personally went beyond and made some changes and created new charts. 

My team members and I (a group of 3) chose 'Climate Change' as our topic, specifically focusing on the emission of Carbon Dixodie around the world. We chose climate change because our world is currently being affected by the effects of climate change such as the rising temperatures and melting glaciers. 

We will be using datasets we collected to provide insights on which countries were the largest producers of CO2 and by what fuel type (source). With our findings, we will 

## Business Questions: 

There are a total of 3 questions we hope to answer once we have our findings. 
  1. Which countries have the highest CO2 emissions? 
  2. Which sources contribute the most CO2 in the United States? 
  3. What are the impacts of CO2 emissions on our economy, society, and environment? 
  
 
### Personal Questions: 
  4. Which fuel type do countries emit the most? 


## Dataset we used & cleaning the dataset: 

The dataset we used is titled, "CO2 and Greenhouse Gas Emissons", by Hannah Ritchie, Max Roser, and Pablo Rosado. 

  Hannah Ritchie, Max Roser and Pablo Rosado (2020) - "CO₂ and Greenhouse Gas Emissions". Published online at OurWorldInData.org. Retrieved from: 'https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions' [Online Resource]


## Data cleaning & scrubbing: 

Before we used the dataset, some changes were made. First, we added a new column titled 'Total' which is the sum of each fuel type within that country. Next, we added replaced the spaces with underscores in each column name. 

When imported into Tableau, our dataset had over 10,000 rows with some being redudant data. We, therefore, used the filter method to keep rows ranging from the years 1750-2020 and 2010-2020. We also removed grouped up nations (for example Asia and Europe). 


## Findings and Insights: 

### 1. Which countries have the highest CO2 emissions? 

We applied a filter to only showcase top 10 countries with the highest CO2 emissions and in the year range of 2010-2020. We found that China, United States, and India were the top 3 CO2 producers. If we were to change oour year range to 2000-2010, United States was actually in the lead. From here, we can make predictions as to why the leading producer changed over the years. 

We chose to select a year range from 2010-2020; however, we can also choose individual years by changing our filter type. We made this chart interactive by adding a 'year' sliding filter on the side. 

### 2. Which sources contribute the most CO2 in the United States? 

From the chart titled, "----", we found that the top 3 fuel types produced in the United States were Oil, Coal, and Gas. 

### 3. What are the impacts of CO2 emissions on our economy, society, and environment? 

For this question, we did outside research on the impacts of CO2 emissions on our economy, society, and environment if countries continue to emit large amounts of CO2 into our atmosphere. 

## From my own personal questions 

### 4. Which fuel type do countries emit the most? Who are the top 10 producers for that source?  

For this question, I created my own chart to answer my question. From previous charts, I found that Coal was the largest fuel type produced by countries. From there, I filtered out top 10 countries from Coal production in 2020 and found that top 3 were China, United States, and Russia. The results are not any different from our previous findings; however, we see Africa and Poland on our new list. This tells us that though Africa and Poland weren't the top 10 general largest CO2 producers, they are producing large amounts of CO2 compared to other fuel types. 

<img width="988" alt="sources" src="https://user-images.githubusercontent.com/115118406/198791540-4a668a2b-c518-45c6-84d9-0330b55a9b1e.png"> 
