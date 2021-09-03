Week 1 Part 2 Homework


1. JavaScript was initially created to “make web pages alive”.

2. Add new HTML to the page, change the existing content, modify styles.
React to user actions, run on mouse clicks, pointer movements, key presses.
Send requests over the network to remote servers, download and upload files (so-called AJAX and COMET technologies).
Get and set cookies, ask questions to the visitor, show messages.

3. Document Object Model

4. ECMAScript (or ES) is a general-purpose programming language, standardised by Ecma International according to the document ECMA-262.

5. Single line comments start with //
   ex. // Change heading:

6. Multi-line comments start with /* and end with */.
`code` /*
The code below will change
the heading with id = "myH"
and the paragraph with id = "myP"
in my web page:
*/ `code`

1. The console.log() method outputs a message to the web console
   `code` console.log(obj1 [, obj2, ..., objN]);
    console.log(msg [, subst1, ..., substN]); `code`

2. The arithmetic operators perform addition, subtraction, multiplication, division, exponentiation, and modulus operations.

3.  A numeric literal is a character string selected from the digits, the plus sign, the minus sign, and the decimal point.

4.   A numerical or continuous variable (attribute) is one that may take on any value within a finite or infinite interval.

5.   Subtraction (-) Subtracts the second operand from the first.
    Multiplication (*) Multiplies one operand by the other.
    Division (/) Divides the first operand by the second.
    Modulo (%) Divides the first INTEGER operand by the second, and returns the remainder.
    Exponentiation (**) Lets you refer to a number in terms of a base value and an exponent.

6.   JavaScript has only one type of number. Numbers can be written with or without decimals.

7.  With BigInts, you can safely store and operate on large integers even beyond the safe integer limit for Numbers.

8.  An integer overflow occurs when you attempt to store inside an integer variable a value that is larger than the maximum value the variable can hold.

9.  Double-precision binary floating-point is a commonly used format on PCs, due to its wider range over single-precision floating point, in spite of its performance and bandwidth cost.

10. You can use +, *, -, **, and % with BigInts, just like with Numbers.

11. A whole number; a number that is not a fraction.

12. The quantity on which an operation is to be done.

13. `code` Number.MAX_SAFE_INTEGER ex. const x = Number.MAX_SAFE_INTEGER + 1;
     Number.MIN_SAFE_INTEGER ex. const x = Number.MIN_SAFE_INTEGER - 1; `code`

14. The toFixed() method converts a number into a string, keeping a specified number of decimals. The toPrecision() method formats a number to a specified length. It returns all digits(as per parameter value) excluding decimal point.

15. Operator precedence determines how operators are parsed concerning each other. Operators with higher precedence become the operands of operators with lower precedence.

16. 53
    Multiplication has higher precedence.

17. 28
    The parenthesis inside the parenthesis has higher precedence so you start there first. 

18. 5
    From left to right division/multiplication has more precedence over subtraction.

19. 54 
        From left to right division/multiplication has more precedence over addition.
