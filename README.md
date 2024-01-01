# Investment-Case-Study

This is a Data Cleaning, EDA and Data Analysis project done using Python, NumPy and Pandas. The format is a question-and-answer type.
The dataset has funding information of the Indian Startups from January 2015 to August 2017.
The following questions were asked and the following insights were found. 

## Q1. Check the trend of investments over the years.

### Ans :- To answer this question, the total number of fundings done in each year was found and  a line graph between the year and the number of fundings was also plotted.

Year - Number of Fundings  
2015 - 936  
2016 - 993  
2017 - 443  

![image](https://github.com/AmartyaBansod/Investment-Case-Study/assets/139859241/53efe8c9-50b4-415e-9b8d-74984702cd69)

### The dip in the number of fundings for the year 2017 can be attributed to the fact that the data is only present till August. 

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

### As is well known, the Silicon Valley of India, Bangalore has the maximum funding raised in the analysed timeframe. 

## Q3. Find out if cities play any role in receiving funding.

### Ans :- This question was answered by finding the top 10 Indian cities with the most amount of funding received. The percentage of funding each city contributes (among the top 10 Indian cities only) is found.

As we were dealing with the city name data column, the same data cleaning just as of Q2 was done here as well. The multiple cities assumption was made here as well.

Bangalore - 49.71  
New Delhi - 16.63  
Mumbai - 13.90  
Gurgaon - 12.21  
Chennai - 2.43  
Pune - 2.16  
Hyderabad - 1.15  
Noida - 1.01  
Ahmedabad - 0.58  
Jaipur - 0.21  

### This shows Bangalore's prominent role in the startup ecosystem, with its startups contributing nearly 50% of all funding. 

## Q4. There are 4 different types of investments. Find out the percentage of the amount funded for each investment type.

### Ans :- The total funding for each investment type was found and plotted in a pie chart. 

There were some mistakes in spelling for investment type, e.g. PrivateEquity, Crowd funding, SeedFunding which were replaced by "Private Equity", "Crowd Funding", and "Seed Funding" respectively. 

Private Equity - 98.15  
Seed Funding - 1.81  
Debt Funding - 0.04  
Crowd Funding - 0.00  

![image](https://github.com/AmartyaBansod/Investment-Case-Study/assets/139859241/a1e4bfb2-ce82-40bb-ad3a-f650817997b6)


### Funding via Private Equity seems to be the go-to type of funding for companies and investors while Crowdfunding contributes to almost negligible amounts.


## Q5. Which type of companies got more easily funding?

### Ans :- Given the data, it was assumed that the type of companies referred to the industry vertical the companies belonged to, Thus, The Top 5 industries and the percentage of the total amount funded to that industry (among the top 5 only) would answer this question. 

There were multiple spellings for E-commerce which were corrected to Ecommerce.

Ecommerce - 40.53  
Consumer Internet - 35.95  
Technology - 10.45  
Online Marketplace - 6.63  
E-Commerce & M-Commerce platform - 6.44 

![image](https://github.com/AmartyaBansod/Investment-Case-Study/assets/139859241/fe427b17-19a5-40a5-8896-37456323a30b)


### This shows a dominant focus on e-commerce and consumer tech, securing over 75% of total funding during the analysed period. 

## Q6. Find the top 5 startups with the most amount of total funding.

### Ans :- The total funding per startup was calculated. 
There are many errors in startup names, like Ola, Flipkart, Oyo, and Paytm, which were corrected.

Paytm
Flipkart
Ola
Snapdeal
Oyo

### Well-known startups, maybe well known for their funding rounds and valuations lead this list.

## Q7. Find the top 10 startups who received the most number of funding rounds.

### Ans :- Startups which got funding the maximum number of times are listed in the answer
There are many errors in startup names, like Ola, Flipkart, Oyo, and Paytm, which were corrected.  
Ola - 9  
Swiggy - 7  
UrbanClap - 6  
Paytm - 6  
Oyo - 6  

No. of Rounds - No. of Companies  
1    - 1713  
2    - 220  
3    - 39  
4    - 12  
5    - 4  
6    - 3  
7    - 1  
9    - 1  
### The 2nd table shows the number of companies vs the number of rounds. The table above shows the top 5 companies with the most funding rounds. These Five companies stand out as absolute magnets for investment, far exceeding the rest

## Q8. Find the Investors who have invested the maximum number of times.

### Ans :- Given that in a startup, multiple investors might have invested. Hence, each investor is counted separately, so a company with 3 backers adds 3 to the overall investor count
We decided to ignore the undisclosed investors.

Sequoia Capital - 64  
Accel Partners - 53  
Kalaari Capital - 44  
SAIF Partners - 41  
Indian Angel Network - 40  

### Sequoia Capital comes up on the top of this list.



