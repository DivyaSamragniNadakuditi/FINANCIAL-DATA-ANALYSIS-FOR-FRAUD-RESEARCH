# FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH
PROBLEM STATEMENT 1: 
Percent of Fraud occurrence based on age, Gender revealed.

PROBLEM STATEMENT 2: 
Top 5 categories of  fraud occurrence.

PROBLEM STATEMENT 3: 
Fraud repetition from same customer account and top 5 merchant accounts with the most number of frauds.

Video link:
https://bridgeport.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=e542a965-7642-4874-8db5-aa8f017864a2

## DataSet

You can find the dataset in kaggle using the below link:
https://www.kaggle.com/ntnu-testimon/banksim1#bsNET140513_032310.csv
It consists of around 595k rows.
Though it is financial data , no personal information is disclosed.

1. How we got the data
BankSim, a simulator for Bank Payments is used  for data generation based on real data provided by a bank in spain. Restricted by Zip Code to Madrid and Barcelona. Realistic Fraud Data sharing as the main Goal.

2. Model used
Statistical and Social Network Analysis (SNA) of relations between merchants and customers were used.

3. Usage of Data
These generated details are used for fraud detections

![Image 2](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture2.png)

## Use Case Diagram used by BankSim

![Image 1](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture1.png)
## Modeling

###### MapReduce
The data is made into key-value pairs like Age- Fraud, Categories - Fraud. These pairs are processed aggregated and the output of this is generated as key - values

![Image 3](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture3.png)

![Image 4](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture4.png)

![Image 5](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture5.png)

![Image 6](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture6.png)

![Image 7](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture7.png)

![Image 8](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture8.png)

###### Spark
In this model, we create schema for our data and process it. The data after processing it and output of the analysis is generated. The output can be further visualized in graphs and diagrams. We can use pyspark or spark sql. The schema when implemented gives the output after reducing.

###### Hive
Hive is another model in which we use sql queries in it which actually runs  a mapreduce program

![Image 9](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture9.png)

![Image 10](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/images/Picture10.png)

## Poster and Technical Paper
Here is the poster of this project:
![Image 11](https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/Financial%20Data%20analysis%20for%20fraud%20detection%20Poster.png)

You can find the technical paper at the below link:
https://github.com/DivyaSamragniNadakuditi/FINANCIAL-DATA-ANALYSIS-FOR-FRAUD-RESEARCH/blob/master/Phase%205%20WritingUp.pdf




