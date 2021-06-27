# Expression and Operators
- binary operator: requires 2 operands and an operator
- unary: requires 1 operand, either before or after the operator
- expression: any valid unit of code that resolves to a value
    - arithmetic: evaluates to a number
    - string: evaluates to a character string
    - logical: evaluates to true or false
    - primary expressions: basic keywords and general expressios
    - left-hand-side expressions: left values are the destination of an assignment
# Functions 
- "function" keyword, then:
    - name of function
    - a list of parameters to the function, enclosed by parentheses and separated by commas
    - the JS statements that define the function, enclosed in {}
- must define a function and then also call it
- three ways a function can refer to and call itself (recursive function)
    1. the function's name
    2. arguments.callee
    3. an in-scope variable that refers to the function
- closure: an expression (function) that can have free variables together with an environment that binds those variables
    - must preserve the arguments and variables in all scopes it references
- in nested functions:
    - the inner function can be accessed only from statements in the outer function
    - the inner functions form a closure: the inner function can use the arguments and variables of the outer function, while the outer function cannot use the arguments and variables of the inner function
# Control Flow
- order in which the computer executes statements in a script
- code is run from fist line to last line, only chnaging with conditionals and loops
# JS Functions
- function invocation --> code inside a function will execute when something invokes (calls) the function:
    - when an event occurs (i.e. when a user clicks a button)
    - when it is invoked (called) from JS code
    - automatically (self invoked)
- the function will stop executing when it reaches a "return" statement
- local variables: variables declared within a JS function (can only be accessed from within the function)
    - can use the same names within different functions
        - they are created at the beginning of a function and deleted at the end
 