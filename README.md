# Reduction Operations Calculator

## Description

This application provides a way to calculate the minimum number of operations required to reduce a given number n to 1. The operations allowed are subtraction by 1, division by 2, and division by 3.

The JavaScript functions included in the application use dynamic programming to efficiently compute the minimum sequence of operations.

## Functions

- schet(): Reads the user's input number from an HTML element with id numberInput, calculates the required operation sequence using getOperations(n), and displays results in the HTML element with id result.

- getOperations(n): Calculates and returns the optimal sequence of operations to reduce n to 1. It uses dynamic programming to store intermediate results and minimize the computations.

## Usage

1. Make sure your HTML page has an input element with the id numberInput for the user's number n and an element with the id result to display the result.

2. Include the JavaScript code in your HTML page, either within <script> tags or as an external file.

4. Bind the schet() function to a user event, such as clicking a button, to trigger the calculation.

The program will execute and display the minimum number of operations along with the operation sequence in the designated HTML element.

## Note

This README assumes a basic understanding of HTML and JavaScript. For details about dynamic programming or JavaScript event handling, please consult additional resources.
