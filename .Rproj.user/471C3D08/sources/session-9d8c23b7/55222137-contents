library(tidyverse)
gapminder_data<-read_csv("gapminder_data.csv")

# Summarizing data
summarize(gapminder_data, averageLifeExp = mean(lifeExp))

# Working with the pipe operator
gapminder_summary <- gapminder_data %>% 
  summarize(averageLifeExp = mean(lifeExp))

