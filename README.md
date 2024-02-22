library(rio)
continent= import('https://raw.githubusercontent.com/datalake101/continents/main/continent.csv')
df= inner_join(df, continent, by='country')
