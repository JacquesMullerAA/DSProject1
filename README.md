
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

I was interested in using Boston Airbnb listings data from 2016 to answer the following questions:

1. Who are the most popular hosts?
2. Which neighbourhoods are you most likely to stay in?
3. What determines the price, and can it be predicted?

The files for this analysis are located [here](https://github.com/JacquesMullerAA/DSProject1).

## File Descriptions <a name="files"></a>

There is 1 notebook to perform the initial data preparation, and 3 notebooks to answer each of the 3 questions. Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://jacquesmul.medium.com/3-questions-answered-about-airbnbs-in-boston-85574b14ecc2).

Summary of the results:
Data science was used to make some interesting observations and answer 3 questions about Airbnb’s in Boston:

1. Who are the most popular hosts?
There are 5 hosts with more than 60 listings each, and Kara with 138 listings is at the top of the list. The mean price per host is $143.95, but Aihua stands out with a mean price per listing of $375, which is $40 above that of the next host.

2. Which neighbourhoods are you most likely to stay in?
Neighbourhoods have on average 97.6 listings, but Allston-Brighton is at the top with 359 listings. The Financial District is the neighbourhood with the highest mean price of $283.69 per listing. Neighbourhoods have mostly high review scores, but Downtown and Camrbidge stand out with very low scores. East Boston is an appealing neighbourhood, being closest to the airport, relatively close to the city centre, a high number of listings and low mean prices.

3. What determines the price, and can it be predicted?
Price is indicated to be strongly positive related to variables: accommodates, bathrooms, beds, and guests_included — all related the room size and number of people that can stay in a room. However, relatively low regression coefficients of 0.3 were obtained using linear regression to predict price from these variables.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Information on the data used can be found on Kaggle [here](https://www.kaggle.com/airbnb/boston). Feel free to use the code here as you would like! 



