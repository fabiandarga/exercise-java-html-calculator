# Exercise Java Html Calculator
## Build a Calculator Web App using HTML and Java

In this exercise, you will create a simple calculator web app with two components:

1. A frontend HTML form where users can input two numbers and select an operation.
2. A Java backend server that will process the input and return the calculation result.

The app will perform basic arithmetic operations: addition, subtraction, multiplication, and division.

## Task 1: Create the HTML Form
**Description:**
You will create an HTML page that takes two number inputs and allows the user to select the arithmetic operation from a dropdown. Once the user submits the form, the data should be sent to the Java server for processing.
### Steps:
1. Create an HTML file (index.html).
2. Add a form with:
  * Two input fields for the numbers (num1 and num2).
  *  A dropdown (select) with four options: +, -, *, /.
  *  A submit button.

## Task 2: Set Up the Java Server
**Description:**
You will create a simple Java server that accepts requests from the HTML form. The server should:

* Parse the input values (num1, num2, and operator) sent via a GET request.
* Perform the appropriate arithmetic operation.
* Return the result as plain text.

Steps:
1. Create a new Java project.
2. Use Maven or Gradle to set up the project dependencies.
3. Add Jetty or Java HTTP Server for handling HTTP requests (here, we'll use the built-in Java HTTP server for simplicity).
4. Write a Java class that handles the incoming request, processes the input, performs the calculation, and returns the result.
