# nosql-challenge

This challenge contains two Juptyer Notebook scripts and a Resource folder. The two Jupyter Notebook scripts are NoSQL_setup_starter.ipynb and NoSQL_analysis_starter.ipynb. The Resources folder contains a json file called establishments.json.

## NoSQL_setup_starter.ipynb
Once establishment.json is imported into the MongoDB server, the script loads in the database uk_food and the collection establishments and displays a document in the establishments collection. The script then updates the collection to add a new restaurant and then performs a query that deletes documents with a Local Authority of Dover. The latitude and longitude values are changed to decimal numbers, and the Rating Values are then changed to integers.

## NoSQL_analysis_starter.ipynb
In this script 4 queries are performed to answer the following questions:
    
    1. Which establishments have a hygiene score equal to 20?
    2. Which establishments in London have a RatingValue greater than or equal to 4?
    3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? 
    4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

For each question, the query is converted to a Pandas DataFrame.
