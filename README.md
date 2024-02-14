#README

This repository contains a Python script for analyzing parcel data using libraries such as Pandas, NumPy, Matplotlib. The script loads a dataset, performs data cleaning, and visualizes various aspects of the parcel data.

#Requirements

Python 3.x

pandas

numpy

matplotlib


#Usage

Make sure you have Python installed on your system.
Install the required libraries using pip or conda:

Clone this repository or download the script file Test Project.py

Update the path variable in the script to the location of your dataset.
Run the script using Python or jupyter Notebook:

#Description

Importing Libraries: The script begins by importing necessary libraries for data analysis and visualization.

Loading the Data: It loads the dataset from the specified path using Pandas read_csv function.

Data Cleaning: The script performs various data cleaning tasks such as handling null values, checking for duplicates, standardizing column values, and converting data types.

Data Visualization: After cleaning the data, the script visualizes different aspects of the dataset using Matplotlib. It generates plots to analyze charges based on weight, service level, carrier name, etc.

Output
The script generates several plots to visualize different aspects of parcel data:

Charges of parcels based on weight
Charges based on service level
Count of service levels
Charges of carriers for parcels weighing 4 lbs and 5 lbs
Charges of carriers for parcels weighing 5 lbs based on service level etc

