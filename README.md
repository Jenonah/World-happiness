# World-happiness
# Objectives

- To identify Key factors  influencing happiness.
- To compare happiness levels among different regions and countries and provide insights into the disparities and similarities in happiness scores for a better understanding of countries that are doing great and identify ones which require more attention.
- To Analyze the relationships between the components that contribute to happiness.

# Data Source

Happiness data was gotten from https://drive.google.com/file/d/1_CnjjxdWbtB5mhh2nvazMmOQMO0H-WdY/view?usp=drivesdk
The country-continent data scrapped from https://statisticstimes.com/geography/countries-by-continents.php

# Data Cleaning and Transformation
Power Query was used for the data cleaning and power Bi was used for visualization.
- Used the first row as the header for the dataset.
- Scraped a dataset containing countries and their corresponding continents from the web.
- Deleted unwanted columns from the scrapped country-continents dataset.
- Merged the country-continents dataset with the cleaned happiness dataset based on the country names.
- Expanded the merged column to display the continents for each country.
- Created a happiness segment table to analyze how different components influence the happiness score.
- Used DAX to calculate a new table called "continent average happiness" to show the average happiness score per continent
- Calculated a new measure called "rating" to determine the happiness rating for each continent.

# Findings

- The dataset contains 146 countries and 6 continents.
- The average happiness score across all countries is 5.92.
- Finland is the happiest country, while Afghanistan is the least happy country.
- Oceania is the happiest continent, while Africa is the least happy continent.
-  Europe has the highest number of countries (42 countries), accounting for 22.77% of the total, while Oceania has the least number of countries (2 countries), accounting for 1.37% of the total.
- The components Dystopia (1.83) + residual, GDP per capita, and social support have the highest scores, accounting for 32.98%, 25.40%, and 16.31% of the total happiness score, respectively. Generosity contributes the least to happiness, with a score of 2.56%.
- Possibility of High Happiness: Three segments show a high possibility of happiness, with average happiness scores of 7.35, 6.96, and 6.51.
- The most important factors for high happiness scores are the sum of GDP per capita, the sum of freedom to make life choices, and the sum of social support at different values. Notably, Dystopia was not mentioned as an important factor as it serves as a benchmark for the worst country.
- Happiest Countries in Each Segment: When the average happiness score is 7.35, the happiest country is Luxembourg, and the least happy country is Venezuela. When the average happiness score is 6.96, the happiest country is Australia, and the least happy country is Estonia. When the average happiness score is 6.51, the happiest country is Singapore, and the least happy country is Panama.

These findings provide valuable insights into the factors influencing happiness levels across countries and continents and highlight specific countries that stand out in terms of happiness scores under different scenarios.

# Recommendation

- Countries with lower happiness scores should be provided with resources and support to improve the well-being of their citizens. Identifying the specific factors contributing to lower happiness in these nations can guide policymakers in formulating effective strategies.
- As social support is a significant factor in happiness, countries should invest in building strong support systems, such as improving healthcare, education, and community engagement programs to foster a sense of belonging and connectedness among citizens.
- Given the substantial impact of GDP per capita on happiness scores, economic development should remain a priority for countries seeking to increase well-being.
- Recognizing the significance of freedom to make life choices in influencing happiness, governments and societies should prioritize individual freedoms and autonomy. By ensuring citizens have the liberty to make personal decisions, pursue their interests, and participate in societal matters, ultimately contributing to increased happiness levels.
- Although generosity has a relatively low impact on happiness, promoting a culture of giving can still contribute to overall well-being. Public awareness campaigns and incentives for charitable activities can be implemented to foster a spirit of generosity within societies.
- Dystopia an essential benchmark for understanding the worst-case scenario. Countries should be aware of their progress in comparison to this benchmark and strive to continually improve their citizens' well-being.
