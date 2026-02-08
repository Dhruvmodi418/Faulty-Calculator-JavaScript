# Faulty-Calculator-JavaScript
Faulty Calculator JavaScript


JavaScript Project: The Faulty Calculator
This project consists of an HTML entry point and a JavaScript logic file that creates a calculator with a "glitch." It is designed to perform the correct calculation 90% of the time, while intentionally providing wrong results 10% of the time by swapping mathematical operators.

Key Features:
Probability Logic: Uses Math.random() to generate a value between 0 and 1, setting a 10% threshold for "faulty" behavior.
Operator Mapping: Utilizes a JavaScript object (obj) to store the "wrong" operator pairs, such as replacing + with - or - with /.
User Interaction: Collects data through prompt() calls for two numbers and an operation, then displays the result via alert().
Dynamic Evaluation: Employs the eval() function to parse and execute the string-based mathematical expression.
