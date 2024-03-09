Eat Safe, Love: NoSQL Project
Overview
This project was completed for UCSB Data Analytics Bootcamp. It involves analyzing data related to food establishments across the United Kingdom using MongoDB, a NoSQL database. The goal is to assist the editors of a fictional food magazine, "Eat Safe, Love," in evaluating food hygiene ratings and identifying locations of interest for future articles.

Project Structure
NoSQL_setup_starter.ipynb: Jupyter Notebook for setting up the MongoDB database, importing data, and making necessary updates to the database.
NoSQL_analysis_starter.ipynb: Jupyter Notebook for exploratory analysis of the data and answering specific questions provided by the food magazine editors.
data: Directory containing the sample data file (establishments.json) used in the project.
README.md: This file, providing an overview of the project and instructions for setup and usage.
requirements.txt: File listing the Python dependencies required for running the project.
Setup
Database Setup:

Import the provided data file (establishments.json) into MongoDB using the instructions provided in NoSQL_setup_starter.ipynb.
Confirm the successful creation of the database (uk_food) and collection (establishments) within MongoDB.
Environment Setup:

Ensure Python and the necessary dependencies (PyMongo, Pretty Print) are installed by running:
bash
Copy code
pip install -r requirements.txt
Part 1: Database Setup
Use NoSQL_setup_starter.ipynb to import data, confirm database setup, and prepare the collection for analysis.
Part 2: Update the Database
Use NoSQL_setup_starter.ipynb to make modifications to the database as per the magazine editors' requests.
Part 3: Exploratory Analysis
Utilize NoSQL_analysis_starter.ipynb to explore the dataset and find answers to specific questions posed by the food magazine editors.
Results
The project provides insights into food establishments' hygiene ratings and locations of interest based on data stored in MongoDB. The analysis assists the food magazine editors in identifying potential venues for articles.

References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
