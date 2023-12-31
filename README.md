# Investment-Case-Study

This is a Data Cleaning, EDA and Data Analysis project done using Python, NumPy and Pandas. The format is a question-and-answer type.
The dataset has funding information of the Indian Startups from January 2015 to August 2017.
The following questions were asked and the following insights were found. 

## Q1. Check the trend of investments over the years.

### Ans :- To answer this question, Total number of fundings done in each year was found and  a line graph between the year and the number of fundings was also plotted.

Year - Number of Fundings  
2015 - 936  
2016 - 993  
2017 - 443  

![image](https://github.com/AmartyaBansod/Investment-Case-Study/assets/139859241/53efe8c9-50b4-415e-9b8d-74984702cd69)

The dip in the number of fundings for the year 2017 can be attributed to the fact that the data is only present till August. 

## Q2. Find out which cities are generally chosen for starting a startup.

### Ans :- The top 10 Indian cities which have the most number of startups were found to answer this question. A pie chart was plotted for the same.

Before answering the question, there was some data cleaning to be done.  
The city names had multiple values for the same city, e.g.- New Delhi had the value of "New Delhi" as well as "Delhi". There were some issues with case sensitivity, e.g. 'Bangalore' was also given as 'bangalore'.  

These values were cleaned and then the solution was found.   
For a few startups, multiple locations are given, one Indian and one Foreign. These startups were counted as Indian startups with the Indian city name coming first.  

The following are the top 10 cities with the most startups -  
Bangalore - 635  
Mumbai - 449  
New Delhi - 389  
Gurgaon - 241  
Pune - 91  
Noida - 79  
Hyderabad - 77  
Chennai - 67  
Ahmedabad - 35  

![image](https://github.com/AmartyaBansod/Investment-Case-Study/assets/139859241/062c25ba-9094-4064-9c2b-330c3a816071)

## Q3.
