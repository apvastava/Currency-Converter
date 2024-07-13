# Currency Converter

This script is a simple currency converter that reads exchange rates from a file and converts a given amount in INR (Indian Rupee) to the specified foreign currency.

## Features
- Reads exchange rates from a file (`currency_data.txt`).
- Allows the user to input an amount in INR.
- Displays a list of available currencies.
- Converts the amount to the selected currency based on the exchange rates provided.

## Prerequisites
- Python 3.x
- A file named `currency_data.txt` in the same directory as the script. The file should contain currency exchange rates in the following format:

## Usage
1. Make sure you have Python installed on your system.
2. Create a `currency_data.txt` file in the same directory as your script and add the exchange rates as shown above.
3. Run the script.

## How It Works
1. The script opens and reads the `currency_data.txt` file, where each line contains a currency name and its exchange rate separated by a tab.
2. It creates a dictionary (`currencyDict`) where the key is the currency name and the value is the exchange rate.
3. It prompts the user to input an amount in INR.
4. It displays a list of available currencies that can be converted to.
5. The user selects a currency from the list.
6. The script converts the entered amount in INR to the selected currency using the exchange rate from the dictionary and prints the result.
