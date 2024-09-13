# README for Module 12 Challenge (nosql-challenge)

## Introduction

This challenge looks at food safety for the UK Food Standards Agency.  It looks at food establishments across the United Kingdom and gives them a hygiene rating. The challenge requires us to look at food ratings for the fictional magazine 'Eat, Safe, Love'. The establishment 'Penang Flavours' is added the the collection, and is compared to other establishments in the collection.

## Data

The data consists of a JSON file (establishments.json), which contains one database (uk_food) and one collection (establishments). This collection includes many food establishments across the UK, with several fields of description for each. Important fields include: co-ordinates, names, hygiene, and rating among others.

## Methodology

This challenge involves using MongoDM, Mongosh, and mostly Pymongo. These tools enable the import of the JSON file into MongoDM, and Python to parse the JSON file. Pymongo is used extensively to query and the data. Finally Pandas is also used to create DataFrames for ease of viewing the data.

## Results

The results show a wide range of hygiene and rating values across the United Kingdom. 

## Conclusion

The establishment we added in Part 1 ('Penang Flavours') is relatively close to many restaurants with good hygiene. There may be some competition for them, and should try to keep hygiene standards high to stay competitive.

## References

Class materials were used extensively for this assignment, as well as:

* stackoverflow.com
* Xpert Learning Assistant
* ChatGPT.com

## Usage

This challenge is comprised on two IPYNB files that are straight forward in usage. If there are any questions regarding Jupyter Notebooks please refer to the documentation: https://docs.jupyter.org/en/latest/
