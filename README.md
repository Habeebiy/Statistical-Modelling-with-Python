# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to find out if the number of bike stations within different parts of Quebec City correlates with the number of businesses within that location

1.	Define the problem
2.	Extraction of data from city-bike API
3.	Extraction of data from Foursquare and Yelp API
4.	Cleaned the data 
5.	Extracted relevant data from all three datasets and joined them into a single data frame 
6.	Performed EDA on the new dataset 


## Results
After dissecting the result from the three APIs, I discovered the Yelp API produces way better and quality information when compared to similar request from the Foursquare API

I tested my hypothesis on whether the number of businesses within a geographical area correlate to the amount of bike stations within that area by running a simple linear regression. The p-value turns out to be 0.173. 

## Challenges 
My major challenge whilst working on this project was extraction of data from both Yelp and Foursquare API. I ran into LIMIT based on the amount of API request I can make within a period time which significantly slowed my progress.

I also faced some time constraint challenges which prevented me from exploring those dataset in dept as I’d preferred to. 


## Future Goals
My future goal for this project will be to explore other city and also find out if certain time of the day affect bikes availability and what could have triggered the change if any. 
