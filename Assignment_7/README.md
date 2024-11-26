## Assignment 7

### Python and Library Versions
Python==3.10
Pandas==2.2.3

### Questions and Brief Explanations

#### Exercise 1: Create a new column called **professor_initials** that stores the initials of each professor's first and last names. Use the following data:
- Column "professor" is split and first letter of each word is taken and created a new column named "professor_initials"

#### Exercise 2: Given the dataframe below. Use **join** to combine this new DataFrame with the original one based on the professor column.
- Used set_index on the column "professor"
- Used join to combine the dfs

#### Exercise 3: Combine the original df and df_courses DataFrames.
- Used merge to combine the dfs

#### Exercise 4: In the professor column, create a new column professor_last_name by extracting the last name of each professor using string operations.
- Split the name column and choosing the last word as the last name and creating a new column based on the last name.
