# Unsupervised-Property-Fraud-Algorithm
End-to-end unsupervised fraud algorithm, used to detect fraud in the New York City valuation and assessment dataset.

Tax evasion is the act of avoiding one’s true tax payments by deceiving the government. Property tax evasion is among the most common forms of tax evasion, especially in New York City, where tax rates are high and the city is dense with properties. Property tax fraud occurs at all levels of property ownership, ranging from the large real estate firms, to the individual property owners. Identifying and flagging properties with anomalous information, typically through manipulation of their real valuation or assessment, is a necessary task.

This analysis will focus on identifying likely property tax fraud for New York City, through two fraud algorithms: a heuristic algorithm and an autoencoder. We will identify unusual values of variables, related to attributes of the property, that raise a cause for concern. The goal of this project is to assign each non-government property a score of fraudulence, identifying the principal one hundred most likely fraudulent records.

The report details the complete architecture, analysis, and determination processes of the unsupervised fraud models, which comprises seven sections:

1. Description of Data - original variables examined and summarised
2. Data Cleaning - excluded data and imputation
3. Variable Creation - manipulated variables to create expert variables
4. Dimensionality Reduction - removed correlations and performed linear transformation
5. Fraud Model Algorithms - established unsupervised machine learning model
6. Results - detailed description of results
7. Summary and Conclusions - summarized results and discussed future improvements

Two different methods were used in building this unsupervised fraud model. The first being
a heuristic function of z-scores, with a Minkowsky distance of p = 2, and the second being an autoencoder reproduction error, also with a Minkowsky distance of p = 2. After the construction and implementation of these two algorithms, we combined the two final scores by the average rank order, which became our final ranking system for which records were quantified by their possibility of fraudulence in descending order.

In addition, we discussed the implications of the inconsistencies in the New York City Property data, as well as the methods in cleaning the dataset and assembling the unsupervised model. We also recognized future improvements that would make for a stronger analysis of the fraudulence of properties.
