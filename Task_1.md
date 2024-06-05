# Task Instruction
My task - we need to understand PowerCo’s problem in detail
First things first, i and Estelle need to understand the problem that PowerCo is facing at a deeper level and plan how i tackle it. If you recall the 5 steps in the Data Science methodology, this is called “business understanding & problem framing”.

Your AD wants you and Estelle to email him by COB today outlining:

1. the data that we’ll need from the client, and
the techniques we’ll use to investigate the issue.

2. Use the text field below to write your email, here’s what you’ll need to include:

You must formulate PowerCo’s issue as a problem using the 5 step data science process and lay out the major steps needed to test it.

1. What do you think are the key reasons for a customer deciding to stay with or switch energy providers? For example: price, is it clean energy, customer service, location etc.
2. What data do you think would be useful in order to investigate these key reasons? E.g. customer purchasing trends over past 5 years, location of business etc.
3. If you were to get this data, how could you analyse or visualize it to test whether these reasons may have an impact on churn?

# Task Analysis
Hi [AD],

In order to test the hypothesis of whether churn is driven by the customers’ price sensitivity, we would need to model churn probabilities of customers, and derive the effect of prices on churn rates. 

We would need the following data to be able to build the models.

Customer data - which should include characteristics of each client, for example, industry, historical electricity consumption, date joined as customer etc.
Churn data - which should indicate if customer has churned
Historical price data – which should indicate the prices the client charges to each customer for both electricity and gas at granular time intervals

Once we have the data, the work plan would be:

We need to define what price sensitivity is and calculate it
We need to prepare the data and engineer features 
Then, we can test our hypothesis using a binary classification model (e.g. Logistic Regression, Random Forest, Gradient Boosted Machines to name a few)
We would choose a model from one of the tested algorithms based on the model complexity, the explainability, and the accuracy of the models.
With the trained model, we would be able to extrapolate the extent to which price sensitivity influences churn

Regards, Oyeyemi Ebenezer Oluwatobi.