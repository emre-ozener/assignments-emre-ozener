# Assignment 4

## Versions
- python==3.10.15
- numpy==2.1.2

## Libraries Imported
- numpy
- os
- glob

## Questions and Brief Explanation of Answers

### Question 1: How many files does the annotation file have?
- With glob the files are listed and the number of files are found through len().

### Question 2: How many of them follow the name convention expressed above?
- the path and file type is removed.
- through splitting by "_" and conditions, each part is tested and counted through counter and for loop.
### Question 3:How many of annotations you have per month and year. Which month has more annotation files?
- two dicts are created named "months" and "years"
- through for loop the and split the values of the dict keys and values are created.
### Question 4: Create a new annotations folder with multiple folders corresponding to a month.
- through os library new folders are created.
- to name the folders that are specific for months, previous dict is used. 
### Question 5: Print all the annotations from the most recent to the oldest one. 
- the date part is split from the rest of the file name and full file name and date is added to a nested list. 
- list is made a np.array and sorted. 
### Question 6: How many different satellites there are, how many annotations we have per satellite number, and which one was used in the most recent annotation file?
- Conditions in the second question's answer is used till the satellite number. 
- Dict for satellite is created.
- Through conditions and for loop the keys and values of the unique satellites are created.
### Question 7: How many unique regions are there?
- conditions and split used in the second question is used. 
- dict for region is created. 
- counter is created
- through conditions and for loop, the keys and values of the unique satellites are created.