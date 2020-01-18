# Data-Mining-II
The final report for my Data Mining and Analytics II class that earned the WGU Academic Excellence Award.

The Jupyter Notebook holds the actual project, and all of the work needed to produce the final report.

The Report.pdf file is a stripped-down version of the final report, with assignment-specific details and questions removed to adhere to the governing academic policies. As specified in the report requirements, the work was packaged and presented in a Microsoft Word document that has many screenshots of the executed code. As the code was executed in the attached notebook, all of the screenshot information is directly from the notebook.

I recommend going over the notebook first as most of the rational is dictated in the explanation cells there, and then looking over the report if desired.

This project is done in Python using the various libraries in the scientific Python ecosystem of scikit-learn with a few other libraries for various uses. Specifically, this involves using pandas for data wrangling, manipulation, and cleaning, matplotlib and Seaborn for data visualization, and scikit-learn itself for model creation and analysis.


Project Goal:
The goal of this data mining and analysis project is to examine customer attrition patterns and to determine what indicators can be used to make better business decisions to prevent loss. Furthermore, a model will be produced in order to predict whether or not a given customer might discontinue business based on a model built from this analysis. This process will involve cleaning and tidying the dataset, testing for significance and correlation, finding and removing interactions, preparing the cleaned dataset for the modeling, and examining the results of the data mining for conclusions.

Methods of Analysis:
The primary descriptive method used in this project is FAMD, or Factor Analysis of Mixed Data. FAMD will be performed to both examine the variables in order to determine which are the most important, and to reduce the number of variables to examine without overly reducing the explained variance so that the predictive method will be easier to create and use.

MCA and PCA are also used to a lesser extent.

The primary predictive method will be logistic regression, and this technique will be used to build the predictive model. Logistic regression is appropriate because the dependent variable is Boolean and is easily predicted using the probability of binary results that logistic regression provides. Additionally, three of the variables are continuous, which factor easily into any type of linear regression, and the remaining are nominal categorical, which can easily factor into the regression by encoding them in dummy variables. Finally, the coefficients of each parameter that the model will provide can be used to see how much that variable affects the chance of churn. The result is a model that is robust, easy to understand, and is simple to use in predicting if a customer will churn or not.
