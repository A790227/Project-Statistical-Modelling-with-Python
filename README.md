# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
1.Integrative Data Analysis: Combine data from various sources to build a comprehensive view of bike-sharing infrastructure.
2.API Proficiency: Enhance skills in working with different APIs and data formats.
3.Data Management: Learn to structure and manage data in a relational database.
4.Predictive Analytics: Develop and interpret model to understand and predict bike-sharing dynamics.
5.Comparative Analysis: Evaluate the effectiveness and completeness of different data sources.
This project provides a robust framework for understanding urban bike-sharing systems, integrating multiple data sources, and applying analytical techniques to derive actionable insights.

## Process
Part 1: Connecting to CityBikes API
	Step 1: API Exploration and Setup
	Step 2: Retrieve Bike Station Data
Part 2: Connecting to Foursquare and Yelp APIs
	Step 1: Connect to APIs
	Step 2: Retrieve and Compare POI Data
Part 3: Joining Data
	Step 1: Merge Data
	Step 2: Create and Populate SQLite Database
Part 4: Building a Model
	Step 1: Develop the Regression Model
	Step 2: Extend Analysis (Stretch)

## Results
The project likely provided insights into how bike station locations relate to the availability and quality of nearby amenities.
- Direc relation between Bike Station and Education, Art and Shopping places
The comparison between Foursquare and Yelp data highlighted differences in coverage and detail, guiding the choice of API for different types of analyses.
- Select Yelp By Database Size, categories of Yelp are more specific and Yelp API are more info associate ubication
The regression model helped uncover patterns in bike availability related to POI characteristics, with potential extensions for classification providing additional angles for exploration.
- The model is quite high, suggesting a good fit and the overall model is not statistically significant at common levels

## Challenges 
Part 1: Connecting to CityBikes API
- API Documentation and Endpoints:
Understanding the API documentation and finding the correct endpoints for retrieving data.
- Data Parsing:
Parsing JSON responses from the API and converting them into a structured Pandas DataFrame.
- Data Quality:
Ensuring the accuracy and completeness of the data retrieved from the API.

Part 2: Connecting to Foursquare and Yelp APIs
- API Authentication:
Managing API keys and handling authentication processes for both Foursquare and Yelp.
- Rate Limits and Quotas:
Handling API rate limits and quotas, which can restrict the number of requests you can make.
- Data Consistency:
Ensuring consistency between data retrieved from different APIs, especially when comparing the quality of POIs.

Part 3: Joining Data
- Data Integration:
Merging datasets with different structures and ensuring alignment between bike stations and POIs.
- Database Design:
Designing an effective SQLite database schema that supports efficient querying and storage of combined data.

Part 4: Building a Model
- Model Complexity:
Choosing the right features and handling complex relationships between bike availability and POI characteristics.
- Model Evaluation:
Interpreting the results of the regression model and ensuring it provides meaningful insights.
- Classification Extension:
Transforming the regression problem into a classification problem and defining meaningful categories.

## Future Goals

Part 1: CityBikes API Enhancements
Expand to More Cities or Countries:
Retrieve and analyze bike station data for multiple cities to gain a broader perspective.
Historical Data:
Incorporate historical bike-sharing data to analyze trends over time.

Part 2: Foursquare and Yelp API Enhancements
Extended POI Types:
Retrieve and analyze additional types of POIs beyond studied in this exercice.
Sentiment Analysis:
Perform sentiment analysis on reviews from Yelp to understand the qualitative aspects of POIs.
Real-Time Data:
Implement real-time data collection and analysis to provide up-to-date information.

Part 3: Data Joining and Database Enhancements
Advanced Database Features:
Enhance the SQLite database with advanced features such as indexing, triggers, and stored procedures.
Data Enrichment:
Enrich the dataset with additional information such as demographic data or transportation infrastructure.

Part 4: Modeling and Analysis Enhancements
Advanced Modeling Techniques:
Experiment with more advanced modeling techniques such as ensemble methods or deep learning.
Classification Model Exploration:
Further develop the classification model and explore different classification algorithms.
