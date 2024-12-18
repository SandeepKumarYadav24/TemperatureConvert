# Temperature Converter

This project is a simple Temperature Converter that allows users to convert between Celsius and Fahrenheit.

## Features
- Convert Celsius to Fahrenheit
- Convert Fahrenheit to Celsius
- Simple and intuitive user interface
- Responsive design

## Files
- **index.html**: The main HTML file containing the structure of the Temperature Converter application.
- **style.css**: The CSS file for styling the application.
- **script.js**: The JavaScript file containing the logic for temperature conversion.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter a temperature value in either the Celsius or Fahrenheit input field.
3. Click the "Convert" button to see the converted temperature in the other input field.

## Project Structure

```
project/
|-- index.html
|-- style.css
|-- script.js
```

### index.html
- Defines the structure of the application.
- Includes two input fields for Celsius and Fahrenheit.
- Contains a button to trigger the temperature conversion.

### style.css
- Styles the application with a modern and clean design.
- Uses flexbox to center the content and responsive styling for better usability.

### script.js
- Contains the JavaScript function `convertTemperature()` to handle the conversion logic.
- Validates input to ensure it is a number.
- Alerts the user if the input is invalid.

## Example

1. Input `0` in the Celsius field and click "Convert":
   - The Fahrenheit field displays `32.00`.

2. Input `32` in the Fahrenheit field and click "Convert":
   - The Celsius field displays `0.00`.

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
