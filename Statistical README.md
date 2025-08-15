# NYC TLC Statistical Analysis


New York City Taxi and Limousine Commission (New York City TLC) Yellow taxi trip data analyze, clean, process, data analysis by using Python and its Library **pandas, numpy, matplotlib.pyplot, datetime** and **seaborn** with **A/B testing, hypothesis testing** presentation in Jupyter Notebook.


![NYC](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/NYC%20tlc.png)
![TLC](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/Taxi%20trip.png)


## Project Overview

**The purpose of this project is to predict taxi cab fares before each ride. At this point, this project’s focus is to find ways to generate more revenue for New York City taxi cab drivers. This part of the project examines the relationship between total fare amount and payment type.**


## Project background

**Automatidata is working on the TLC project. The following tasks are needed at this stage of the project:**

- Explore the project data

- Implement a hypothesis test

- Communicate insights with team members and TLC stakeholders

[Dataset](https://github.com/nihalshaikh-analyst/NYC-Yellow-Taxi-Trip-Data-Analysis/blob/main/2017_Yellow_Taxi_Trip_Data.csv)



## Specific project deliverables

- Complete a PACE Strategy Document to consider questions, details, and action items for each stage of the project scenario.

- Answer the questions in the Jupyter notebook project file

- Statistical testing

- Report results in executive summary


## Jupyter Notebook

[Notebook](https://github.com/nihalshaikh-analyst/NYC-TLC-Data-Understanding-EDA-Statistical-Regression-ML-Models/blob/main/Statistical%20Analysis%20of%20NYC%20TLC.ipynb)


## Storytelling and Problem Solveing


### Problem

**"Taxi cab drivers receive varying amount of tips. While examining the relationship between total fare amount and payment type, this project seeks to discover if customers who pay in credit card tend to pay a larger total fare amount than customers who pay in cash."**


### Solution

**"The Automatidata team ran an A/B test to analyze the relationship between credit card payment and total fare amount. The key business insight is that encouraging customers to pay with credit cards will likely generate more revenue for taxi drivers."**

![Presentation](https://github.com/nihalshaikh-analyst/NYC-TLC-Data-Understanding-EDA-Statistical-Regression-ML-Models/blob/main/Statistics%20of%20NYC%20TLC%20Preasentations.png)


## Detail Key Insights

#### Steps conducted in the A/B test

**1. Collected sample data from an experiment in which customers are randomly selected and divided into two groups:**

- Customers who are required to pay with credit card.
  
- Customers who are required to pay with cash. This enables us to draw causal conclusions about how payment method affects fare amount.


**2. Computed descriptive statistics to better understand the average total fare amount for each payment method available to the customer.**
   
**3. Conducted a two-sample t-test to determine if there is a statistically significant difference in average total fare between customers who use credit cards and customers who use cash.**



#### A/B test results

**"There is a statistically significant difference in the average total fare between customers who use credit cards and customers who use cash. Customers who used credit cards showed a higher total amount compared to cash."**


## Next Step

##### "The Automatidata data team recommends that the New York City TLC encourages customers to pay with credit cards, and create strategies to promote credit card payments. For example, the New York City TLC can install signs that read “Credit card payments are preferred” in their cabs, and implement a protocol that requires cab drivers to verbally inform customers that credit card payments are preferred."


## Step by Step Process

-  Statistical analysis

- Imports and data loading

-  Conduct EDA and hypothesis testing

-  Communicate insights with stakeholders

-  Conduct an A/B test

-  Imports and data loading Import packages and libraries needed to compute descriptive statistics and conduct a hypothesis test.

-   Data exploration Use descriptive statistics to conduct Exploratory Data Analysis (EDA).

- In the dataset, payment_type is encoded in integers:

1: Credit card

2: Cash

3: No charge

4: Dispute

5: Unknown

- Hypothesis testing

- Null hypothesis: There is no difference in average fare between customers who use credit cards and customers who use cash.
-
- Alternative hypothesis: There is a difference in average fare between customers who use credit cards and customers who use cash

- State the null hypothesis and the alternative hypothesis
  
- Choose a signficance level
  
- Find the p-value
  
- Reject or fail to reject the null hypothesis

- 𝐻0
 : There is no difference in the average fare amount between customers who use credit cards and customers who use cash.

- 𝐻𝐴
: There is a difference in the average fare amount between customers who use credit cards and customers who use cash.

- Since the p-value is significantly smaller than the significance level of 5%, you reject the null hypothesis.

- Notice the 'e-12' at the end of the pvalue result.

- Communicate insights with stakeholders

- The key business insight is that encouraging customers to pay with credit cards can generate more revenue for taxi cab drivers.

- This project requires an assumption that passengers were forced to pay one way or the other, and that once informed of this requirement, they always complied with it.

- The data was not collected this way; so, an assumption had to be made to randomly group data entries to perform an A/B test. This dataset does not account for other likely explanations. For example, riders might not carry lots of cash, so it's easier to pay for longer/farther trips with a credit card. In other words, it's far more likely that fare amount determines payment type, rather than vice versa.


Any query contact to us nihalshaikh.analyst@gmail.com



-------------Thank you.................
