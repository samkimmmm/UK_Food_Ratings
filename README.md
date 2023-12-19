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

3. Update the new restaurant with the BusinessTypeID you found.
<img width="718" alt="Screenshot 2023-12-19 at 2 48 53 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/c294b9ca-0db2-4373-8951-25c192088d84">

4. The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.

5. Some of the number values are stored as strings, when they should be stored as numbers.
   * Use update_many to convert latitude and longitude to decimal numbers.
   * Use update_many to convert RatingValue to integer numbers.
