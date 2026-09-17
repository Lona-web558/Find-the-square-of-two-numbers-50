# Find-the-square-of-two-numbers-50


Find the Square of Two Numbers

A simple HTML and JavaScript program that asks the user to enter two numbers and displays the result.

Description

This project demonstrates how to use:

- HTML to create a simple webpage
- CSS to style the page
- JavaScript to receive user input
- "parseFloat()" to convert input into numbers
- "window.prompt()" to ask for values
- "window.alert()" to display the result

How It Works

1. Open the HTML file in a web browser.
2. Click the Press Here button.
3. Enter the first number when prompted.
4. Enter the second number.
5. The program calculates the result.
6. The result is displayed in an alert box.

Example

If you enter:

First number: 5
Second number: 5

The program displays:

The square is: 25

Important Note

The current JavaScript calculates the product of the two numbers:

let square = num1 * num2;

If the intention is to calculate the square of each of the two numbers, you could instead use:

let square1 = num1 * num1;
let square2 = num2 * num2;

window.alert("The square of " + num1 + " is: " + square1 +
             "\nThe square of " + num2 + " is: " + square2);

Technologies Used

- HTML5
- CSS3
- JavaScript

Running the Project

Save the HTML code as a file such as:

index.html

Then open "index.html" in any modern web browser.

Project Structure

project/
│
├── index.html
└── README.md

Author

Created as a basic HTML, CSS, and JavaScript exercise.
