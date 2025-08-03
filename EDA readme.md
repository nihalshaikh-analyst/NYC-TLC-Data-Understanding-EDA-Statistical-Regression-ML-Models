# Exploratory Data Analysis (EDA) of New York City TLC Data


New York City Taxi and Limousine Commission (New York City TLC) Yellow taxi trip data analyze, clean, process, data analysis by using Python and its Library **pandas, numpy, matplotlib.pyplot, datetime and seaborn**  with presentation in Jupyter Notebook.


![NYC](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/NYC%20tlc.png)
![TLC](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/Taxi%20trip.png)

## Project Overview

**The NYC Taxi & Limousine Commission has contracted with Automatidata to build a regression model that predicts taxi cab ride fares. In this part of the project, the data needs to be analyzed, explored, cleaned and structured prior to any modeling.**


## Project background

**Automatidata is working on the TLC project. The following tasks are needed before the team can begin the data analysis process**

- EDA and cleaning

- Select and build visualization(s) type

- Create plots to visualize relationships between relevant variables

- Share your results with the Automatidata team

[Dataset](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/2017_Yellow_Taxi_Trip_Data.csv)

## Specific project deliverables

- Strategy Document to consider questions, details, and action items for each stage of the project scenario.

- Answer the questions in the Jupyter notebook project file.

- Create a Jupyter notebook of full EDA.

- Create a Tableau visualization showing two important variables.

- Write an executive summary of results and include a visualization.

# Step by Step EDA Process

**The goal is to clean data set and create a visualization.**

-  1: Imports, links, and loading

-  2: Data Exploration

- Data cleaning
-  3: Building visualizations

- 4: Evaluate and share results

- For EDA of the data, import the data and packages that would be most helpful, such as pandas, numpy and matplotlib.

- Then, import the dataset.

- Decide which columns are applicable
  The first step is to assess your data. Check the Data Source page on Tableau Public to get a sense of the size, shape and makeup of the    data set. Then answer these questions to yourself:
  Given our scenario, which data columns are most applicable? Which data columns can I eliminate, knowing they won’t solve problem    
  Consider functions that help you understand and structure the data.

head()

describe()

info

groupby()

sortby()


- There is no missing data according to the results from the info() function.

- On the data source page in Tableau, double check the data types for the applicable columns you selected on the previous step. Pay close    attention to the dimensions and measures to ensure they are correct.

- Select data visualization types that will help you understand and explain the data.

Line graph
Bar chart
Box plot
Histogram
Heat map
Scatter plot
A geographic map

- Perform a check for outliers on relevant columns such as trip distance and trip duration. Remember, some of the best ways to identify      the presence of outliers in data are box plots and histograms.

- The majority of trips were journeys of less than two miles. The number of trips falls away steeply as the distance traveled increases      beyond two miles.

- The months are out of order.

- Reorder the results to put the months in calendar order.

- Repeat the above process, but now calculate the total rides by day of the week.

- Suprisingly, Wednesday through Saturday had the highest number of daily rides, while Sunday and Monday had the least.

- Repeat the above process, but now calculate the total revenue by day of the week.

-  Thursday had the highest gross revenue of all days, and Sunday and Monday had the least. Interestingly, although Saturdd only 35 fewer     rides than Thursday, its gross revenue was ~$6,000 less than Thursday's&mdash;more than a 10% drop.

- Monthly revenue generally follows the pattern of monthly rides, with noticeable dips in the summer months of July, August, and            September, and also one in February.

- This plot presents a characteristic curve related to the cumulative density function of a normal distribution. In other words, it         indicates that the drop-off points are relatively evenly distributed over the terrain. This is good to know, because geographic           coordinates were not included in this dataset, so there was no obvious way to test for the distibution of locations.

To confirm this conclusion, consider the following experiment:

1. Create a sample of coordinates from a normal distribution—in this case 1,500 pairs of points from a normal distribution with a mean of    10 and a standard deviation of 5
2. Calculate the distance between each pair of coordinates
3. Group the coordinates by endpoint and calculate the mean distance between that endpoint and all other points it was paired with
4. Plot the mean distance for each unique endpoint


- There are 49 numbers that do not represent a drop-off location. 

- To eliminate the spaces in the historgram that these missing numbers would create, sort the unique drop-off location values, then         convert   them to strings. This will make the histplot function display all bars directly next to each other.

- Notice that out of the 200+ drop-off locations, a disproportionate number of locations receive the majority of the traffic, while all     the rest get relatively few trips. It's likely that these high-traffic locations are near popular tourist attractions like the Empire     State Building or Times Square, airports, and train and bus terminals. However, it would be helpful to know the location that each ID     corresponds with. Unfortunately, this is not in the data.

  **"EDA is important because ...
EDA helps a data professional to get to know the data, understand its outliers, clean its missing values, and prepare it for future modeling.
Visualizations helped me understand ..
That this dataset has some outliers that we will need to make decisions on prior to designing a model."**



## Storytelling and Problem Solveing

**"As a result of the conducted exploratory data analysis, the Automatidata data team considered trip distance and total amount as key variables to depict a taxi cab ride. The provided scatter plot shows the relationship between the two variables. This scatter plot was created in Tableau to enhance the provided visualization."**


![EDA NYC TLC Presentations](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/EDA%20NYC%20TLC%20Presentation.png)


## Key Insights

**"The Problem: After running initial exploratory data analysis (EDA) on a sample of the data provided by New York City TLC, it is clear that some of the data will prove an obstacle for accurate ride fare prediction. Namely, trips that have a total cost entered, but a total distance of “0.” At this point, our analysis indicates these to be anomalies or outliers that need to be factored into the algorithm or removed completely."**

Proposed solution: After analysis, we recommend removing outliers with a total distanced recorded of 0. 

**Keys to success**

- Ensuring with New York City TLC that the sample provided is an accurate reflection of their data as a whole.

- Plan for handling other outliers, such as low trip distance paired with high costs.


<img width="612" height="400" alt="image" src="https://github.com/user-attachments/assets/22c67883-f2c7-4024-819d-5f796f45e839" />


## Next Step 

**1. Determine any unusual data points that could pose a problem for future analysis in predicting trip fares.**

**2. For example, locations that have longer durations.**

**3. Determine the variables that have the largest impact on trip fares.** 

**4. Filter down to consider the most relevant variables for running regression, statistical analysis, and parameter tuning.**



 Any concern connect to us nihalshaikh.analyst@gmail.com


 -------Thank you..........
