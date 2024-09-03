NOSQL / PYMONGO CHALLENGE

(1)	Project Overview and Purpose: This exercise aims to support the editorial team of the food magazine Eat Safe, Love in planning future articles by their journalists and food critics. The focus is on utilizing the Food Standards Agency's food hygiene ratings for various establishments across the United Kingdom (UK).

(2)	 Dataset Description: The dataset for this exercise is a file named "establishments.json" located in the Resources folder. It contains detailed information about UK establishments, including address details, business name, business type, business type ID, changes by server ID, distance, FHRSID, local authority information, new rating pending, phone number, postcode, rating date, rating key, rating value, right to reply, scheme type, identification number, geocode, links, metadata, and scores.

(3)	Data Cleaning and Preprocessing: The 'establishments' collection was updated to include a new halal restaurant in Greenwich, which is needed for the analysis but has not yet been rated. The Business Type ID for this new establishment was also updated.

Latitudes and longitudes within the geocode information were converted from string values to decimal numbers, and rating values were updated from strings to integers.

(4)	Data Visualization Techniques: DataFrames were created

(5)	Results and Analysis:
a.	Which establishments have a hygiene score equal to 20? (top ten)
-	The Chase Rest Hom
-	Brenalwood	
-	Melrose Hote
-	Seaford Pizza
-	Golden Palace
-	Ashby's Butchers
-	South Sea Express Cuisine
-	Golden Palace
-	The Tulip Tree	
-	F & S
b.	Which establishments in London have a RatingValue greater than or equal to 4? (top ten)
-	Charlie's
-	Mv City Cruises Erasmus
-	Benfleet Motor Yacht Club
-	Coombs Catering t/a The Lock and Key
-	Tilbury Seafarers Centre
-	Mv Valulla
-	Tereza Joanne	
-	Brick Lane Brews
-	The Nuance Group (UK) Limited
-	City Bar & Grill
c.	What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
-	Volunteer	
-	Plumstead Manor Nursery
-	Atlantic Fish Bar	
-	Celand
-	Howe and Co Fish and Chips - Van 17
d.	How many establishments in each Local Authority area have a hygiene score of 0?
-	 55
  
(6)	Instructions for Interacting with the Project and references:
-	Database and Jupyter Notebook Setup, and Part 2: Database Update – The code is available in the main folder as an IPYNB file titled "NoSQL_setup_Le.ipynb." 
-	 Exploratory Analysis – The code is provided in the main folder as an IPYNB file titled "NoSQL_analysis_Le.iipynb."
-	Xpert Learning Assistant
-	UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site..
