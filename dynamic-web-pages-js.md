# JavaScript
- just-in-time programming language
- well-known for bases of web pages, but also utilized by in non-browser environments (i.e. Adobe)
- has the following properties:
    - prototype-based
    - multi-paradigm
    - singled-threaded
    - dynamic
    - supporting object-oriented
    - imperative
    - declarative
- standards are ECMAScript Language Specification(ECMA-262) and ECMAScript Internationalization API specification (ECMA-402)
# Input Output in plain JavaScript
- can take input from users and create output based on it
- a function in JavaScript can pull an element by its ID and return a value that a user has entered
    - function will take the input from the user and assign two new variables to the new data
    - these variables are used to create a new HTML piece and can then be displayed
# JavaScript Variables
- three ways to declare a JavaScript variable
    1. using var
    2. using let
    3. using const
## Using the var variable
- variables hold values (like in algebra)
- these variables can be used in combos/expressions
- all JavaScript variables must be identified with unique numbers call identifiers
    - criteria:
        - can contain letters, digits, underscores, and dollar signs
        - must begin with a letter
        - names can also begin with $ and _
        - names are case senstive
        - reserved words (i.e. JavaScript keywords) cannot be used
- a single = is used to assign values to variables
- two == means equal to
- variables can be numbers or text
    - text is text string
        - written with " or '
    - numbers don't need quotes (will be evaluated as text if used with quotes)
- creating a variable is called "declaring" a variable
    - will not have a value until one is assigned to it
    - can combine into "var carName = "Volvo""
    - then have to "output" value inside HTML paragraph with an id= 
- can declare many variables in one statement, separated by commas
    - can also be split into multiple lines
- can use + and - operators in JavaScript
    - using + with text strings will concatenate them