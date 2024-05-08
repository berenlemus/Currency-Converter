# Currency-Converter

## Description
This Python application allows users to convert currency amounts between different currencies. It utilizes the RapidAPI Currency Converter API to perform the conversion. The user interface is built using tkinter library, providing a simple and user-friendly interface for currency conversion.

## Features
- Convert currency amounts between various currencies including CAD, BRL, EUR, INR, USD, MXN, and JPY.
- Displays the converted amount with the respective currency symbol.
- User-friendly interface with dropdown menus and entry fields for input.

## Requirements
- tkinter library (usually comes pre-installed with Python)
- Pillow library (install using `pip install Pillow`)
- requests library (install using `pip install requests`)

## Usage
1. Run the Python script (`currency_converter.py`).
2. Select the currency you want to convert from the "From" dropdown menu.
3. Select the currency you want to convert to from the "To" dropdown menu.
4. Enter the amount you want to convert in the provided entry field.
5. Click the "Currency Converter" button to perform the conversion.
6. The converted amount will be displayed below the button with the respective currency symbol.

## Important Notes
- Ensure that you have a working Python environment with the required libraries installed (`tkinter`, `Pillow`, `requests`).
- The application uses the RapidAPI Currency Converter API for currency conversion. Make sure you have an active API key to use this service.
- Adjust the `cor0`, `cor1`, and `cor2` variables to customize the colors of the user interface.
- You can modify the list of currencies (`currency`) to include additional currencies supported by the API.
- The currency symbols for USD, INR, EUR, BRL, CAD, MXN, and JPY are predefined in the code. You can customize these symbols if needed.

## Files
- `currency_converter.py`: The main Python script.
- `icon.png`: Icon image used in the user interface.
