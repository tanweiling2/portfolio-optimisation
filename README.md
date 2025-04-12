# portfolio-optimisation

Objective: Construct a portfolio consisting of 43 industry portfolios (risky assets), with the goal of maximising Sharpe ratio when evaluated on the test dataset. 

The results of the usage of a robust shrinkage estimator for returns and the covariance matrix gave results that exceeded that of the Tangency Portfolio and also CVaR portfolio. 
The dataset was extracted from the Kenneth R. French data library, with a time period of 1986-2015

https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html


Project Document: 
The file gp data 1986 to 2015.csv contains the following information (Credit: Kenneth R. French Data Library):
• Mkt-RF : The excess return on the market portfolio, i.e., the value-weight return of all applicable
firms incorporated in the US and listed on the NYSE, AMEX, or NASDAQ;
• RF : The riskless return rate;
• The next 43 columns: The monthly return of 43 industry capital-weighted portfolios. The
descriptions of those industries are provided in the file 43 industry description.txt.

All returns are measured in the unit of percentages on a monthly basis. These data series all start in January of 1986 and run through the end of 2015. Therefore, there are 30 years in total.

2 The Data Challenge (35 pts)

Imagine you are an investor at the beginning of the Year 2016 and would like to know the answer to the following single question:
• How to allocate my money among the 43 industries with an investment horizon of 5 years?
With the provided historical data, try to come up with a portfolio that you recommend.

2.1 Rules of the Data Challenge
1. Your final recommendation is a vector of weights for the 43 industries.
2. Your weights among the 43 industry portfolios should sum up to one.
3. You could use the toolboxes in this class, or you can develop your own methods. (If you use
external sources, please explicitly mention them.)
4. For simplicity, the weights are static: you cannot re-balance your portfolio within the next 5
years.
5. You cannot use any information you are not supposed to know at the beginning of the Year 2016
(for example, you should not Google the stock prices in 2018). Use your best judgment on this
rule!
2.2 Deliverable
Please submit your final recommendation. Please also summarize your thought process and reasoning
for your recommendations. Report the intermediate steps/calculations/visualizations, if any.
In addition, we will also organize a workshop in Week 13 for every group to present their strategies,
findings, and reflections in class.

2.3 Evaluation
1. Your recommendation will be evaluated on the 2016-2020 data (which was not made available to
you). The main performance metric is the Sharpe ratio. Other metrics, such as expected return
and standard deviation, will also be considered.
2. The goal of this data challenge is to give you a flavor of portfolio management in practice.
While the top-performing team will get bonus points based on 2016-2020 performance, your
grades in this section will be mainly based on how thorough your thought process is and your
understanding of the subject.
