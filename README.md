# DoodleBob

Extra Credit Project for PLC 

Between a group of 6 students, we have to create our own programming language from SCRATCH. 
The language should be able to perform basic arithmetic operations (addition, subtraction, division, and multiplicaton.

We will be writing everything in Python, given that we only need to perform basic operations, writing in a high-level interpreted language wont affect efficieny. 
 
Our code is named Doodlebob and it is a programming language derived from Python that performs the opposite of arithmetic operations. Simply by following Doodlebob’s rules, if the user enters ‘+’ it will subtract, if you enter ‘*’, it will divide, etc. The only keyword we have is a variable name ‘VAR’ because this keyword is a reserved word. The operation has a short-circuit semantics so after 3+3 is entered, it will return 0 immediately. The denotation of our programming language is . We attempted to add in string literals, but the code would not run, so we had to comment out the string code in our program. Our project works by first asking the user to input text. Then the code will turn the text into its corresponding tokens, so the program can analyze the text easier. So the text “3 + 3” will be transformed to something that looks like “[INT:3, MINUS, INT:3, EOF]”. Integers will be represented by the token “INT” followed by a colon and the number it represents. Operators will also be identified as MINUS, PLUS, MUL, DIV, POW, LPAREN, etc. And at the end of the array, it will have EOF, which stands for end of file. Our code also handles errors, it will identify syntax errors, such as a missing opening parenthesis, or a missing mathematical operand. With the keyword VAR, we are able to assign values to variables, and use those variables in expressions. However, with the purpose of making our programming language be an opposite, like how DoodleBob is the opposite of SpongeBob, we made it so that it would detect ‘+’ as a minus operand, ‘-’ as an addition operand, ‘*’ as a division operand, and ‘/’ as a multiplication operand.

 
Dont be fooled, just like in SpongeBob, DoodleBob is the opposite of him. 
 
HAVE FUN !!!
