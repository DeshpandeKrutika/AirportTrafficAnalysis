# Exploratory Data Analysis of 2015 Flight Delays Dataset

### 2015 Flight Delays

The data-set used deals with the time delay of flights at the core of it, and different others parameters related to location, scheduled time, departure time,arrival time etc. that help with the prediction of delay and understand the trends of delayed flights for airports as well as airlines, giving a sneak peek into their functioning and capabilities. The dataset also contains details about airlines and airports along with location parameters such as city,state,latitude and longitude. This dataset is created by the U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics.

Some of the questions that can be answered with the insights are impact of the origin airport on delay, airlines prone to cause frequent arrival delays, busiest airports across the year and number of delayed flights based on various parameters such as airline, airport, day of the week,etc.

The complete dataset can be found at https://www.kaggle.com/datasets/usdot/flight-delays

![image](https://github.com/DeshpandeKrutika/AirportTrafficAnalysis/assets/133702243/b11e2483-dad3-4109-bb69-103d21304be5)


### Audience

The consumers of the results from this project are the Airline Industry. The informative visualizations showcase the statistics of delay, airport wise, which helps the airline concentrate on streamlining its processes at a given location. It also gives an insight into the trends in delays of its competitors, and trends across the calendar year.

### Story

The airline industry has one of the most complicated logistics processes in the world. Their conquest to streamline and optimize business processes while enhancing customer satisfaction and quality is an incessant and rigorous process. The data set in question, provided ample data to comeup with trends, distributions, predictions, etc. with which we can infer and gain useful insights, and observe pain points to be focused on.

### Data Science Life Cycle

The DSA-project lifecycle is an efficient methodology to follow to solve a data science problem. I went over each of the steps during my project lifecycle and did so in an iterative fashion. Following are some of examples of how I used these steps in my project.

1) Project definition, requirements, and expectations: Defined the aim of the project and identified my target audience which guided me to ask the right questions while analyzing the data
2) Data acquisition, governance, and curation: Acquired the data that will help me answer the questions for my stakeholder and ensured that the data is derived from a trusted source.
3) Data shaping and carpentry: Handled missing values in the data, removed unwanted rows, converted the formats of the columns where necessary, merged two datasets, created the result column, etc.
4) Exploratory data analysis and visualization: Used ggplot2 and dplyr to group,filter and summarize the data based of various parameters and plot them using the appropriate visual channels. Eg- Top 15 origin airports with the highest percentage of delayed flights
5) Statistics and ML modeling planning building testing: Appropriate machine learning models were used according to the question. Naive bayes for classification and Regression for prediction.
6) Statistics and ML model validation, visualization, and interpretation:The model was tested on the test dataset and satisfactory accuracy was achieved. The regression line was visualized.
Data story/product development & reporting: The derived insights are noted and presented to the audience with the help of visualizations.

#### Insights

Towards the end of the year the delays are lesser and in few cases the flights are early on schedule. The holiday season that onsets towards the end of the year usually witnesses a lot of air traffic, however data suggest that there is improved management, preventing high number of delays. There is reason to infer that when higher traffic is expected, the airlines and airport authorities are accordingly staffed and operations are streamlined in order to enhance customer satisfaction. The number of delayed flights are relatively higher during the mid of the year.

For an airline to have the highest number of delayed flights does not make it the highest probable airline to have a delay as we need to account for the total number of flights operated by the airline. The airport with the most number of delayed flights is WN, and the airport with the highest percentage of delayed flights is NK. It can be clearly inferred that the highest number of delays is not an accurate parameter to conclude an Airlines' efficiency with flight delays. Airlines like the WN, are very commercial and have more number of flights in the air at a given point in time. The superset of number of WN flights is higher and hence subsequently the delayed flights. Airlines like NK seem to be smaller in scale as they have more of their flights getting delayed than others. As WN airlines takes the 2nd spot in the US Domestic airline market share, its obvious to infer that its operations are streamlined and more efficient as compared to the smaller players.

The airport with the most number of flights is ATL, and the airport with the highest number of delayed flights is ORD. The top 15 busiest airports are not even a part of the top 15 airports with the highest percentage of delayed flights. This again brings home the point that the airports with higher air traffic per day does not necessarily lead to higher probability of flight delay. Infact, they cater to the air traffic with efficient logistics. ORD appears in the top 15 of airports with higher delayed flights as well as higher percentage of delay. This clearly shows that airport ORD has to ramp up its operations to try and reduce flight delay.

For American Airlines, the number of flights per month are almost double in the second half of the year. This is a significant increase. As was observed earlier for all airlines, American airline also follows the trend where the highest number of delayed flights occur in the mid of the year, specifically -July and August. Also, number of delayed flights are also high for the month of december. As the airlines had almost double the number of flights in the second half of the year, and observes higher number of delays in the second half. The airlines must increase their management power and make a better estimate of the departure and arrival times so that any expected delay can be accounted for within the scheduled time of the flights.

In a nutshell, these observations and insights are very valuable to the players in the airline industry to understand airports and their competitors to enhance customer experience.





