## nosql-challenge
This porjects consists of three parts which are database and jupyter notebook set up, update the database, and exploratory analyis.

#### Part 1: Database and Jupyter Notebook Set Up
- Import the data provided in the json file from Terminal.
- Import PyMongo and Pretty Print libraries in Jupyter Notebook.
- Create an instance of the Mongo Client.
- Confirm that the database was created and data loaded properly.
- Assign the establishments collection to a variable to prepare the collection for use.

#### Part 2: Update the Database
- Add a new document to the collection
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
- Update the new restaurant with the BusinessTypeID found.
- check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
- Change data types for some fields.

#### Part 3: Exploratory Analysis
- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a RatingValue greater than or equal to 4?
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
