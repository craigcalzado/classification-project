# Classification Project - Telco Churn
<h2>Objectives:</h2>

- Documentation of all code, processes, findings, and key takeaways in a Jupyter Notebook Final Report.
- Creation of modules the make that process repeatable and easy to follow.
- Construct a model that perdicts customer churn using classification techniques.
- Deliver a Report in the form of a 5 minute presentation.

<h2>Buisness Goals:</h2>

- Find drivers for customer churn at Telco and answer why are customers churning?
- Construct a Machine Learning classification model that accurately predicts customer churn.
- Deliver a report that anyone can read through and understand what steps were taken, why and what was the outcome.

<h2>Audience:</h2>

- Target audience is direct chain of command and administrative executives.

<h2>Deliverables:</h2>

- Accurate and helpful documentation
- Jupyter Notebook Report (.ipynb)
- Necessary modules for project repoduction (.py)
- Prediction probabilities and data (.cvs)

<h2>Context:</h2>

- Utilization of Telco Co. dataset acquired from Codeup SQL database

<h2>Data Dictionary</h2>

| Attribute | Definition | Data Type | Additional Info |
| --- | --- | --- | --- |
| customer_id | Unique customer identification number | object |
| senior_citizen | If customer is a senior | int64 |
| partner | If customer has a partner | object |
| dependents | If customer has dependents | object |
| tenure | How long the customer has been with Telco | int65 |
| phone_service | If the customer has a phone line with Telco | object |
| multiple_lines | If customer does have phone service do they have more than one | object |
| online_security | If the customer has online security with Telco | object |
| online_backup | If the customer has online backup service with Telco | object |
| device_protection | If the customer has device protection with Telco | object |
| tech_support | If the customer has tech support with Teco | object |
| streaming_tv | If the customer has streaming tv service | object |
| streaming_movies | If the customer has streaming movies service | object |
| paperless_billing | If the customer opt in for electronic statments | object |
| monthly_charges | The monthly bill the customer recives | float |
| total_charges | The total amount the customer has been charged | object |
| churn | If the customer has churned or not | int64 | 1=has churned, 0=has not churned |
| gender_male | If the customer is a male or not | uint8| 0=female, 1=male |
| payment_type_credit card(automatic) | If the customer pays with debit card | uint8 | 0=not automatic,1=automatic |
| payment_type_electronic check | If the customer pays with electronic check | uint8 |
| payment_type_mailed check | If the customer mails in a check | uint8 |
| contract_type_one_year | If customer is locked into a 1 year contract | uint8
| contract_type_two_year | If customer is locked into a 2 year contract | uint8
| internet_service_type_Fiber Optic | If the customer has Fiber Optic or DSL | uint8 | 0=DSL, 1=Fiber Optic |
|internet_service_type_None | If the customer has no internet service | uint8 | 0=has internet, 1=has no internet
| contract_type_monthly | If customer is on a month to month contract | int64 |
| tenure_years | How many years the customer has been with telco | float|

<h2>Questions:</h2>

- What are the drivers for customer churn?
- What are the steps that will be taken to predict customer churn?
- Why are customers churning?
- Who is the target of churn?
- How long until the customer churns?
- How long until churn is addressed?

<h2>Hypotheses</h2>

- Alpha = .05 (95% confidence level)

<h2>Hypo #1 Fiber vs. Churn</h2>

-  $H_0:$ There is no correlation between Fiber internet service and customer churn.
-  $H_a:$ There is a correlation between Fiber internet service type and customer churn.

<h2>Hypo #2 Electronic Checks vs. Churn</h2>

-  $H_0:$ There is no correlation between  Electronic checks and customer churn.
-  $H_a:$ There is a correlation between Electronic checks type and customer churn.

<h2>Hypo #3 Monthly Contracts vs. Churn</h2>

-  $H_0:$ There is no correlation between  Monthly Contracts and customer churn.
-  $H_a:$ There is a correlation between Monthly contracts and customer churn.

<h2>Hypo #2 Tenure vs. Churn</h2>

-  $H_0:$ There is no correlation between  tenure and customer churn.
-  $H_a:$ There is a correlation between tenure and customer churn. 

<h2>Executive Summary/Conclusion and Recommendations</h2>

Discovery:

- There were four driver of churn internet service(Fiber), Payment(Electronic Check), Month to month contracts, and Tenure.
- Analysis showed that customers under a year of tenure were the most likley to churn.
- The Classification model predited the churn of customers at a 78% accuracy.

Reccomendations:

- Offer incintves to move customers from month to month to a 1 or 2 year contract.
- Offer incintive to setup autopay.
- Target customer who have a tenure less then 12 months.
- Create surveys to check the integrety of the Fiber optic internet service.
- For customers on Fiber offer DSL until Fiber is stable.

<h2>Data Science Pipeline</h2>

<h2>Plan, Acquire, Prepare, Explore, Model, and Deliver</h2>

<h2>Plan</h2>

- Created documentation(README.md) with objuctives, data dictionary, buisness goals, and hypothesis
- Located data for exploration aswell as created functions to automate data prep. Functions located in 'acquire.py' and 'prepare.py'
- Create an outline of how to move forward through the pipeline.

<h2>Acquire</h2>

- Accessed Data by utilizing acquire.py to pull the data from SQL database.
- Initilized data summarization with .info(), .describe(), .value_counts()

<h2>Prepare</h2>

- Utilized stored functions within prepare.py 
- Cleaned data by creating useful columns and dropping not so useful columns.
- Split cleaned data into train, validate and test data sets.

<h2>Explore</h2>

- Answered key questions and figured out which features were the true drivers of churn.
- Created two statistical tests that measured the the relationships of churn.
- Created visulizations of the drivers of churn.
- Summerized conclustion and began to provide answers to specific questions and identified key take aways.

<h2>Model</h2>

- Created a baseline accuracy to determine if the models i created are useable.
- Utilized the train data set to fit, transform and evaluate multiple models. Utilizing differnt hyperparameters and algoithums.
- Compared evaluation metrics though all models and selecting the best for the validatation data set.
- Based on evalution of the train and validate data i selected the model that moves to testing.
- Tested final model sumerized performance and document the results,

<h2>Project Reproduction</h2>

- Python
- SQL
- numpy
- sklearn
- pandas
- matplotlib
- seaborn
- stats
- acquire.py
- prepare.py
- env.py(your credientials)
- final_report.ipynb











