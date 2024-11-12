# Assignment 6
## Python Version==3.10
## Used Libraries and Versions
### - pandas==2.2.3

## Exercises and Brief Explanations

### Netflix Exercises
#### 1. Is there any missing rating?
- using isna() and sum(), find the total number of missing ratings.
- in case there is no na value, inform the user. 

#### 2. How many films in 2021 correspond to your country?
- filter the df based on the country, "turkey", and year, 2021.
- display the films in different formats such as table, number, and titles. 

#### 3. What's the number of movies in 2020 with full information?
- filter df for movies that was released in 2020
- drop the rows with na values
- using len() find the number of rows

#### 4. Give me the year with more titles,
- create  a variable called most_titles_year
- group by release year
- count the title column and return the maximum index
- print the variable with the corresponding value

#### 5. and what has been the average in terms of releases from 2010. 
- filter based on the year 2010 and then group by release year with counting the title column
- calculate the mean of variable named "titles_per_year" which was created. 
- print the mean

### Titanic Exercises
#### 1. Calculate Gender-Based Survival Percentage
- group by gender and calculate the mean of column "2urvived"
- print the gender and the corresponding survival rate

#### 2. Calculate Survival Percentage Grouped By Gender And Class
- group by gender and class
- repeat the previous questions with adjusted groupby

