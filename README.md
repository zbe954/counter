Counter Button
This is a simple web application that displays a counter value and allows the user to increment or reset the value.

Getting Started
To run this application, you will need a web browser that supports JavaScript. No other dependencies are required.

Usage
When the page loads, the counter value is displayed in the container element. To increment the counter value, click the "Count" button. 
To reset the counter value to zero, click the "Reset" button.

Code Overview
The code consists of the following parts:

Global variables: counterValue is used to store the current counter value.
Function renderCounterValue(): This function updates the HTML content of the container element to display the current counter value.
Function countCallback(): This function increments the counter value by one and then updates the container element to display the new value.
Function resetCallback(): This function sets the counter value to zero and then updates the container element to display the new value.
Event listeners: The "Count" button and the "Reset" button are assigned event listeners that call the countCallback() and resetCallback() functions, respectively.
Initialization: The renderCounterValue() function is called to display the initial counter value when the page loads.
Notes
The code uses the querySelector() method to select HTML elements by their class name.
The code uses the addEventListener() method to attach event listeners to HTML elements.
The code uses the innerHTML property to update the HTML content of the container element.
The code follows the conventions of modern JavaScript, including the use of arrow functions and template literals.
