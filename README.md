# Health Factors Regression - WHO Life Expectancy Project

## Project Overview:
This project aims to develop a comprehensive regression model, incorporating mixed effects and multiple linear regression, using data spanning from 2000 to 2015 for 193 countries, to predict life expectancy for each nation. The project particularly emphasizes immunization factors, mortality rates, economic indicators, social elements, and other health-related variables. By scrutinizing these facets collectively, the research intends to provide nuanced insights into the determinants of life expectancy, guiding countries to prioritize specific areas for effective population health improvements.

## Tools & Skills:
### Python
#### Packages: pandas, NumPy, Matplotlib, Seaborn, Sklearn, OS, Folium, JSON, Pylab 
+ Conducted data wrangling and merging procedures.
+ Employed grouping and aggregation methods to structure and condense data.
+ Developed visualizations to improve the representation and comprehension of data.
+ Executed principal component analysis to optimize number of variables.
+ Performed multiple linear regression on life expectancy using the PCA variables.
+ Geographically analyzed life expectancy data using a world map JSON file.
+ Conducted time series analysis on GDP per capita, one of the leading influencing factors on life expectancy. 

### Tableau
https://public.tableau.com/app/profile/miguel.oliveira8698/viz/WHOLifeExpectancy_17072297231160/WHOLifeExpectancyProject?publish=yes

## Data Cleaning & Transformation:
The Scripts folder outlines a detailed procedural sequence of all the cleaning and transformation steps. Key steps include:
+ Replacing missing values with column averages.
+ Renaming columns to improve comprehension.
+ Aggregating data by country and removing the 'Year' column.
+ Renaming countries with wrong spelling and/or unnecessary wording.
+ Solving inconsistencies with Measles and BMI columns.

## Recommendations & Findings:
+ According to the data analysis, early vaccination rates, years of schooling and GDP per capita have the biggest impact on life expectancy.
+ According to the data analysis, years of schooling is the factor that most positively impact the average lifespan of a country's population.
+ Governments should invest in education at all levels, at it creates greater health awareness and healthy practices in the population.
+ Governments should invest in vaccinations, especially for Diphtheria and Polio and other diseases that increase both infant and adult mortality rates.
+ The WHO encourages economic policies that allow for creation of wealth and freedom of choice regarding healthcare.
+ The WHO recommends countries investigate and research factors affecting their adult mortality rate and mitigate them. According to the data analysis, some of the biggest factors affecting adult mortality rates are vaccination rates and alcohol consumption.

## Learning Experience:
Undertaking this project presented a steep learning curve, introducing me to advanced regression modeling techniques and expanding my proficiency in Python programming. Navigating through data wrangling and merging procedures, I honed my skills in handling large datasets and crafting meaningful visualizations using Matplotlib and Seaborn. Venturing into principal component analysis (PCA) for dimensionality reduction, I embraced novel statistical methodologies, challenging myself to think critically and creatively. Through iterative experimentation and guided mentorship, I refined my Python scripting abilities and problem-solving acumen. This experience underscored the importance of perseverance and adaptability in mastering new concepts and methodologies, fostering continuous learning and professional growth.

## Data Source:
The data originates from Kaggle, the world's largest data science community, uniting over one million registered users globally for discussions, model development, data exploration, and networking across 194 countries. https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who/data
