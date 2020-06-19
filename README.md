# data-science

# Med Cabinet


# StrainAPItoPG.py

Pulls approximately 24,393 rows of medical cannabis data from Strain API including:

id, name, race, effect ... as column headers.

The remainder of the code includes creating a connection to a Postgres Database hosted on ElephantSQL and storing the pulled Strain API data there, for analysis by DS in conjuncture with front end "form data" from the user that is submitted to the DS API for analysis, aka modeling and strain recommendation.


# StrainAPI.csv

CSV file from StrainAPI data in Postgres DB.


# cannabis.csv

Leafly data from Kaggle


# leafly_csv_wrangle.py

Wrangling the Leafly "cannabis.csv" data to discover 13 useful unique "effects" values for ML training and Front End user survey for relaying user input via app/API to the final pickled ML model for predictions.


# processing_data.ipynb

Processing Leafly data (cannabis.csv) to perform baseline model. "#to be pickled.... #nn, dtm, tfidf"

