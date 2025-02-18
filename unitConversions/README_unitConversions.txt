# Unit Conversion Web Application

## Overview
This project is a simple web application that allows users to perform basic unit conversions for temperature, weight, and distance. The application provides an interactive user interface where users can input values and get the converted results instantly.

## Features
- **Temperature Conversion**: Converts Celsius to Fahrenheit.
- **Weight Conversion**: Converts Kilograms to Pounds.
- **Distance Conversion**: Converts Kilometers to Miles.
- **User-Friendly Interface**: Provides easy-to-use input fields and buttons for conversions.

## Files Included
1. **script.js**: Contains JavaScript functions for performing conversions.
2. **unitConversions.html**: The main HTML file providing the user interface.
3. **style.css**: (Not included in the given code but assumed) Used for styling the webpage.

## Functionality
### JavaScript Functions (script.js)
1. **`temperature()`**: 
   - Converts Celsius to Fahrenheit using the formula `(C × 9/5) + 32`.
   - Takes input from an HTML input field with `id="celsius"`.
   - Displays the result in an input field with `id="fahrenheit"`.

2. **`weight()`**: 
   - Converts Kilograms to Pounds using the formula `KG × 2.2`.
   - Takes input from an HTML input field with `id="kilo"`.
   - Displays the result in an input field with `id="pounds"`.

3. **`distance()`**: 
   - Converts Kilometers to Miles using the formula `KM × 0.62137`.
   - Takes input from an HTML input field with `id="km"`.
   - Displays the result in an input field with `id="miles"`.

## How to Use
1. Open `unitConversions.html` in a web browser.
2. Use the navigation buttons to switch between temperature, weight, and distance conversion sections.
3. Enter a value in the input field and click the **Convert** button.
4. The converted value will be displayed in the respective output field.

## Example Usage
**Temperature Conversion**
- Input: `Celsius = 25`
- Output: `Fahrenheit = 77`

**Weight Conversion**
- Input: `Kilograms = 10`
- Output: `Pounds = 22`

**Distance Conversion**
- Input: `Kilometers = 5`
- Output: `Miles = 3.10685`

## Notes
- This application currently supports only three types of conversions.
- Additional unit conversions can be added by modifying the `script.js` file.
- Ensure JavaScript is enabled in your browser for the application to work properly.

## Author
This project is designed for educational purposes to demonstrate unit conversion functionality in JavaScript and HTML.