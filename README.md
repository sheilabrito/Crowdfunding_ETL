# Crowdfunding_ETL

## Project 2: Extract, Transform, and Load

For this project we started with with two excel files crowdfunding.xlsx and contacts.xlsx which were given to us by the Columbia bootcamp team and had a great amount of different data including contact information, categories and subcategories of croud funding. We began extracting information from these two excel files and created 4 Dataframes. First we created the Category Dataframe where we separated the categories from the subcategories and gave each category their own ID as Primary Key. Then we created the Subcategory Dataframe where we also separated the subcategories from the categories and gave each subcategory their own ID as Primary Key. We then proceeded to create the Contacts Dataframe where we included Name, Last Name, email and we also gave each contact their own ID as Primary Key. Lastly we created the Campaign Dataframe which contained information the investments made like who made them, for what amount and what category and subcategy. We also added a Primary Key fror every Campaign and added three Foreign Keys that connectred to the Contacts, Category and Subcategory Dataframes. 

We exported the 4 Dataframes to the following 4 CSV Files: category.csv, subcategory.csv, contacts.csv and campaign.csv

In order to import our CSV files to the Postgres database we created the following ERD in order to stablish the relationship between our tables and keys:

<img width="400" alt="ERD" src="https://user-images.githubusercontent.com/120340433/227254769-c115b11d-9b67-4548-81ce-1a6e977feab3.png">
