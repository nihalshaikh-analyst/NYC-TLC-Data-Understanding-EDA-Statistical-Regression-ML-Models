# NYC-Yellow-Taxi-Trip-Data-Analysis
New York City Taxi and Limousine Commission (New York City TLC) Yellow taxi trip data analyze, clean, process, data analysis by using Python and its Library pandas and numpy with presentation in Jupyter Notebook.

![NYC](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/NYC%20tlc.png)


## The NYC Taxi & Limousine Commission has contracted with Automatidata to build a regression model that predicts taxi cab fares. In this part of the project, the Automatidata data team performed a preliminary inspection of the data supplied by the NYC Taxi and Limousine Commission in order to inform the team of key data variable descriptions, and ensure the information provided is suitable for generating clear and meaningful insights.

## Background on the Automatidata scenario
Automatidata works with its clients to transform their unused and stored data into useful solutions, such as performance dashboards, customer-facing tools, strategic business insights, and more. They specialize in identifying a client’s business needs and utilizing their data to meet those business needs. 

Automatidata is consulting for the New York City Taxi and Limousine Commission (TLC). New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. The agency has partnered with Automatidata to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered. 

The TLC data comes from over 200,000 taxi and limousine licensees, making approximately one million combined trips per day. 

- Note: This project's dataset was created for pedagogical purposes and may not be indicative of New York City taxi cab riders' behavior.

## Team members at Automatidata and the New York City TLC
** Automatidata Team Members **
- Udo Bankole, Director of Data Analysis

- Deshawn Washington, Data Analysis Manager

- Luana Rodriquez, Senior Data Analyst

- Uli King, Senior Project Manager

Your teammates at Automatidata have technical experience with data analysis and data science. However, you should always be sure to keep summaries and messages to these team members concise and to the point. 


![TLC](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/Taxi%20trip.png)


## New York City TLC Team Members


- Juliana Soto, Finance and Administration Department Head

- Titus Nelson, Operations Manager

The TLC team members are program managers who oversee operations at the organization. Their roles are not highly technical, so be sure to adjust your language and explanation accordingly.

- Note: The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes. 

## Data dictionary
This project uses a dataset called 2017_Yellow_Taxi_Trip_Data.csv. It data gathered by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. In order to improve the learning experience and shorten runtimes, a sample was drawn from the 113 million rows in the 2017 Yellow Taxi Trip Data table.


## Project background
Automatidata is in the earliest stages of the TLC project. The following tasks are needed before the team can begin the data analysis process:

- Build a dataframe for the TLC dataset

- Examine data type of each column

- Gather descriptive statistics


## Specific project deliverables
With this end-of-course project, you will gain valuable practice and apply your new skills as you complete the following:

- Complete the questions in the Course 2 PACE strategy document

- Answer the questions in the Jupyter notebook project file

- Complete coding prep work on project’s Jupyter notebook

- Summarize the column Dtypes

- Communicate important findings to DeShawn and Luana in the form of an executive summary

## Step by step Process
1.Ready to answer questions and yield insights

2.Ready for visualizations

3.Ready for future hypothesis testing and statistical methods

The purpose of this project is to investigate and understand the data provided.

The goal is to use a dataframe contructed within Python, perform a cursory inspection of the provided dataset, and inform team members of your findings.

This activity has three parts:

- Part 1: Understand the situation

Prepare to understand and organize the provided taxi cab dataset and information.
- Part 2: Understand the data

Create a pandas dataframe for data learning, future exploratory data analysis (EDA), and statistical activities.

Compile summary information about the data to inform next steps.

- Part 3: Understand the variables

Use insights from your examination of the summary data to guide deeper investigation into specific variables.

## Task 1. Understand the situation
- How can you best prepare to understand and organize the provided taxi cab information?
Begin by exploring dataset and consider reviewing the Data Dictionary. One can prepare to understand the information by reading the taxi cab data fields and understanding the impact of each one. Reviewing the fact sheet could also provide helpful background information. However, the primary goal is to get the data into Python, inspect it, and provide DeShawn with initial observations. The next step would be to learn more about the data and check for any anomalies.

## Build dataframe
Create a pandas dataframe for data learning, and future exploratory data analysis (EDA) and statistical activities.

Code the following,

- import pandas as pd. pandas is used for buidling dataframes.

- import numpy as np. numpy is imported with pandas

- df = pd.read_csv('Datasets\NYC taxi data.csv')

Note: pair the data object name "df" with pandas functions to manipulate data, such as df.groupby().

- Regarding fare amount, the distribution is worth considering. The maximum fare amount is a much larger value ($1000) than the 25-75       percent range of values. Also, it's questionable how there are negative values for fare amount. Regarding trip distance, most rides are   between 1-3 miles, but the maximum is over 33 miles.

- The values align with our earlier data discovery, where we noticed that the longest rides are approximately 33 miles.

- Yes, the first two values are significantly higher than the others.

- The most expensive rides are not necessarily the longest ones.

- After looking at the dataset, the two variables that are most likely to help build a predictive model for taxi ride fares are             total_amount and trip_distance because those variables show a picture of a taxi cab ride.

## Project Status
- Explored dataset to find any unusual values.
- Considered which variables are most useful to build predictive models (in this case: total_amount and trip_distance, which work           together to depict a taxi cab ride).
- Considered potential interactions between the two chosen variables.
- Examined which components of the provided data will provide relevant insights.
- Built the groundwork for future exploratory data analysis, visualizations, and models.



## Insights
**1This dataset includes variables that should be helpful for building prediction model(s) on taxi cab ride fares.**

**2The identified unusual values are trips that are a short distance but have high charges associated with them, as shown in the             total_amount variable. Reference screenshots.**



## Next Step

**1.Conduct a complete exploratory data analysis.**

**2.Perform any data cleaning and data analysis steps to understand unusual variables (e.g., outliers).**

**3.Use descriptive statistics to learn more about the data.**

**4Create and run a regression model.**


Any query reach out nihalshaikh,analyst@gmail.com


------Thankyou......


