
# Data Scientist Nano Degree

##  starbucks-capstone-project


# Installation 
- Anaconda disrtbution with python vesion of 3^ will suffice.

# Project Motivation
It is a capstone project from my nanadegree programm,
My aim is to build a model that can predict whether a customer is going to complete an offer sent to them by starbucks

# File Description
The notebook lays out my approach
This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.
The data is contained in three files:

- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
-  profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:
- portfolio.json
  -  id (string) - offer id
  - offer_type (string) - the type of offer ie BOGO, discount, informational
  - difficulty (int) - the minimum required to spend to complete an offer
  - reward (int) - the reward is given for completing an offer
  - duration (int) - time for the offer to be open, in days
  - channels (list of strings)

- profile.json
  - age (int) - age of the customer
  - became_member_on (int) - the date when customer created an app account
  - gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
  - id (str) - customer id
  - income (float) - customer's income

- transcript.json
  - event (str) - record description (ie transaction, offer received, offer viewed, etc.)
  - person (str) - customer id
  - time (int) - time in hours since the start of the test. The data begins at time t=0
  - value - (dict of strings) - either an offer id or transaction amount depending on the record

# Results and Insights
Results can be found in Notebook and [here](https://medium.com/@yasir.masad/analyzing-starbucks-offers-in-python-f4c40cf0d791)
# Acknowledgements
Credit goes to udacity and starbucks for providing the data
