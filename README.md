noSQL Challenge
----------
For this challenge, our task was to import JSON files (found in resources) into MongoDB, update the database, and then perform an exploratory analysis. 


**Details**
***

Part 1: Database and Jupyter Notebook Setup

Import the data provided in the establishments.json file from your Terminal and confirm that you created the database and loaded the data properly.

Part 2: Data Engineering

Update the database with a new restaurant and remove data not needed (establishments in Dover).

Part 3: Data Analysis

Conduct analysis to answer the following questions:

Which establishments have a hygiene score equal to 20?

Which establishments in London have a RatingValue greater than or equal to 4?

What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

How many establishments in each Local Authority area have a hygiene score of 0?
  

**References**
***
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
