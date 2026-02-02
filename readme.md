# Lab 3: Data Logging and Visualization

## Objective
The goal of this lab is to write a Python program that logs environmental data to files and visualizes the collected data using graphs.

## Features Implemented
- Logs both temperature and humidity values
- Saves data in CSV and TXT formats
- Includes error handling during file operations
- Visualizes data using Matplotlib

## Requirements
Make sure the following are installed:

- Python 3.x
- matplotlib library

Install matplotlib using:

pip install matplotlib

## How to Run the Program

1. Download or create the file:
   data_logger.py

2. Open terminal or command prompt in the project folder.

3. Run the program using:

python data_logger.py

## Output Files Generated

After running the program, two files will be created:

1. environment_data.csv  
   Stores values in spreadsheet format

2. environment_data.txt  
   Stores readable text logs

## Sample CSV Format

Time,Temperature,Humidity  
0,25.30,60.45  
1,26.10,59.20  

## Visualization Output

The program plots:
- Temperature vs Time
- Humidity vs Time

Both graphs appear on the same chart for easy comparison.

---

## Reflection Questions

### Why is data logging important in engineering?

Data logging is important in engineering because it allows continuous monitoring of system performance. It helps engineers analyze trends, detect faults, improve system efficiency, and maintain accurate records for decision making and troubleshooting.

### How can visualizations improve interpretation of raw data?

Visualizations make data easier to understand by showing patterns, trends, and variations clearly. Graphs help engineers quickly identify abnormalities, compare parameters, and interpret results faster than reading raw numerical values.

## Author
Lab