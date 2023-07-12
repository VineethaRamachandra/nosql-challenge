# nosql-challenge
nosql-challenge is the main directory which contains the following project files/sub-directories:

1. NoSQL_analysis_starter.ipynb -> jupyter notebook source file related 
2. noSQL_setup_starter.ipynb -> jupyter notebook source file related

3. Resources folder which contains the following json data file:
  a. establishments.json 

4. The MongoImport command that I used to import the json data file into establishments collection under uk_food database is as follows:
Mongoimport --type json -d uk_food -c establishments --drop --jsonArray "D:\RUT-DS\July-HW\nosql-challenge\nosql-challenge\Resources\establishments.json"

Above command was run from Mongosh terminal.


