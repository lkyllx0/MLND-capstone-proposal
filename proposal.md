# Machine Learning Engineer Nanodegree

## Capstone Proposal

Takayoshi Nishida  
XX October, 2017

## Proposal

### Domain Background

Predicting the stock price has been researched for long. 
Now many people try to predict with the machine learning algorithms, 
but there is not a single answer for this and it is still challenging problem.

It is also known that every country's stock market influences each other.
So putting the another country's stock market price and predicting the stock price index worth challenging.

### Problem Statement

The goal of this project is to predict whether the Nikkei 225 index increases or decreases compared to the previous day. 
Nikkei 225 is a stock market index for the Tokyo Stock Exchange. 

My hypothesis is that the Nikkei 225 has a strong correlation with the US stock prices (NASDAQ index) and foreign exchange rate (JPY/USD) of the previous day.

### Datasets and Inputs

#### 1. Nikkei 225 

The data starts from January 1950 to current date. This is obtained using Quandl.
- https://www.quandl.com/data/NIKKEI/INDEX-Nikkei-Index
#### 2. NASDAQ Index

The data starts from January 2003 to current date. This is obtained using Quandl.
- https://www.quandl.com/data/NASDAQOMX/COMP-NASDAQ-Composite-COMP

#### 3. Currency Exchange - JPY/USD

The data starts from March 1991 to current date. This is obtained using Quandl.
- https://www.quandl.com/data/CURRFX/USDJPY-Currency-Exchange-Rates-USD-vs-JPY

### Solution Statement
_(approx.1 paragraph)_

In this section, clearly describe a solution to the problem.
The solution should be applicable to the project domain and appropriate for the dataset(s) or input(s) given.
Additionally, describe the solution thoroughly such that it is clear that the solution is quantifiable 
(the solution can be expressed in mathematical or logical terms) , 
measurable (the solution can be measured by some metric and clearly observed), 
and replicable (the solution can be reproduced and occurs more than once).

### Benchmark Model
_(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, 
problem statement, and intended solution.
Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, 
which could then be objectively compared to the solution.
Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.

### Evaluation Metrics
_(approx.1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model.
The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution.
Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable).
Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
_(approx.1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem.
Provide thorough discussion for what strategies you may consider employing, 
what analysis of the data might be required before being used, or which algorithms will be considered for your implementation.
The workflow and discussion that you provide should align with the qualities of the previous sections.
Additionally, you are encouraged to include small visualizations, pseudocode, 
or diagrams to aid in describing the project design, but it is not required.
The discussion should clearly outline your intended workflow of the capstone project.
