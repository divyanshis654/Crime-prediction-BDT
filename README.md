 Crime Analysis Project

This project involves analyzing crime data using big data tools. It uses the dataset 'Indian_Crime_Dataset.csv' and various analytical techniques and algorithms to identify crime patterns and insights at a district level across several years.

Project Overview

The aim of this project is to develop a data-driven approach to analyze district-wise crimes in India from 2001 to 2012. By leveraging big data processing tools, this project extracts insights into crime trends and evaluates the impact of different crime types across regions.

Key Features
- Data Processing : Cleans and preprocesses data for analysis.
- Streaming : Incorporates Kafka and Spark for real-time data processing (with alternative approaches if necessary due to compatibility issues).
- Data Storage : Utilizes MongoDB for scalable storage and retrieval of processed crime data.
- Machine Learning Models : Applies classification techniques like decision trees, random forests, and logistic regression for predictive analysis on crime data.

 Project Structure

- `crime_final-2.ipynb`: The primary Jupyter Notebook for analysis, containing data loading, preprocessing, model training, and evaluation.
- `data/`: Directory containing raw and processed crime datasets.
- `scripts/`: Custom functions and helper scripts for data processing, model evaluation, and visualization.

 Technologies Used

- Apache Spark : For data processing and analysis.
- Kafka : For real-time streaming (considering alternative solutions).
- MongoDB : For storing and managing large datasets.
- Python Libraries : `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.

Getting Started:

Prerequisites

1. Apache Spark : Ensure Spark is installed and configured.
2. Kafka :  Kafka setup for streaming functionality.
3. MongoDB : Set up MongoDB and create a database for storing crime data.


Usage

1. Start Jupyter Notebook and open `crime_final-2.ipynb`.
2. Run the cells sequentially to process the data, analyze crime trends, and evaluate models.
3. For real-time processing, configure Kafka or the chosen streaming solution.

