"# ML-Project" 
# Real Estate: Data Integration, Cleaning API & Modeling Project



# Project Objective
This project is designed to simulate a real-world end-to-end data science and machine learning task. You will collect residential property data from two real estate APIs, perform data cleaning and integration, and then develop a predictive model to estimate property prices based on their features.
The entire process is structured to reflect the type of pipeline commonly used in industry: from raw data ingestion to a production-ready model accessible via APIs. Each component data acquisition, cleaning, integration, and modeling is modular, maintainable, and reusable.



# APIs Used for Data Collection (Assigned APIs)
•	API 1 Endpoint: https://www.attomdata.com/solutions/property-data-api/
•	API 2 used local API 




# Steps Taken in Data Collection and Cleaning

1.Generated Dummy Data via FastAPI


2.Fetched and Combined Data from Multiple Sources


3.Removed Duplicates and Null Values


4.Standardized Data Types


5.Filled in Missing Fields


6.Dropped Irrelevant or Redundant Columns


# Modeling Approach and Results

• Implemented multiple supervised learning algorithms, including Decision Tree, Random Forest, and XGBoost , to model and predict property prices based on cleaned feature data.

• Random Forest delivered the highest predictive accuracy among the tested models (see the results section in the code/notebook for detailed metrics).
