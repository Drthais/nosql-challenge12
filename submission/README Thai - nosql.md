# Unit 12 Homework: Eat Safe, Love

NoSQL Challenge: UK Food Standards Agency Data Evaluation
Instructions
Part 1: Database and Jupyter Notebook Set Up

1- Import Data:

2- Set Up:

Import PyMongo and pprint.

Create a Mongo Client.

Confirm uk_food database and establishments collection.

Display one document using find_one and pprint.


Part 2: Update the Database
Add New Restaurant:

Add "Penang Flavours" with the provided information.

Update BusinessTypeID:

Find and update the BusinessTypeID.

Remove Dover Establishments:

Check and remove all Dover Local Authority establishments.

Convert Data Types:

Use update_many to convert latitude, longitude, and RatingValue.


Part 3: Exploratory Analysis
Questions to Answer:

Establishments with a hygiene score of 20.

London establishments with RatingValue >= 4.

Top 5 establishments with RatingValue 5, sorted by lowest hygiene score, near "Penang Flavours".

Local Authorities with the most establishments having a hygiene score of 0.

Notes: For each question:

Use count_documents.

Display one document with pprint.

Convert to a Pandas DataFrame and display the first 10 rows.

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.