# nosql-challenge - Module 12 Challenge

# Overview
In this challenge, I evaluated the ratings data of the UK Food Standards Agency. 

# Technologies
* PyMongo
* Pandas
* Pretty Print

# Part 1: Database and Jupyter Notebook Set Up
After creating an instance of Mongo Client and confirming the correct databases and collections were listed, I assigned the "establishments" collection to a variable for future use.
<img width="324" alt="Screenshot 2023-12-19 at 2 46 09 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/11cc30e3-d48d-48cd-ade0-ec40de1edfac">

# Part 2: Update the Database
## 1. In the "establishments" collection, there was additional information of a specific restaurant that need to be added:
<img width="511" alt="Screenshot 2023-12-19 at 2 47 25 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/588d8c1c-665b-49ca-9bb7-e79a65a9df0b">

## 2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
<img width="876" alt="Screenshot 2023-12-19 at 2 48 42 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/d21ca938-44bd-4bba-8631-c5699dd751f0">

## 3. Update the new restaurant with the BusinessTypeID you found.
<img width="718" alt="Screenshot 2023-12-19 at 2 48 53 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/c294b9ca-0db2-4373-8951-25c192088d84">

## 4. The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted. The results were saved into a Pandas DataFrame.
<img width="494" alt="Screenshot 2023-12-19 at 2 49 54 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/d36b3def-ec67-4995-9f83-9b69e125d2e5">

## 5. Some of the number values are stored as strings, when they should be stored as numbers.
   * Use update_many to convert latitude and longitude to decimal numbers.
     <img width="754" alt="Screenshot 2023-12-19 at 2 50 32 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/a27f2e36-ad72-4fb9-9e0d-98184cea6380">

   * Use update_many to convert RatingValue to integer numbers.
     <img width="790" alt="Screenshot 2023-12-19 at 2 50 45 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/e1fe6185-59de-4de9-afa8-1dfc563db548">

# Part 3: Exploratory Analysis
## 1. Which establishments have a hygiene score equal to 20?
<img width="703" alt="Screenshot 2023-12-19 at 2 52 08 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/bc6e62bd-7300-4bc6-9f32-89c604b38009">

## 2. Which establishments in London have a "RatingValue" greater than or equal to 4?
<img width="836" alt="Screenshot 2023-12-19 at 2 52 46 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/5f4c564f-41ad-4bf4-bd4e-15954f09f35a">

## 3. What are the top 5 establishments with a "Ratingvalue" of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
<img width="978" alt="Screenshot 2023-12-19 at 2 53 39 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/538f9773-f407-4d9a-821f-0e0838753de4">

## 4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
<img width="465" alt="Screenshot 2023-12-19 at 2 54 22 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/dac4c4ea-6a3a-458f-b4f0-12e085c22ecf">


