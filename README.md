# nosql-challenge - Module 12 Challenge

# Overview
In this challenge, I conducted a comprehensive evaluation of the ratings data from the UK Food Standards Agency.

# Technologies
* PyMongo
* Pandas
* Pretty Print

# Part 1: Database and Jupyter Notebook Set Up
After establishing a Mongo Client instance and verifying databases and collections, I assigned the "establishments" collection to a variable for future use.
<img width="324" alt="Screenshot 2023-12-19 at 2 46 09 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/11cc30e3-d48d-48cd-ade0-ec40de1edfac">

# Part 2: Update the Database
## 1. Added specific information for a restaurant to the "establishments" collection.
<img width="511" alt="Screenshot 2023-12-19 at 2 47 25 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/588d8c1c-665b-49ca-9bb7-e79a65a9df0b">

## 2. Retrieved BusinessTypeID and BusinessType fields for "Restaurant/Cafe/Canteen."
<img width="876" alt="Screenshot 2023-12-19 at 2 48 42 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/d21ca938-44bd-4bba-8631-c5699dd751f0">

## 3. Updated the new restaurant with the found BusinessTypeID.
<img width="718" alt="Screenshot 2023-12-19 at 2 48 53 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/c294b9ca-0db2-4373-8951-25c192088d84">

## 4. Checked and removed establishments in the Dover Local Authority from the database.
<img width="494" alt="Screenshot 2023-12-19 at 2 49 54 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/d36b3def-ec67-4995-9f83-9b69e125d2e5">

## 5. Converted latitude, longitude, and RatingValue to decimal numbers and integers, respectively.
<img width="754" alt="Screenshot 2023-12-19 at 2 50 32 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/a27f2e36-ad72-4fb9-9e0d-98184cea6380">
<img width="790" alt="Screenshot 2023-12-19 at 2 50 45 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/e1fe6185-59de-4de9-afa8-1dfc563db548">

# Part 3: Exploratory Analysis
## 1. Identified establishments with a hygiene score equal to 20.
<img width="703" alt="Screenshot 2023-12-19 at 2 52 08 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/bc6e62bd-7300-4bc6-9f32-89c604b38009">

## 2. Identified establishments in London with a "RatingValue" greater than or equal to 4.
<img width="836" alt="Screenshot 2023-12-19 at 2 52 46 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/5f4c564f-41ad-4bf4-bd4e-15954f09f35a">

## 3. Identified the top 5 establishments with a "RatingValue" of 5, sorted by the lowest hygiene score, nearest to the new restaurant added, "Penang Flavours."
<img width="978" alt="Screenshot 2023-12-19 at 2 53 39 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/538f9773-f407-4d9a-821f-0e0838753de4">

## 4. Determined the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest, and printed out the top ten Local Authority areas.
<img width="465" alt="Screenshot 2023-12-19 at 2 54 22 PM" src="https://github.com/samkimmmm/nosql-challenge/assets/135805393/dac4c4ea-6a3a-458f-b4f0-12e085c22ecf">


