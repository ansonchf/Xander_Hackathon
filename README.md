# Xander_Hackathon

This Python script is designed to perform various data cleaning operations on a dataset. The script is built using the pandas library to read the dataset from various file formats, including CSV, Excel, JSON, HTML, Fixed-wordth format, and API. The script also allows the user to perform operations such as removing columns, removing duplicates, filling null values, and removing outliers.

## Dependencies
This script requires the following dependencies:

pandas
requests
matplotlib
You can install these libraries via pip.

## Usage
Clone or download this repository to your local machine.
Navigate to the directory containing the script.
Ensure that you have installed the required dependencies by running pip install -r requirements.txt.
Run the script using python data_cleaning.py.
Upon running the script, you will be prompted to enter the following:

## Type of file: whether to read from a local file or an API/website.
Format of the dataset: the format of the dataset you want to read.
Column removal: whether you want to remove any columns from the dataset.
Duplicate removal: whether you want to remove any duplicate rows from the dataset.
Null value treatment: how to fill null values in the numeric columns of the dataset.
Once you have completed all of the prompts, the script will perform the selected data cleaning operations and save the cleaned dataset in a new file.
