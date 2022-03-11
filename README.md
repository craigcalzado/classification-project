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



