# Assignment 5:
## Python Version==3.10
## Used Libraries and Versions
- re == 2.2.1
- json == 2.0.9
- glob
- os
- datetime
- pickle

## Exercises and Brief Explanations

### Exercise 1: How many annotations you have per month and year. Which month has more annotation files.
- Created two dicts named "months" and "years"
- based on pattern and datetime library, extracted the date
- Through conditionals, added years and months to the dicts
- With max_month and max_count variable, determined the month with highest files through conditionals and for loop.

### Exercise 2: Create a dictionary where each **key** is a month, and the corresponding **value** is a list containing all the annotation names with where their date corresponds to the month. 
    a. Save it following the json format, and load it again to check that everything is ok.
    b. Save it this time using Pickle.
    c. Instead of storing a list of all the annotation names happening that month, let's create for each annotation a dictionary with keys: name and date (using a datetime object).
- Imported json and pickle
- Created a new dict named and add it to the months dict and iterate with for loop to do this process for each file. 
- Wrote the months dictionary to a json file
- Read the json file
- Printed the json file
- Repeated with the pickle

### Exercise 3: Print all the annotations from the oldest ones to the newest one during the second half of the 2024. 
- Created a new list for the files in the second half of 2024
- Added the files to the list using if conditions.
- Sorted them using sort()
- Iterated with for loop and print each file
- If the list is empty, informed the user