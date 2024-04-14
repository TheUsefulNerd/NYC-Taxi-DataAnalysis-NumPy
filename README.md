# **NYC Taxi Data Analysis**

## **Overview**

This Python script analyzes New York City taxi data to derive key metrics. These metrics include:

- Mean speed of all rides
- Number of rides taken in February
- Number of rides with tips exceeding $50
- Number of rides with drop-offs at JFK Airport

## **How to Use**

1. Ensure you have Python 3.x installed on your machine.
2. Place the **`nyc_taxis.csv`** file in the same directory as the script.
3. Run the script **`analyze_taxi_data.py`**.
4. The script will output the following information in the console:
    - Mean speed of all rides
    - Number of rides taken in February
    - Number of rides with tips exceeding $50
    - Number of rides with drop-offs at JFK Airport

## **Understanding the Output**

- **Mean Speed of All Rides**: This is the average speed of all rides in miles per hour.
- **Number of Rides Taken in February**: This indicates how many rides were taken in the month of February.
- **Number of Rides with Tips Exceeding $50**: This represents the count of rides where the tip amount was greater than $50.
- **Number of Rides with Drop-offs at JFK Airport**: This tells you how many rides ended with a drop-off at JFK Airport.

## **Dataset**

The script uses the **`nyc_taxis.csv`** dataset, which contains relevant information about NYC taxi rides. Make sure this file is available in the directory before running the script.

## **Dependencies**

This script uses the **`numpy`** library for data manipulation. If you don't have **`numpy`** installed, you can install it via pip:
```python
pip install numpy
```
## **Additional Notes**

- This script assumes that the provided CSV file (**`nyc_taxis.csv`**) is correctly formatted and contains the required data fields.
- If you encounter any issues or have questions about the script, feel free to reach out.
