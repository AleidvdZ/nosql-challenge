# nosql-challenge

## Module 11 Challenge

## About
This challenge is to demonstrate the use of MongoDB and analyze data within an updated database. Specifically the "storyline" is that I have been hired by editors of a food manazine to evaluate food hygiene ratings data for food establishments in the UK as a tool for journalists and food critics.

The requirements are as follows:

Part 1: Database and Jupyter Notebook Set Up

Part 2: Update the Database

Part 3: Exploratory Analysis

## Process and Resources
### Timeline
0722 Created repository, cloned locally, added and commited starter files.

0724 Set up README format, completed Part 1 and most of Part 2

0725 Completed Part 2 after figuring out how to update_many on a nested dictionary. 

0725 Completed Part 3 without issues.

### Links used:
Super helpful syntax for nested dictionaries.  Solved issue with changing data types in the setup starter for longitude and latitude and also the query for Hygiene in the analysis starter: https://stackoverflow.com/questions/64784150/query-to-find-nested-dictionary-in-pymongo

Used examples from Module 12 class activities.

## Examples
Import the dataset with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
<br>  
Insert new business: <br>  
<img width="740" alt="check_insert" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/72cd0abb-2163-43b6-bafc-eeda5b3f6734">
<br>  

Updated business type id: <br>  
<img width="731" alt="updated_BusinessTypeID" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/213ccb04-d45c-4591-9590-00ebcc50ab9d">
<br>  

Checking updates to fields: <br>  
<img width="741" alt="check_field_updates" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/66dc0bfe-0d50-4240-a0c7-8697e82d18e6">
<br>  

Establishments with hygiene score of 20: <br>  
<img width="731" alt="hygiene_20" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/965089ea-8ed0-4ef8-add3-36e16bcdf42e">
<br>  

Establishements in Londing with rating of 4 or greater: <br>  
<img width="721" alt="London_4_rating" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/8e882178-dd63-4740-b990-49cbaacc709d">
<br>  

Top 5 establishments with hygiene score of 0: <br>  
<img width="740" alt="top_5" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/aa3a4472-121a-4707-a188-231f10d9fb36">
<br>  

Establishments in each Local Authority area have a hygiene score of 0: <br>  
<img width="416" alt="Hyg_0_Local_Auth" src="https://github.com/AleidvdZ/nosql-challenge/assets/131220504/ff9565c7-10cc-491e-a9d0-6806ebf56954">
<br>  

## Installing
Jupyter Notebook

PyMongo

Pretty Print

Pandas

## Contributing
Solo Challenge - Aleid van der Zel

Confirm from Panfilo Marbibi that for Question 2 there are 33 documents rather than 34 as stated in Bootcamp Spot.
 
